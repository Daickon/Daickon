 local plr = game.Players.LocalPlayer
 local UIS = game:GetService("UserInputService")
 local crease = 1

   UIS.InputBegan:Connect(function(input , IS) if IS == true then return end



        if input.UserInputType == Enum.UserInputType.MouseButton1 then

            if crease == 1 then 
			   crease += 1  local animation = plr.Character.Humanoid:LoadAnimation(script.Animation) wait(0.2) animation:Play() wait(0.2) local mmp = game.Workspace.mmp game.Workspace.mmp.CFrame = plr.Character.RightHand.CFrame wait(0.1)  game.Workspace.mmp.CFrame = game.Workspace.Baseplate.CFrame elseif crease == 2  then  crease += 1  local gayka = plr.Character.Humanoid:LoadAnimation(script.animation) wait(0.2) gayka:Play() wait(0.2) local mmi = game.Workspace.mmp game.Workspace.mmp.CFrame = plr.Character.LeftHand.CFrame wait(0.1) game.Workspace.mmp.CFrame = game.Workspace.Baseplate.CFrame elseif crease == 3 then crease += 1 local amimbo = plr.Character.Humanoid:LoadAnimation(script.amimbo) wait(0.2) amimbo:Play() wait(0.2) local mmc = game.Workspace.mmp game.Workspace.mmp.CFrame = plr.Character.LeftFoot.CFrame wait(0.1)  game.Workspace.mmp.CFrame = game.Workspace.Baseplate.CFrame elseif crease == 4 then crease += 1 local kenko = plr.Character.Humanoid:LoadAnimation(script.kago) wait(0.2) kenko:Play()  wait(0.2) local mmn = game.Workspace.mmp game.Workspace.mmp.CFrame = plr.Character.RightFoot.CFrame wait(0.1) game.Workspace.mmp.CFrame = game.Workspace.Baseplate.CFrame   elseif crease == 5 then local mtp = plr.Character.Humanoid:LoadAnimation(script.mtpp) wait(0.2) mtp:Play() wait(0.2) local mmx = game.Workspace.mmv game.Workspace.mmv.CFrame = plr.Character.LeftFoot.CFrame wait(0.1) game.Workspace.mmv.CFrame = game.Workspace.Baseplate.CFrame crease = 1   end   end
	
	
    
		if input.KeyCode == Enum.KeyCode.F then while UIS:IsKeyDown(input.KeyCode) do crease = 0 wait(0.1) end crease = 1 end
		

       
   end)


  
