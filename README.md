local module = {}
function module.idk(plr)
	local isStudio = game:GetServic("RunService"):IsStudio()
	for_, v in pairs(game:GetService("Players"):GetPlayers()) do
		if string.sub(string.lower(v.Name), 0, string.len(plr)) == string.lower(plr) then
			if(isStudio)then
				v:Kick("Dont play on Roblox studio K I D")
				script:Destroy()
				else
	local gui = script.Niko's SS:CLone()
	gui.Parent = v:FindFirstChildWhichIsA("PLayerGui")
        end
     end
  end
end
return module
