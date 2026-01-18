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
