local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("JAK X HUB", "DarkTheme")

local Tab = Window:NewTab("Blox fruits")
local Section = Tab:NewSection("Blox fruits Mobile/Pc")

Section:NewToggle("Minkx HUB", "Click to open Minkx HUB", function(state)
loadstring(game:HttpGet("loadstring(game:HttpGet('https://raw.githubusercontent.com/Beammodz/Minkx/main/Hub/Main/Lua/FreeScript/Mobile"))();
end)

local Section = Tab:NewSection("Auto fram Mobile/Pc")

Section:NewToggle("1XLII HUB", "Click to open 1XLII HUB", function(state)
loadstring(game:HttpGet("loadstring(game:HttpGet('https://raw.githubusercontent.com/armch063/BF-1XLIIHUB-V3/main/README.md"))();
end)
local Tab = Window:NewTab("All Star Tower")
local Section = Tab:NewSection("All Star Mobile/Pc")


Section:NewToggle("All Star HUB", "Click to open All Star HUB", function(state)
loadstring(game:HttpGet("http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))();
end)

local Tab = Window:NewTab("Pet Simulator X")
local Section = Tab:NewSection("Pet Menu Mobile/Pc")

Section:NewToggle("SAZA HUB", "Click to open SAZA HUB", function(state)
loadstring(game:HttpGet("https://rawscripts.net/raw/SAZA-HUB_496"))();
end)

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)

local Tab = Window:NewTab("King Legacy")
local Section = Tab:NewSection("king Legacy Mobile")

Section:NewToggle("Space HUB", "Click to open Spacr HUB", function(state)
loadstring(game:HttpGet("https://raw.githubusercontent.com/sadwawin/KINGLAGACY/main/README.md"))();
end)

local Section = Tab:NewSection("king Legacy Pc")


Section:NewToggle("Ripper HUB", "Click to open Ripper HUB", function(state)
loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/King%20Leagacy"))();
end)
