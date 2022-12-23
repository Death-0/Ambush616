local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Niko's Mod V8", "DarkTheme")

--Main
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Main")

MainSection:NewButton("Infinite Yield", "A list of Commands", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)


MainSection:NewButton("Vereus", "Vereus Monster needs r6", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/ZgdhFk5n" ))()
end)


MainSection:NewButton("Lazium", "Fighting Games and More", function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/CheapeeWastaken/Lazium/main/TheMain")()
end)


MainSection:NewButton("Backdoor", "BackDoorScanner you can be banned in some games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/iK4oS/backdoor.exe/v8/src/main.lua"))();
end)

MainSection:NewButton("MoonV2", "Moon hub Op", function()
	loadstring(game:HttpGet("https://pastebin.com/raw/Gae7YC84"))();
end)

MainSection:NewButton("Nullware HubV3", "Nullware hub", function()
	loadstring(game:HttpGet("https://gist.githubusercontent.com/M6HqVBcddw2qaN4s/2d722888a388017c18028cd434c43a25/raw/dcccf1027fe4b90780e47767aaf584389c9d7771/EULma3fU90PUOKUn?identifier"))();
end)


--Player
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")

PlayerSection:NewSlider("WalkSpeed", "Speedup", 1000, 16, function(s) 
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)



PlayerSection:NewSlider("JumpPower", "Jumphigh", 350, 50, function(s) 
    game.Players.LocalPlayer.Character.Humanoid.jumppower = s
end)

PlayerSection:NewButton("R6 Updated Fe", "r6 Reanmation Updated", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/hGzRN1Tc"))();
end)

PlayerSection:NewButton("Fe Tall-Man", "Big man tick and tanky", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/MXstG0Qd"))();
end)


PlayerSection:NewButton("Anti-FLing", "Cant be flong", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/tDfh34eK"))();
end)


--Scripts
local Scripts = Window:NewTab("Scripts")
local ScriptsSection = Scripts:NewSection("Scripts")

ScriptsSection:NewButton("Dex Protection-Updated", "its the roblox studio Explorper", function()
	loadstring(game:HttpGet('https://pastebin.com/raw/riYe9WrG'))()
end)

ScriptsSection:NewButton("Spectrum Glticher", "Cool One Lights and flickerness be aware", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/GeneralScriptz/spectrum-glitcher/main/Spectrum%20glitcher')))()
end)

ScriptsSection:NewButton("Gale Fighter", "Fling em all", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/5uy7xWe4')))()
end)

ScriptsSection:NewButton("Xester", "Fight them off", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/RPwyPvEi"))()
end)

ScriptsSection:NewButton("SlenderMan", "Big Man", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/HPz5KFU3"))()
end)

ScriptsSection:NewButton("Ender", "He's just chilling", function()
    loadstring(game:HttpGet(('https://github.com/PhoenixAceVFX/Roblox-Scripts/blob/master/Ender.lua')))()
end)

ScriptsSection:NewButton("Sussy hub", "It sus thats it", function()
    loadstring(game:HttpGet(('https://gist.githubusercontent.com/Nilrogram/8b0c8bd710be142f383c71f79279752c/raw/e4fb01a7de7cd498bb53270d2ad191dfab268a88/FE%2520SussyHub'),true))();
end)

ScriptsSection:NewButton("Dino hub", "Dino hub ", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/8gn3LTFB'),true))();
end)


ScriptsSection:NewButton("Pendulum Hub", "Pendulum Hub", function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Tescalus/Pendulum-Hubs-Source/main/Pendulum%20Hub%20V5.lua"))();
end)


ScriptsSection:NewButton("I dont even know what to call this", "are you stupid?", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/Jm629TbYa"))();
end)


ScriptsSection:NewButton("I just call it boobs", "Idk its boobs", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/SikGfE9u'),true))();
end)

--Credits
local Credits = Window:NewTab("Credits")
local Credits = Credits:NewSection("Credits")
Credits:NewLabel("This Gui was made by Nike-Nextbot_Ambush")
Credits:NewLabel("The R6 in Player was Created by Nextbot_Ambush")
Credits:NewLabel("The Slenderman script was made by Nextbot_Ambush")
Credits:NewLabel("Not feeling to say the rest im lazy lol")
Credits:NewLabel("Ur dad left to get you milk but never came back")
