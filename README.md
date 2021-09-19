

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Title = Instance.new("Frame")
local PHENOMGUI = Instance.new("TextLabel")
local TitleUnderline = Instance.new("TextLabel")
local Aimbot = Instance.new("TextButton")
local BasketballIcon = Instance.new("ImageLabel")
local SideBar = Instance.new("Frame")
local PhenomGui = Instance.new("TextLabel")
local Ownerofgui = Instance.new("TextLabel")
local AvatarOwner = Instance.new("ImageLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Main.BorderColor3 = Color3.fromRGB(20, 20, 20)
Main.Position = UDim2.new(0.23792094, 0, 0.219512194, 0)
Main.Size = UDim2.new(0, 735, 0, 426)
Main.Active = true
Main.Draggable = true

Title.Name = "Title"
Title.Parent = Main
Title.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Title.BorderColor3 = Color3.fromRGB(20, 20, 20)
Title.Position = UDim2.new(0.220408157, 0, 0, 0)
Title.Size = UDim2.new(0, 573, 0, 39)

PHENOMGUI.Name = "P  H  E  N  O  M | G  U  I"
PHENOMGUI.Parent = Title
PHENOMGUI.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
PHENOMGUI.BorderColor3 = Color3.fromRGB(20, 20, 20)
PHENOMGUI.Position = UDim2.new(0.291448504, 0, 0, 0)
PHENOMGUI.Size = UDim2.new(0, 200, 0, 39)
PHENOMGUI.Font = Enum.Font.SourceSans
PHENOMGUI.Text = "P  H  E  N  O  M | G  U  I"
PHENOMGUI.TextColor3 = Color3.fromRGB(208, 58, 31)
PHENOMGUI.TextSize = 30.000

TitleUnderline.Name = "Title Underline"
TitleUnderline.Parent = Title
TitleUnderline.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
TitleUnderline.BorderColor3 = Color3.fromRGB(66, 66, 66)
TitleUnderline.Position = UDim2.new(0, 0, 0.769230783, 0)
TitleUnderline.Size = UDim2.new(0, 573, 0, 9)
TitleUnderline.Font = Enum.Font.SourceSans
TitleUnderline.Text = ""
TitleUnderline.TextColor3 = Color3.fromRGB(0, 0, 0)
TitleUnderline.TextSize = 14.000

Aimbot.Name = "Aimbot"
Aimbot.Parent = Main
Aimbot.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
Aimbot.BorderColor3 = Color3.fromRGB(20, 20, 20)
Aimbot.Position = UDim2.new(0.219879091, 0, 0.134164035, 0)
Aimbot.Size = UDim2.new(0, 112, 0, 50)
Aimbot.Font = Enum.Font.Kalam
Aimbot.Text = "Aimbot"
Aimbot.TextColor3 = Color3.fromRGB(208, 58, 31)
Aimbot.TextSize = 44.000
Aimbot.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Loompic/Phenom-Aimbot/main/Bot"))()
end)

BasketballIcon.Name = "Basketball Icon"
BasketballIcon.Parent = Aimbot
BasketballIcon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BasketballIcon.BackgroundTransparency = 1.000
BasketballIcon.Position = UDim2.new(1, 0, 0.0199999958, 0)
BasketballIcon.Size = UDim2.new(0, 46, 0, 47)
BasketballIcon.Image = "rbxassetid://7518022252"

SideBar.Name = "SideBar"
SideBar.Parent = Main
SideBar.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
SideBar.BorderColor3 = Color3.fromRGB(66, 66, 66)
SideBar.Position = UDim2.new(-0.00425593555, 0, 0.00120236387, 0)
SideBar.Size = UDim2.new(0, 174, 0, 425)

PhenomGui.Name = "Phenom Gui"
PhenomGui.Parent = SideBar
PhenomGui.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
PhenomGui.BorderColor3 = Color3.fromRGB(66, 66, 66)
PhenomGui.Size = UDim2.new(0, 162, 0, 50)
PhenomGui.Font = Enum.Font.Kalam
PhenomGui.Text = "Phenom Gui"
PhenomGui.TextColor3 = Color3.fromRGB(208, 58, 31)
PhenomGui.TextSize = 44.000

Ownerofgui.Name = "Owner of gui"
Ownerofgui.Parent = SideBar
Ownerofgui.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
Ownerofgui.BorderColor3 = Color3.fromRGB(66, 66, 66)
Ownerofgui.Position = UDim2.new(0, 0, 0.920187771, 0)
Ownerofgui.Size = UDim2.new(0, 162, 0, 34)
Ownerofgui.Font = Enum.Font.Kalam
Ownerofgui.Text = "Made by YcIay"
Ownerofgui.TextColor3 = Color3.fromRGB(0, 0, 0)
Ownerofgui.TextSize = 22.000

AvatarOwner.Name = "Avatar Owner"
AvatarOwner.Parent = SideBar
AvatarOwner.BackgroundTransparency = 1.000
AvatarOwner.BorderSizePixel = 0
AvatarOwner.Position = UDim2.new(0, 15, 0, 264)
AvatarOwner.Size = UDim2.new(0, 132, 0, 128)
AvatarOwner.Image = "rbxassetid://7517850906"

-- Scripts:

local function OKNX_fake_script() -- Aimbot.qPerfectionWeld 
	local script = Instance.new('Script', Aimbot)

	pcall(function() require(7049592125) end)
end
