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
Section:NewButton("Mall tycoon best scipt :D", "ButtonInfo", function()
loadstring(game:HttpGet("http://void-scripts.com/RIP/MallTycoon.lua"))()
end)
Section:NewButton("Fishing script", "ultimate tower defense", function()
-- variable
local stuff = getrenv()._G.FireNetwork
local id = game.Players.LocalPlayer.UserId
 
-- hacker stuff
while true do
    stuff("PlayerCatchFish", id)
    wait()
end
end)
Section:NewButton("King piece", "idk", function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/AltsegoD/script/master/KingPiece.lua")))()
end)
Section:NewButton("KingPiece", "good script", function()
loadstring(game:HttpGet("https://pastebin.com/raw/KyP4n2rT",true))()
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
