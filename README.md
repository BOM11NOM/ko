local vu = game:GetService("VirtualUser")

game:GetService("Players").LocalPlayer.Idled:connect(function()

    vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

    wait(1)

    vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

end)

 

game.StarterGui:SetCore("SendNotification", {

    Title = "Lucky Blocks Script";

    Text = "Made by JN HH Gaming"; -- what the text says (ofc)

    Duration = 60;

})

wait(1)

game.StarterGui:SetCore("SendNotification", {

    Title = "Subscribe To Him";

    Text = "Now!"; -- what the text says (ofc)

    Duration = 60;

})

 

local LuckyBlock = Instance.new("ScreenGui")

local Frame = Instance.new("ImageLabel")

local title = Instance.new("TextLabel")

local Frame_HUB = Instance.new("ImageLabel")

local HUB = Instance.new("TextLabel")

local Main = Instance.new("Frame")

local LuckyBlock_2 = Instance.new("TextButton")

local SuperBlock = Instance.new("TextButton")

local GalaxyBlock = Instance.new("TextButton")

local RainbowBlock = Instance.new("TextButton")

local DiamondBlock = Instance.new("TextButton")

local CopyDiscordServer = Instance.new("TextButton")

local DiscordServer_box = Instance.new("TextBox")

local lable_discord = Instance.new("TextLabel")

local open_box = Instance.new("TextBox")

local toBox = Instance.new("TextLabel")

local Frame_2 = Instance.new("Frame")

local close = Instance.new("ImageButton")

 

--Properties:

 

LuckyBlock.Name = "LuckyBlock"

LuckyBlock.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

LuckyBlock.ResetOnSpawn = false

 

Frame.Name = "Frame"

Frame.Parent = LuckyBlock

Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

Frame.BackgroundTransparency = 1.000

Frame.ClipsDescendants = true

Frame.Position = UDim2.new(0.304542094, 0, 0.326781332, 0)

Frame.Size = UDim2.new(0, 525, 0, 300)

Frame.Image = "rbxassetid://3570695787"

Frame.ImageColor3 = Color3.fromRGB(255, 0, 0)

Frame.ScaleType = Enum.ScaleType.Slice

Frame.SliceCenter = Rect.new(100, 100, 100, 100)

Frame.SliceScale = 0.120

Frame.Active = true

Frame.Draggable = true

 

title.Name = "title"

title.Parent = Frame

title.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

title.BackgroundTransparency = 1.000

title.Size = UDim2.new(0, 439, 0, 51)

title.Font = Enum.Font.SourceSans

title.Text = "LuckyBlock"

title.TextColor3 = Color3.fromRGB(255, 0, 0)

title.TextSize = 28.000

 

Frame_HUB.Name = "Frame_"

Frame_HUB.Parent = Frame

Frame_HUB.BackgroundColor3 = Color3.fromRGB(0, 0, 0)

Frame_HUB.BackgroundTransparency = 1.000

Frame_HUB.BorderColor3 = Color3.fromRGB(255, 0, 0)

Frame_HUB.Position = UDim2.new(0.531428576, 0, 0.0277550742, 0)

Frame_HUB.Size = UDim2.new(0, 81, 0, 33)

Frame_HUB.Image = "rbxassetid://3570695787"

Frame_HUB.ImageColor3 = Color3.fromRGB(255, 0, 0)

Frame_HUB.ScaleType = Enum.ScaleType.Slice

Frame_HUB.SliceCenter = Rect.new(100, 100, 100, 100)

Frame_HUB.SliceScale = 0.120

 

HUB.Name = "JN HH Gaming Hub"

HUB.Parent = Frame_HUB

HUB.BackgroundColor3 = Color3.fromRGB(0, 0, 0)

HUB.BackgroundTransparency = 1.000

HUB.Position = UDim2.new(0, 0, -0.00494801067, 0)

HUB.Size = UDim2.new(0, 200, 0, 50)

HUB.Font = Enum.Font.SourceSans

HUB.Text = "JN HH Gaming Hub"

HUB.TextColor3 = Color3.fromRGB(0, 0, 0)

HUB.TextScaled = true

HUB.TextSize = 14.000

HUB.TextWrapped = true

 

Main.Name = "Main"

Main.Parent = Frame

Main.BackgroundColor3 = Color3.fromRGB(255, 215, 0)

Main.BorderColor3 = Color3.fromRGB(0, 0, 0)

Main.Position = UDim2.new(-0.034285713, 0, 0.170000002, 0)

Main.Size = UDim2.new(0, 559, 0, 0)

 

LuckyBlock_2.Name = "LuckyBlock"

