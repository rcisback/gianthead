for i,v in pairs(game.Players.LocalPlayer.Character.Humanoid:GetChildren()) do
   if string.find(v.Name,"Scale") and v.Name ~= "HeadScale" then
       repeat wait(HeadGrowSpeed) until game.Players.LocalPlayer.Character.Head:FindFirstChild("OriginalSize")
       game.Players.LocalPlayer.Character.Head.OriginalSize:Destroy()
       v:Destroy()
       game.Players.LocalPlayer.Character.Head:WaitForChild("OriginalSize")
   end
end
