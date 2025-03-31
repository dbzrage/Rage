# Rage
local Players = game:GetService("Players") local LocalPlayer = Players.LocalPlayer repeat task.wait() until LocalPlayer.Character and LocalPlayer.Character:FindFirstChild("Humanoid") print("Funcionou! Velocidade aumentada.") LocalPlayer.Character.Humanoid.WalkSpeed = 100