LuckyBlock_2.Parent = Frame

LuckyBlock_2.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

LuckyBlock_2.BorderSizePixel = 0

LuckyBlock_2.Position = UDim2.new(0.0552380905, 0, 0.223333329, 0)

LuckyBlock_2.Selectable = false

LuckyBlock_2.Size = UDim2.new(0, 150, 0, 35)

LuckyBlock_2.AutoButtonColor = false

LuckyBlock_2.Font = Enum.Font.SourceSans

LuckyBlock_2.Text = "LuckyBlock"

LuckyBlock_2.TextColor3 = Color3.fromRGB(255, 0, 0)

LuckyBlock_2.TextSize = 28.000

 

SuperBlock.Name = "SuperBlock"

SuperBlock.Parent = Frame

SuperBlock.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

SuperBlock.BorderSizePixel = 0

SuperBlock.Position = UDim2.new(0.0552381277, 0, 0.383333325, 0)

SuperBlock.Selectable = false

SuperBlock.Size = UDim2.new(0, 150, 0, 35)

SuperBlock.AutoButtonColor = false

SuperBlock.Font = Enum.Font.SourceSans

SuperBlock.Text = "SuperBlock"

SuperBlock.TextColor3 = Color3.fromRGB(255, 0, 0)

SuperBlock.TextSize = 28.000

 

GalaxyBlock.Name = "GalaxyBlock"

GalaxyBlock.Parent = Frame

GalaxyBlock.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

GalaxyBlock.BorderSizePixel = 0

GalaxyBlock.Position = UDim2.new(0.0552381277, 0, 0.826666653, 0)

GalaxyBlock.Selectable = false

GalaxyBlock.Size = UDim2.new(0, 150, 0, 35)

GalaxyBlock.AutoButtonColor = false

GalaxyBlock.Font = Enum.Font.SourceSans

GalaxyBlock.Text = "GalaxyBlock"

GalaxyBlock.TextColor3 = Color3.fromRGB(255, 0, 0)

GalaxyBlock.TextSize = 28.000

 

RainbowBlock.Name = "RainbowBlock"

RainbowBlock.Parent = Frame

RainbowBlock.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

RainbowBlock.BorderSizePixel = 0

RainbowBlock.Position = UDim2.new(0.0552381277, 0, 0.679999948, 0)

RainbowBlock.Selectable = false

RainbowBlock.Size = UDim2.new(0, 150, 0, 35)

RainbowBlock.AutoButtonColor = false

RainbowBlock.Font = Enum.Font.SourceSans

RainbowBlock.Text = "RainbowBlock"

RainbowBlock.TextColor3 = Color3.fromRGB(255, 0, 0)

RainbowBlock.TextSize = 28.000

 

DiamondBlock.Name = "DiamondBlock"

DiamondBlock.Parent = Frame

DiamondBlock.BackgroundColor3 = Color3.fromRGB(0, 0, 255)

DiamondBlock.BorderSizePixel = 0

DiamondBlock.Position = UDim2.new(0.0552381277, 0, 0.533333302, 0)

DiamondBlock.Selectable = false

DiamondBlock.Size = UDim2.new(0, 150, 0, 35)

DiamondBlock.AutoButtonColor = false

DiamondBlock.Font = Enum.Font.SourceSans

DiamondBlock.Text = "DiamondBlock"

DiamondBlock.TextColor3 = Color3.fromRGB(255, 0, 0)

DiamondBlock.TextSize = 28.000

 

open_box.Name = "open_box"

open_box.Parent = Frame

open_box.BackgroundColor3 = Color3.fromRGB(40, 40, 40)

open_box.BorderSizePixel = 0

open_box.Position = UDim2.new(0.750476241, 0, 0.313333333, 0)

open_box.Size = UDim2.new(0, 56, 0, 35)

open_box.ClearTextOnFocus = false

open_box.Font = Enum.Font.SourceSans

open_box.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)

open_box.PlaceholderText = "Value"

open_box.Text = "1"

open_box.TextColor3 = Color3.fromRGB(255, 255, 255)

open_box.TextSize = 28.000

open_box.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)

 

toBox.Name = "toBox"

toBox.Parent = Frame

toBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

toBox.BackgroundTransparency = 1.000

toBox.Position = UDim2.new(0.531428635, 0, 0.286666691, 0)

toBox.Size = UDim2.new(0, 194, 0, 50)

toBox.Font = Enum.Font.SourceSans

toBox.Text = "0 to "

toBox.TextColor3 = Color3.fromRGB(255, 255, 255)

toBox.TextSize = 28.000

 

