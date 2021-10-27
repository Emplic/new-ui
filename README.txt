local AudioIds = {537744814}


	local Sound2 = Instance.new("Sound", nil)
	local c = getconnections(game:GetService("PolicyService").ChildAdded)
	for i,v in pairs(c) do v:Disable() end
	Sound2.Parent = game:GetService("PolicyService")
	for i,v in pairs(c) do v:Enable() end
	Sound2.Name = "19324854"
	Sound2.SoundId = "http://www.roblox.com/asset/?id="..AudioIds[1]
	Sound2:Play()

local ChillHub = Instance.new("Frame")
local HomeTab = Instance.new("TextButton")
local ImageLabel = Instance.new("ImageLabel")
local c = Instance.new("TextLabel")
local h = Instance.new("TextLabel")
local I = Instance.new("TextLabel")
local L1 = Instance.new("TextLabel")
local L2 = Instance.new("TextLabel")
local H2 = Instance.new("TextLabel")
local U = Instance.new("TextLabel")
local B = Instance.new("TextLabel")
local ExpanderHome = Instance.new("Frame")
local Executor = Instance.new("TextButton")
local ImageLabel_2 = Instance.new("ImageLabel")
local HomeInformation = Instance.new("ScrollingFrame")
local Welcome = Instance.new("TextLabel")
local Playername = Instance.new("TextLabel")
local PlayersImage = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local Logs = Instance.new("TextLabel")
local madeby = Instance.new("TextLabel")
local madeby_2 = Instance.new("TextLabel")
local madeby_3 = Instance.new("TextLabel")

--Properties:

ChillHub.Name = "ChillHub"
ChillHub.Parent = game.CoreGui
ChillHub.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
ChillHub.BorderColor3 = Color3.fromRGB(25, 25, 25)
ChillHub.Position = UDim2.new(0.44720903, 0, 0.0401284099, 0)
ChillHub.Size = UDim2.new(0, 469, 0, 538)

HomeTab.Name = "Home Tab"
HomeTab.Parent = ChillHub
HomeTab.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
HomeTab.BackgroundTransparency = 1.000
HomeTab.Position = UDim2.new(0.0733137876, 0, 0.0780952349, 0)
HomeTab.Size = UDim2.new(0, 107, 0, 31)
HomeTab.Font = Enum.Font.TitilliumWeb
HomeTab.Text = "Home"
HomeTab.TextColor3 = Color3.fromRGB(255, 32, 117)
HomeTab.TextScaled = true
HomeTab.TextSize = 20.000
HomeTab.TextWrapped = true

ImageLabel.Parent = HomeTab
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(26, 53, 31)
ImageLabel.Position = UDim2.new(-0.158878505, 0, -0.0322580636, 0)
ImageLabel.Size = UDim2.new(0, 41, 0, 35)
ImageLabel.Image = game.Players:GetUserThumbnailAsync(game.Players.LocalPlayer.UserId,Enum.ThumbnailType.HeadShot,Enum.ThumbnailSize.Size420x420)
ImageLabel.ImageColor3 = Color3.fromRGB(195, 53, 255)

c.Name = "c"
c.Parent = ChillHub
c.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
c.BackgroundTransparency = 1.000
c.Size = UDim2.new(0, 41, 0, 33)
c.Font = Enum.Font.TitilliumWeb
c.Text = "C"
c.TextColor3 = Color3.fromRGB(158, 78, 255)
c.TextScaled = true
c.TextSize = 14.000
c.TextWrapped = true

h.Name = "h"
h.Parent = ChillHub
h.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
h.BackgroundTransparency = 1.000
h.Position = UDim2.new(0.0733137801, 0, 0, 0)
h.Size = UDim2.new(0, 41, 0, 33)
h.Font = Enum.Font.TitilliumWeb
h.Text = "H"
h.TextColor3 = Color3.fromRGB(158, 78, 255)
h.TextScaled = true
h.TextSize = 14.000
h.TextWrapped = true

I.Name = "I"
I.Parent = ChillHub
I.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
I.BackgroundTransparency = 1.000
I.Position = UDim2.new(0.143695012, 0, 0, 0)
I.Size = UDim2.new(0, 41, 0, 33)
I.Font = Enum.Font.TitilliumWeb
I.Text = "I"
I.TextColor3 = Color3.fromRGB(158, 78, 255)
I.TextScaled = true
I.TextSize = 14.000
I.TextWrapped = true

