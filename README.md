local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Niko's Mod V10.3", "DarkTheme")

--Main
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Main")


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
    game.Players.LocalPlayer.Character.Humanoid.jumpPower = s
end)

PlayerSection:NewButton("R6 Updated Fe", "r6 Reanmation Updated", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/hGzRN1Tc"))();
end)

PlayerSection:NewButton("Fe Tall-Man", "Big man tick and tanky", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/MXstG0Qd"))();
end)


PlayerSection:NewButton("Anti-Fling", "Cant be flong", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/tDfh34eK"))();
end)


--Hubs
local Hubs = Window:NewTab("Hubs")
local HubsSection = Hubs:NewSection("Hubs")

HubsSection:NewButton("Dex V2", "its ur mom", function()
	loadstring(game:HttpGet('https://pastebin.com/raw/riYe9WrG'))()
end)



HubsSection:NewButton("Sussy hub R6", "It sus thats it", function()
    loadstring(game:HttpGet(('https://gist.githubusercontent.com/Nilrogram/8b0c8bd710be142f383c71f79279752c/raw/e4fb01a7de7cd498bb53270d2ad191dfab268a88/FE%2520SussyHub'),true))();
end)

HubsSection:NewButton("Dino hub", "Dino hub ", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/8gn3LTFB'),true))();
end)


HubsSection:NewButton("Pendulum Hub", "Opens Pendulum Hub", function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Tescalus/Pendulum-Hubs-Source/main/Pendulum%20Hub%20V5.lua"))();
end)


HubsSection:NewButton("A Gui Thats All", "are you stupid?", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/Jm629TbY"))();
end)


HubsSection:NewButton("T0PK0K Diffrent 3.0", "Opens up T0PKOK 3.0", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/SikGfE9u'),true))();
end)


HubsSection:NewButton("Server-Sided Executor", "The name says it", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/RG3a7UG6'),true))();
end)


HubsSection:NewButton("Dex v5", "OPENS up dex v5 ", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/dyyll/Dex-V5-leak/main/Dex%20V5.lua'),true))();
end)


HubsSection:NewButton("BackdoorScan", "Backdoor scan to see if game backdoored", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/1Pg0xW6J'),true))();
end)

HubsSection:NewButton("Turtle Spy", "Opens up Turtle spy", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/zzerexx/scripts/main/TurtleSpy.lua'),true))();
end)


--Other
local Other = Window:NewTab("Other")
local Other = Other:NewSection("Other")

Other:NewButton("Spectrum Glticher R6", "Cool One Lights and flickerness be aware", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/GeneralScriptz/spectrum-glitcher/main/Spectrum%20glitcher')))()
end)

Other:NewButton("Gale Fighter R6", "Fling em all R6", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/5uy7xWe4')))()
end)

Other:NewButton("Xester R6", "Fight them off R6", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/RPwyPvEi"))()
end)

Other:NewButton("SlenderMan", "Big Man", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/HPz5KFU3"))()
end)

Other:NewButton("Ender R6 ", "He's just chilling", function()
    loadstring(game:HttpGet(('https://github.com/PhoenixAceVFX/Roblox-Scripts/blob/master/Ender.lua')))()
end)


--Admin
local Admin = Window:NewTab("Admin")
local AdminSection = Admin:NewSection("Admin")

AdminSection:NewButton("Infinite Yield", "A list of Commands", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

AdminSection:NewButton("Reviz admin", "Commands", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/9dsrirD5"))();
end)


AdminSection:NewButton("Fates admin", "Commands", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end)

AdminSection:NewButton("ShatterVast admin", "Commands", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end)

AdminSection:NewButton("CMD-X admin", "CMDX-X Commands", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
end)


--Credits
local Credits = Window:NewTab("Credits")
local Credits = Credits:NewSection("Credits")
Credits:NewLabel("This Gui was made by Nike-Nextbot_Ambush")
Credits:NewLabel("The R6 in Player was Created by Nextbot_Ambush")
Credits:NewLabel("The Slenderman script was made by Nextbot_Ambush")
Credits:NewLabel("Not feeling to say the rest im lazy lol")
Credits:NewLabel("Ur dad left to get you milk but never came back")
