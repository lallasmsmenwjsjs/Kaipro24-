local scriptFunc = function()
    local Player = game.Players.LocalPlayer
    local Character = Player.Character or Player.CharacterAdded:Wait()
    local RunService = game:GetService("RunService")

    while true do
        Character.HumanoidRootPart.CFrame = CFrame.new(100, 10, 100)
        print("Auto farming target...")
        wait(1)
    end
end

loadstring(string.dump(scriptFunc))()