L1.Name = "L 1"
L1.Parent = ChillHub
L1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
L1.BackgroundTransparency = 1.000
L1.Position = UDim2.new(0.225806445, 0, 0, 0)
L1.Size = UDim2.new(0, 41, 0, 33)
L1.Font = Enum.Font.TitilliumWeb
L1.Text = "L"
L1.TextColor3 = Color3.fromRGB(158, 78, 255)
L1.TextScaled = true
L1.TextSize = 14.000
L1.TextWrapped = true

L2.Name = "L 2"
L2.Parent = ChillHub
L2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
L2.BackgroundTransparency = 1.000
L2.Position = UDim2.new(0.31378299, 0, 0, 0)
L2.Size = UDim2.new(0, 41, 0, 33)
L2.Font = Enum.Font.TitilliumWeb
L2.Text = "L"
L2.TextColor3 = Color3.fromRGB(158, 78, 255)
L2.TextScaled = true
L2.TextSize = 14.000
L2.TextWrapped = true

H2.Name = "H 2"
H2.Parent = ChillHub
H2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
H2.BackgroundTransparency = 1.000
H2.Position = UDim2.new(0.466275662, 0, 0, 0)
H2.Size = UDim2.new(0, 41, 0, 33)
H2.Font = Enum.Font.TitilliumWeb
H2.Text = "H"
H2.TextColor3 = Color3.fromRGB(158, 78, 255)
H2.TextScaled = true
H2.TextSize = 14.000
H2.TextWrapped = true

U.Name = "U"
U.Parent = ChillHub
U.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
U.BackgroundTransparency = 1.000
U.Position = UDim2.new(0.56891495, 0, 0, 0)
U.Size = UDim2.new(0, 41, 0, 33)
U.Font = Enum.Font.TitilliumWeb
U.Text = "U"
U.TextColor3 = Color3.fromRGB(158, 78, 255)
U.TextScaled = true
U.TextSize = 14.000
U.TextWrapped = true

B.Name = "B"
B.Parent = ChillHub
B.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
B.BackgroundTransparency = 1.000
B.Position = UDim2.new(0.689149559, 0, 0, 0)
B.Size = UDim2.new(0, 41, 0, 33)
B.Font = Enum.Font.TitilliumWeb
B.Text = "B"
B.TextColor3 = Color3.fromRGB(158, 78, 255)
B.TextScaled = true
B.TextSize = 14.000
B.TextWrapped = true

ExpanderHome.Name = "Expander Home"
ExpanderHome.Parent = ChillHub
ExpanderHome.BackgroundColor3 = Color3.fromRGB(32, 32, 32)
ExpanderHome.BorderColor3 = Color3.fromRGB(25, 25, 25)
ExpanderHome.Position = UDim2.new(0, 0, 0.0628571436, 0)
ExpanderHome.Size = UDim2.new(0, 341, 0, 7)

Executor.Name = "Executor"
Executor.Parent = ChillHub
Executor.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
Executor.BackgroundTransparency = 1.000
Executor.Position = UDim2.new(0.0469208211, 0, 0.140998408, 0)
Executor.Size = UDim2.new(0, 124, 0, 31)
Executor.Font = Enum.Font.TitilliumWeb
Executor.Text = "Executor (Coming Soon)"
Executor.TextColor3 = Color3.fromRGB(255, 21, 56)
Executor.TextScaled = true
Executor.TextSize = 20.000
Executor.TextWrapped = true

ImageLabel_2.Parent = Executor
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BackgroundTransparency = 1.000
ImageLabel_2.BorderColor3 = Color3.fromRGB(26, 53, 31)
ImageLabel_2.Position = UDim2.new(-0.140186906, 0, 0, 0)
ImageLabel_2.Size = UDim2.new(0, 41, 0, 35)
ImageLabel_2.Image = "rbxassetid://7193652418"
ImageLabel_2.ImageColor3 = Color3.fromRGB(195, 53, 255)

HomeInformation.Name = "HomeInformation"
HomeInformation.Parent = ChillHub
HomeInformation.Active = true
HomeInformation.BackgroundColor3 = Color3.fromRGB(255, 70, 73)
HomeInformation.Position = UDim2.new(0.301398098, 0, 0.0631970242, 0)
HomeInformation.Size = UDim2.new(0, 334, 0, 505)
HomeInformation.Visible = false
HomeInformation.ScrollBarThickness = 10

