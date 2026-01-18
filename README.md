# hub.lua
print("Miranda hub")
config.lua main.luaui.luafunctions.lua
local btn = script.Parent:WaitForChild("TextButton")
local player = game.Players.LocalPlayer
local humanoid = player.Character or player.CharacterAdded:Wait():WaitForChild("Humanoid")

btn.MouseButton1Click:Connect(function()
	humanoid.WalkSpeed = 32
end)
local btn = script.Parent:WaitForChild("TextButton")
local p = game.Players.LocalPlayer
local h = p.Character or p.CharacterAdded:Wait():WaitForChild("Humanoid")

btn.MouseButton1Click:Connect(function()
	h.JumpPower = 100
end)
StarterGui
 └─ ScreenGui
    ├─ TextButton (Velocidade)
    │  └─ LocalScript
    └─ TextButton (Pulo)
       └─ LocalScript




	   -- MIRANDA HUB LOADER (LEGAL)

local player = game.Players.LocalPlayer
local char = player.Character or player.CharacterAdded:Wait()
local humanoid = char:WaitForChild("Humanoid")

-- CONFIG
local SPEED = 32
local JUMP = 100

-- EXECUTA AUTOMATICO
humanoid.WalkSpeed = SPEED
humanoid.JumpPower = JUMP

print("HUB UNIVERSAL")