Frame_2.Parent = Frame

Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)

Frame_2.BorderColor3 = Color3.fromRGB(255, 255, 255)

Frame_2.Position = UDim2.new(0.400000006, 0, 0.170000002, 0)

Frame_2.Size = UDim2.new(0, 0, 0, 292)

 

close.Name = "close"

close.Parent = Frame

close.BackgroundTransparency = 1.000

close.Position = UDim2.new(0.90054822, 0, 0.00678133965, 0)

close.Size = UDim2.new(0, 45, 0, 45)

close.ZIndex = 2

close.Image = "rbxassetid://3926305904"

close.ImageRectOffset = Vector2.new(284, 4)

close.ImageRectSize = Vector2.new(24, 24)

 

 

----------------------------------------------------------------

 

close.MouseButton1Click:connect(function()

    Frame.Visible = false

end)

 

LuckyBlock_2.MouseButton1Click:connect(function()

    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)

        game.ReplicatedStorage.SpawnLuckyBlock:FireServer()

    end

end)

 

DiamondBlock.MouseButton1Click:connect(function()

    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)

        game.ReplicatedStorage.SpawnDiamondBlock:FireServer()

    end

end)

 

SuperBlock.MouseButton1Click:connect(function()

    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)

        game.ReplicatedStorage.SpawnSuperBlock:FireServer()

    end

end)

 

RainbowBlock.MouseButton1Click:connect(function()

    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)

        game.ReplicatedStorage.SpawnRainbowBlock:FireServer()

    end

end)

 

GalaxyBlock.MouseButton1Click:connect(function()

    for i=1, open_box.Text do --This number means that you'll get 100 gears (you can change this)

        game.ReplicatedStorage.SpawnGalaxyBlock:FireServer()

    end

end)

-- Gui to Lua

-- Version: 3.

-- Instances:

local ScreenGui = Instance.new("ScreenGui")

local Main = Instance.new("Frame")

local TextLabel = Instance.new("TextLabel")

local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Main.Name = "Main"

Main.Parent = ScreenGui

Main.BackgroundColor3 = Color3.fromRGB(39, 15, 245)

Main.Position = UDim2.new(0.363293529, 0, 0.28638497, 0)

Main.Size = UDim2.new(0, 300, 0, 154)

Main.Style = Enum.FrameStyle.ChatRed

TextLabel.Parent = Main

TextLabel.BackgroundColor3 = Color3.fromRGB(17, 1, 1)

TextLabel.BackgroundTransparency = 1.000

TextLabel.Position = UDim2.new(-0.025588274, 0, -0.0890700519, 0)

TextLabel.Size = UDim2.new(0, 250, 0, 30)

TextLabel.Font = Enum.Font.SciFi

TextLabel.Text = "JN HH Gaming Lucky Block Speed"

TextLabel.TextColor3 = Color3.fromRGB(245, 16, 16)

TextLabel.TextScaled = true

TextLabel.TextSize = 12.000

TextLabel.TextWrapped = true

TextButton.Parent = Main

TextButton.BackgroundColor3 = Color3.fromRGB(17, 1, 1)

TextButton.Position = UDim2.new(0.136470661, 0, 0.458670378, 0)

TextButton.Size = UDim2.new(0, 200, 0, 58)

TextButton.Style = Enum.ButtonStyle.RobloxRoundDefaultButton

TextButton.Font = Enum.Font.SciFi

TextButton.Text = "Click To Activate"

TextButton.TextColor3 = Color3.fromRGB(21, 235, 78)

TextButton.TextScaled = true

TextButton.TextSize = 14.000

TextButton.TextWrapped = true

TextButton.MouseButton1Down:connect(function()

 while true do wait() game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100 end

Walkspeed()

end)

-- Scripts:

local function LASGYB_fake_script() -- ScreenGui.Script 

	local script = Instance.new('Script', ScreenGui)

	frame = script.Parent.Main -- Take out {}s, and put name of frame

	frame.Draggable = true

	frame.Active = true

	frame.Selectable = true

end

coroutine.wrap(LASGYB_fake_script)()

_G.HeadSize = 50

_G.Disabled = true

game:GetService('RunService').RenderStepped:connect(function()

if _G.Disabled then

for i,v in next, game:GetService('Players'):GetPlayers() do

if v.Name ~= game:GetService('Players').LocalPlayer.Name then

pcall(function()

v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)

v.Character.HumanoidRootPart.Transparency = 0.7

v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really black")

v.Character.HumanoidRootPart.Material = "Neon"

v.Character.HumanoidRootPart.CanCollide = false

end)

end

end

end

end)

