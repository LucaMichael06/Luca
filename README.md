getgenv().Loadgui = false

if getgenv().Loadgui == false then


local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Script hub", "BloodTheme")
local Tab = Window:NewTab("Info")
local Section = Tab:NewSection("written: Luca")
local Section = Tab:NewSection("helper: MatthiasHD22 and Maxi1230111")
local Section = Tab:NewSection("Best friend: kev2345671")
local Tab = Window:NewTab("RandomScripts")
local Section = Tab:NewSection("RandomScripts")
Section:NewButton("SharkBite", "SharkBite script", function()
loadstring(game:HttpGet("https://pastebin.com/raw/YYVLbzVg", true))()
end)
Section:NewButton("ButtonText", "ButtonInfo", function()
loadstring(game:HttpGet("http://void-scripts.com/RIP/MallTycoon.lua"))()
end)
Section:NewButton("ButtonText", "ButtonInfo", function()
local library = loadstring(game:HttpGet(('https://pastebin.com/raw/FsJak6AT')))()
local w = library:CreateWindow("Mall Tycoon")
local b = w:CreateFolder("AutoFarm")
local e = w:CreateFolder("Mix")
local u = w:CreateFolder("Credits")

--Toggle
b:Toggle("AutoCollectButtons",function(bool)
    shared.toggle = bool
    AutoBuy = bool
end)

b:Toggle("AutoSelectStore",function(bool)
    shared.toggle = bool
    AutoSelectStore = bool
end)

b:Toggle("AutoRebirth",function(bool)
    shared.toggle = bool
    AutoRebirth = bool
end)

e:Toggle("AntiAfk",function(bool)
    shared.toggle = bool
    AntiAfk = bool
end)
local Tab = Window:NewTab("MurderMystery2")
local Section = Tab:NewSection("MurderMystery2")
Section:NewButton("MurderMystery", "The best MurderMystery script", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Doggo-cryto/EclipseMM2/master/Script", true))()
end)
Section:NewButton("MurderMystery", "The 2 best script", function()
loadstring(game:GetObjects("rbxassetid://6193945654")[1].Source)()
end)
Section:NewButton("MurderMystery", "Not the best script", function()
loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)
local Tab = Window:NewTab("BloxFruit Scripts")
local Section = Tab:NewSection("BloxFruit Scripts")
Section:NewButton("BloxFruit", "I think the best script for BloxFruit", function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/koonpeatch/PeatEX/master/BKHAX/BloxFruits"),true))()
end)
local Tab = Window:NewTab("ScriptHub")
local Section = Tab:NewSection("ScriptHub")
Section:NewButton("CMD-X", "admin", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
end)
Section:NewButton("bruhHub", " Good for ShindoLife", function()
loadstring(game:HttpGet("https://bruh.keshhub.com/.lua"))()
end)
Section:NewButton("Infinite yield", "Admin", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
local Tab = Window:NewTab("Player")
local Section = Tab:NewSection("Player")
Section:NewSlider("WalkSpeed", "SliderInfo", 250, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
Section:NewSlider("JumpPower", "SliderInfo", 500, 50, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)
Section:NewButton("BloxHub", "Working not in all games", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/BloxiYT/BloxHub-v2/main/Main"))()
end)
Section:NewKeybind("Toggle gui", "Make you gui invisible", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)
end
