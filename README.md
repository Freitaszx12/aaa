game.Players.PlayerAdded:Connect(function(player)
    if player.Name == "Akira" then
        player:Kick("você foi banido")
    end
end)
