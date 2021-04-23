getgenv().Loadgui = false

if getgenv().Loadgui == false then


local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("LUCAS_HUB", "Sentinel")
local Tab = Window:NewTab("main")
local Section = Tab:NewSection("main")
Section:NewButton("SharkBite", "SharkBite script", function()
loadstring(game:HttpGet("https://pastebin.com/raw/YYVLbzVg", true))()
end)
Section:NewButton("MurderMystery", "MurderMystery script", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Doggo-cryto/EclipseMM2/master/Script", true))()
end)
Section:NewButton("ShindoLife", "ShindoLife script", function()
loadstring(game:HttpGet("https://bruh.keshhub.com/.lua"))()
end)
local Tab = Window:NewTab("Player")
local Section = Tab:NewSection("Player")
loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
Section:NewSlider("WalkSpeed", "SliderInfo", 250, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
Section:NewSlider("JumpPower", "SliderInfo", 500, 50, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)
Section:NewKeybind("Toggle gui", "Make you gui invisible", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)
end
