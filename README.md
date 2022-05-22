local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("JAK X HUB", "DarkTheme")

local Tab = Window:NewTab("Blox Fruits")
local Section = Tab:NewSection("Auto Fram")
local Section = Tab:NewSection("Auto Black leg v2")
local Section = Tab:NewSection("Auto Electro v2")
local Section = Tab:NewSection("Auto Dragon Claw v2")
local Section = Tab:NewSection("Auto Super human")

local Tab = Window:NewTab("All Star Tower")
local Section = Tab:NewSection("Kill Mob")
local Section = Tab:NewSection("Auto Summon")
local Section = Tab:NewSection("Auto Start")

local Tab = Window:NewTab("Pet Simulator X")
local Section = Tab:NewSection("Auto Summon Pet")
local Section = Tab:NewSection("Auto Chest")
local Section = Tab:NewSection("Auto Fram")

local Tab = Window:NewTab("Admin")
local Section = Tab:NewSection("Admin")


 Section:NewButton("Admin 500+", "Infinite Yield", function()
local AnnGUI = Instance.new("Frame")
local background = Instance.new("Frame")
local TextBox = Instance.new("TextLabel")
local shadow = Instance.new("Frame")
local PopupText = Instance.new("TextLabel")
local Exit = Instance.new("ImageButton")

screenGui = Instance.new("ScreenGui",game.CoreGui)

AnnGUI.Name = 'Boomer'
AnnGUI.Parent = screenGui
AnnGUI.Active = true
AnnGUI.BackgroundTransparency = 1
AnnGUI.Position = UDim2.new(0.5, -180, 0, -400)
AnnGUI.Size = UDim2.new(0, 360, 0, 20)
AnnGUI.ZIndex = 4

background.Name = "background"
background.Parent = AnnGUI
background.BackgroundColor3 = Color3.fromRGB(36, 36, 37)
background.BorderSizePixel = 0
background.Position = UDim2.new(0, 0, 0, 20)
background.Size = UDim2.new(0, 360, 0, 135)

TextBox.Parent = background
TextBox.BackgroundTransparency = 1
TextBox.Position = UDim2.new(0.017, 0, 0.06, 0)
TextBox.Size = UDim2.new(0, 348, 0, 120)
TextBox.Font = Enum.Font.SourceSans
TextBox.TextSize = 18
TextBox.TextWrapped = true
TextBox.Text = 'Please use the new Infinite Yield loadstring. You can find it in the Discord.\n\ndiscord.io/infiniteyield\n\nYou will now be re-directed to the new loadstring.'
TextBox.TextColor3 = Color3.new(1, 1, 1)
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

shadow.Name = "shadow"
shadow.Parent = AnnGUI
shadow.BackgroundColor3 = Color3.fromRGB(46, 46, 47)
shadow.BorderSizePixel = 0
shadow.Size = UDim2.new(0, 360, 0, 20)
shadow.ZIndex = 4

PopupText.Name = "PopupText"
PopupText.Parent = shadow
PopupText.BackgroundTransparency = 1
PopupText.Position = UDim2.new(0, 51, 0, 0)
PopupText.Size = UDim2.new(0.76, -16, 0.95, 0)
PopupText.ZIndex = 4
PopupText.Font = Enum.Font.SourceSans
PopupText.TextSize = 14
PopupText.Text = "Server Announcement"
PopupText.TextColor3 = Color3.new(1, 1, 1)
PopupText.TextWrapped = true

Exit.Name = "Exit"
Exit.Parent = shadow
Exit.BackgroundTransparency = 1
Exit.Size = UDim2.new(0, 20, 0, 20)
Exit.ZIndex = 4
Exit.Image = "rbxassetid://2132544126"

wait(1)
AnnGUI:TweenPosition(UDim2.new(0.5, -180, 0, 150), "InOut", "Quart", 0.5, true, nil)

Exit.MouseButton1Click:Connect(function()
 AnnGUI:TweenPosition(UDim2.new(0.5, -180, 0, -400), "InOut", "Quart", 0.5, true, nil)
 wait(0.6)
 AnnGUI:Destroy()
end)

wait(5)
loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)