Welcome.Name = "Welcome"
Welcome.Parent = HomeInformation
Welcome.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Welcome.BackgroundTransparency = 1.000
Welcome.Position = UDim2.new(0.0658682659, 0, 0.0162774641, 0)
Welcome.Size = UDim2.new(0, 129, 0, 25)
Welcome.Font = Enum.Font.TitilliumWeb
Welcome.Text = "Welcome"
Welcome.TextColor3 = Color3.fromRGB(212, 83, 255)
Welcome.TextScaled = true
Welcome.TextSize = 14.000
Welcome.TextWrapped = true

Playername.Name = "Player name"
Playername.Parent = HomeInformation
Playername.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Playername.BackgroundTransparency = 1.000
Playername.Position = UDim2.new(0.374251485, 0, 0.0162774641, 0)
Playername.Size = UDim2.new(0, 129, 0, 25)
Playername.Font = Enum.Font.TitilliumWeb
Playername.Text = game.Players.LocalPlayer.Name
Playername.TextColor3 = Color3.fromRGB(212, 83, 255)
Playername.TextScaled = true
Playername.TextSize = 14.000
Playername.TextWrapped = true

PlayersImage.Name = "Player's Image"
PlayersImage.Parent = HomeInformation
PlayersImage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayersImage.Position = UDim2.new(0.0359281451, 0, 0.0396410562, 0)
PlayersImage.Size = UDim2.new(0, 96, 0, 99)
PlayersImage.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner.CornerRadius = UDim.new(1, 0)
UICorner.Parent = PlayersImage

Logs.Name = "Logs:"
Logs.Parent = HomeInformation
Logs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logs.BackgroundTransparency = 1.000
Logs.Position = UDim2.new(-0.0958083794, 0, 0.165107936, 0)
Logs.Size = UDim2.new(0, 129, 0, 34)
Logs.Font = Enum.Font.TitilliumWeb
Logs.Text = "Logs:"
Logs.TextColor3 = Color3.fromRGB(212, 83, 255)
Logs.TextScaled = true
Logs.TextSize = 20.000
Logs.TextWrapped = true

madeby.Name = "made by"
madeby.Parent = HomeInformation
madeby.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
madeby.BackgroundTransparency = 1.000
madeby.Position = UDim2.new(-4.65661287e-09, 0, 0.263607681, 0)
madeby.Size = UDim2.new(0, 129, 0, 50)
madeby.Font = Enum.Font.TitilliumWeb
madeby.Text = "Made by ! EMPLIC#9999"
madeby.TextColor3 = Color3.fromRGB(212, 83, 255)
madeby.TextScaled = true
madeby.TextSize = 20.000
madeby.TextWrapped = true

madeby_2.Name = "made by"
madeby_2.Parent = HomeInformation
madeby_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
madeby_2.BackgroundTransparency = 1.000
madeby_2.Position = UDim2.new(-0.011976053, 0, 0.310076088, 0)
madeby_2.Size = UDim2.new(0, 129, 0, 50)
madeby_2.Font = Enum.Font.TitilliumWeb
madeby_2.Text = "Fixed kill all"
madeby_2.TextColor3 = Color3.fromRGB(212, 83, 255)
madeby_2.TextScaled = true
madeby_2.TextSize = 20.000
madeby_2.TextWrapped = true

madeby_3.Name = "made by"
madeby_3.Parent = HomeInformation
madeby_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
madeby_3.BackgroundTransparency = 1.000
madeby_3.Position = UDim2.new(-4.65661287e-09, 0, 0.356544495, 0)
madeby_3.Size = UDim2.new(0, 129, 0, 50)
madeby_3.Font = Enum.Font.TitilliumWeb
madeby_3.Text = "Chill hub."
madeby_3.TextColor3 = Color3.fromRGB(212, 83, 255)
madeby_3.TextScaled = true
madeby_3.TextSize = 20.000
madeby_3.TextWrapped = true

-- Scripts:

local function HQGEF_fake_script() -- HomeTab.LocalScript 
	local script = Instance.new('LocalScript', HomeTab)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.HomeInformation.Visible = true
	end)
end
coroutine.wrap(HQGEF_fake_script)()
local function GGYHQZ_fake_script() -- Executor.LocalScript 
	local script = Instance.new('LocalScript', Executor)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.HomeInformation.Visible = true
	end)
end
coroutine.wrap(GGYHQZ_fake_script)()
