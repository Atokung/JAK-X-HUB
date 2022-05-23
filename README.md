local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("JAK X HUB", "DarkTheme")

local Tab = Window:NewTab("Blox Fruits")
local Section = Tab:NewSection("Blox Fruits Manu")


Section:NewToggle("1XLIIHUB V3", "Click to open 1XLII HUB V3)", function(state)
loadstring(game:HttpGet('https://raw.githubusercontent.com/armch063/BF-1XLIIHUB-V3/main/README.md
end)

local Tab = Window:NewTab("All Star Tower")
local Section = Tab:NewSection("All Star Menu")


Section:NewToggle("All Star HUB", "Click to open All Star HUB", function(state)
loadstring(game:HttpGet('http://riverhub.xyz/" .. tostring(game.PlaceId) .. ".lua"))()
end)

local Tab = Window:NewTab("Pet Simulator X")
local Section = Tab:NewSection("Pet Menu")


Section:NewToggle("SAZA HUB", Click to open SAZA HUB", function(state)
loadstring(game:HttpGet"https://www.scriptblox.com/raw/SAZA-HUB_496")()
end)
Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)
