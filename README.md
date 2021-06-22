
local args = {
    [1] = "AnimationPack",
    [2] = "Greet"
}

game:GetService("ReplicatedStorage").MainEvent:FireServer(unpack(args))
