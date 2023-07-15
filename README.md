while true do wait()
local args = {
    [1] = workspace:WaitForChild("map"):WaitForChild("dummies"):WaitForChild("TrainingDummy"):WaitForChild("Humanoid")
}

game:GetService("ReplicatedStorage"):WaitForChild("DamageEvent"):FireServer(unpack(args))
end
