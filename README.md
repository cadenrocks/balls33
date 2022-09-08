-- Speedhack : Q
-- Auto pickup : y
 
local BoogaBooga = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local HeaderFrame = Instance.new("Frame")
local TitleGUI = Instance.new("TextLabel")
local SpeedHack = Instance.new("TextButton")
local JumpHack = Instance.new("TextButton")
local InfinityJump = Instance.new("TextButton")
local CraftGUI = Instance.new("TextButton")
local Minimize = Instance.new("TextButton")
local CraftFrame = Instance.new("Frame")
local HeaderFrame_2 = Instance.new("Frame")
local CraftLogo = Instance.new("TextLabel")
local ItemName = Instance.new("TextBox")
local CraftSubmit = Instance.new("TextButton")
local CraftGUI_2 = Instance.new("TextButton")
local AutoPickup = Instance.new("TextButton")
local ESPTrack = Instance.new("TextButton")
local DropItem = Instance.new("TextButton")
local ItemDrop = Instance.new("TextBox")
local MinimizeFrame = Instance.new("Frame")
local MinOpen = Instance.new("TextButton")
 
-- Properties
 
BoogaBooga.Name = "BoogaBooga"
BoogaBooga.Parent = game.CoreGui
 
Frame.Parent = BoogaBooga
Frame.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0, 319, 0, 134)
Frame.Size = UDim2.new(0, 577, 0, 250)
 
HeaderFrame.Name = "HeaderFrame"
HeaderFrame.Parent = Frame
HeaderFrame.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
HeaderFrame.BorderSizePixel = 0
HeaderFrame.Size = UDim2.new(0, 577, 0, 33)
 
TitleGUI.Name = "TitleGUI"
TitleGUI.Parent = Frame
TitleGUI.BackgroundColor3 = Color3.new(1, 1, 1)
TitleGUI.BackgroundTransparency = 1
TitleGUI.BorderSizePixel = 0
TitleGUI.Position = UDim2.new(0, 140, 0, 0)
TitleGUI.Size = UDim2.new(0, 309, 0, 33)
TitleGUI.Font = Enum.Font.SciFi
TitleGUI.Text = "Booga Booga | GGH GUI"
TitleGUI.TextColor3 = Color3.new(1, 1, 1)
TitleGUI.TextSize = 14
 
SpeedHack.Name = "SpeedHack"
SpeedHack.Parent = Frame
SpeedHack.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
SpeedHack.BorderSizePixel = 0
SpeedHack.Position = UDim2.new(0, 20, 0, 49)
SpeedHack.Size = UDim2.new(0, 200, 0, 50)
SpeedHack.Font = Enum.Font.SourceSans
SpeedHack.Text = "SpeedHack"
SpeedHack.TextColor3 = Color3.new(1, 1, 1)
SpeedHack.TextSize = 14
 
JumpHack.Name = "JumpHack"
JumpHack.Parent = Frame
JumpHack.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
JumpHack.BorderSizePixel = 0
JumpHack.Position = UDim2.new(0, 20, 0, 112)
JumpHack.Size = UDim2.new(0, 200, 0, 50)
JumpHack.Font = Enum.Font.SourceSans
JumpHack.Text = "JumpHack"
JumpHack.TextColor3 = Color3.new(1, 1, 1)
JumpHack.TextSize = 14
 
InfinityJump.Name = "InfinityJump"
InfinityJump.Parent = Frame
InfinityJump.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
InfinityJump.BorderSizePixel = 0
InfinityJump.Position = UDim2.new(0, 21, 0, 173)
InfinityJump.Size = UDim2.new(0, 200, 0, 50)
InfinityJump.Font = Enum.Font.SourceSans
InfinityJump.Text = "Infinity Jump"
InfinityJump.TextColor3 = Color3.new(1, 1, 1)
InfinityJump.TextSize = 14
 
CraftGUI.Name = "CraftGUI"
CraftGUI.Parent = Frame
CraftGUI.BackgroundColor3 = Color3.new(1, 1, 1)
CraftGUI.BackgroundTransparency = 1
CraftGUI.BorderSizePixel = 0
CraftGUI.Size = UDim2.new(0, 81, 0, 31)
CraftGUI.Font = Enum.Font.ArialBold
CraftGUI.Text = "<"
CraftGUI.TextColor3 = Color3.new(1, 1, 1)
CraftGUI.TextSize = 14
 
Minimize.Name = "Minimize"
Minimize.Parent = Frame
Minimize.BackgroundColor3 = Color3.new(1, 1, 1)
Minimize.BackgroundTransparency = 1
Minimize.BorderSizePixel = 0
Minimize.Position = UDim2.new(0, 496, 0, 0)
Minimize.Size = UDim2.new(0, 81, 0, 31)
Minimize.Font = Enum.Font.ArialBold
Minimize.Text = ">"
Minimize.TextColor3 = Color3.new(1, 1, 1)
Minimize.TextSize = 14
 
CraftFrame.Name = "CraftFrame"
CraftFrame.Parent = Frame
CraftFrame.BackgroundColor3 = Color3.new(0.196078, 0.196078, 0.196078)
CraftFrame.Position = UDim2.new(0, -245, 0, 0)
CraftFrame.Size = UDim2.new(0, 226, 0, 151)
CraftFrame.Visible = false
 
HeaderFrame_2.Name = "HeaderFrame"
HeaderFrame_2.Parent = CraftFrame
HeaderFrame_2.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
HeaderFrame_2.BorderSizePixel = 0
HeaderFrame_2.Size = UDim2.new(0, 226, 0, 33)
 
CraftLogo.Name = "CraftLogo"
CraftLogo.Parent = CraftFrame
CraftLogo.BackgroundColor3 = Color3.new(1, 1, 1)
CraftLogo.BackgroundTransparency = 1
CraftLogo.BorderSizePixel = 0
CraftLogo.Position = UDim2.new(0, 55, 0, 0)
CraftLogo.Size = UDim2.new(0, 115, 0, 31)
CraftLogo.Font = Enum.Font.SciFi
CraftLogo.Text = "Craft Item"
CraftLogo.TextColor3 = Color3.new(1, 1, 1)
CraftLogo.TextSize = 14
 
ItemName.Name = "ItemName"
ItemName.Parent = CraftFrame
ItemName.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
ItemName.BorderColor3 = Color3.new(0, 0, 0)
ItemName.BorderSizePixel = 3
ItemName.Position = UDim2.new(0, 13, 0, 47)
ItemName.Size = UDim2.new(0, 200, 0, 34)
ItemName.Font = Enum.Font.SciFi
ItemName.Text = "Item Name"
ItemName.TextColor3 = Color3.new(1, 1, 1)
ItemName.TextSize = 14
 
CraftSubmit.Name = "CraftSubmit"
CraftSubmit.Parent = CraftFrame
CraftSubmit.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
CraftSubmit.BorderSizePixel = 0
CraftSubmit.Position = UDim2.new(0, 13, 0, 93)
CraftSubmit.Size = UDim2.new(0, 200, 0, 35)
CraftSubmit.Font = Enum.Font.SciFi
CraftSubmit.Text = "Craft Now!"
CraftSubmit.TextColor3 = Color3.new(1, 1, 1)
CraftSubmit.TextSize = 14
 
CraftGUI_2.Name = "CraftGUI"
CraftGUI_2.Parent = CraftFrame
CraftGUI_2.BackgroundColor3 = Color3.new(1, 1, 1)
CraftGUI_2.BackgroundTransparency = 1
CraftGUI_2.BorderSizePixel = 0
CraftGUI_2.Position = UDim2.new(0, 163, 0, 0)
CraftGUI_2.Size = UDim2.new(0, 63, 0, 31)
CraftGUI_2.Font = Enum.Font.ArialBold
CraftGUI_2.Text = ">"
CraftGUI_2.TextColor3 = Color3.new(1, 1, 1)
CraftGUI_2.TextSize = 14
 
AutoPickup.Name = "AutoPickup"
AutoPickup.Parent = Frame
AutoPickup.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
AutoPickup.BorderSizePixel = 0
AutoPickup.Position = UDim2.new(0, 236, 0, 49)
AutoPickup.Size = UDim2.new(0, 200, 0, 50)
AutoPickup.Font = Enum.Font.SciFi
AutoPickup.Text = "Auto Pickup"
AutoPickup.TextColor3 = Color3.new(1, 1, 1)
AutoPickup.TextSize = 14
 
ESPTrack.Name = "ESP Track"
ESPTrack.Parent = Frame
ESPTrack.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
ESPTrack.BorderSizePixel = 0
ESPTrack.Position = UDim2.new(0, 237, 0, 110)
ESPTrack.Size = UDim2.new(0, 200, 0, 49)
ESPTrack.Font = Enum.Font.SciFi
ESPTrack.Text = "ESP Track"
ESPTrack.TextColor3 = Color3.new(1, 1, 1)
ESPTrack.TextSize = 14
 
DropItem.Name = "DropItem"
DropItem.Parent = Frame
DropItem.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
DropItem.BorderSizePixel = 0
DropItem.Position = UDim2.new(0, 238, 0, 173)
DropItem.Size = UDim2.new(0, 324, 0, 49)
DropItem.Font = Enum.Font.SciFi
DropItem.Text = "Drop item from bag!"
DropItem.TextColor3 = Color3.new(1, 1, 1)
DropItem.TextSize = 14
 
ItemDrop.Name = "ItemDrop"
ItemDrop.Parent = Frame
ItemDrop.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
ItemDrop.BorderColor3 = Color3.new(0, 0, 0)
ItemDrop.BorderSizePixel = 3
ItemDrop.Position = UDim2.new(0, 448, 0, 49)
ItemDrop.Size = UDim2.new(0, 113, 0, 106)
ItemDrop.Font = Enum.Font.SciFi
ItemDrop.Text = "Item Name"
ItemDrop.TextColor3 = Color3.new(1, 1, 1)
ItemDrop.TextSize = 14
 
MinimizeFrame.Name = "MinimizeFrame"
MinimizeFrame.Parent = BoogaBooga
MinimizeFrame.BackgroundColor3 = Color3.new(1, 1, 1)
MinimizeFrame.BackgroundTransparency = 1
MinimizeFrame.BorderSizePixel = 0
MinimizeFrame.Position = UDim2.new(0, 942, 0, 215)
MinimizeFrame.Size = UDim2.new(0, 154, 0, 223)
MinimizeFrame.Visible = false
 
MinOpen.Name = "MinOpen"
MinOpen.Parent = MinimizeFrame
MinOpen.BackgroundColor3 = Color3.new(1, 1, 1)
MinOpen.BackgroundTransparency = 1
MinOpen.BorderSizePixel = 0
MinOpen.Size = UDim2.new(0, 154, 0, 223)
MinOpen.Font = Enum.Font.Fantasy
MinOpen.Text = "<"
MinOpen.TextColor3 = Color3.new(1, 1, 1)
MinOpen.TextScaled = true
MinOpen.TextSize = 14
MinOpen.TextWrapped = true
 
-- Scripts 
 
SpeedHack.MouseButton1Down:connect(function()
	local plr = game:GetService("Players").LocalPlayer
local char = plr.Character
local mouse = game:GetService("Players").LocalPlayer:GetMouse()
local hum = char:FindFirstChild("HumanoidRootPart")
local speed = 3
mouse.KeyDown:connect(function(key)
    if key == "q"  then
        loop = true
        while loop do
            hum.CFrame = hum.CFrame + hum.CFrame.lookVector * speed
            wait()
        end
        end
end)
 
mouse.KeyUp:connect(function(key)
    if key == "q"  then
        loop = false
    end
end)
end)
 
JumpHack.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = 150
end)
 
InfinityJump.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/2eYepag7'),true))()
end)
 
CraftGUI.MouseButton1Down:connect(function()
	CraftFrame.Visible = true
end)
 
Minimize.MouseButton1Down:connect(function()
	Frame.Visible = false
	MinimizeFrame.Visible = true
end)
 
CraftSubmit.MouseButton1Down:connect(function()
local Item = ItemName.Text
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(Item)
end)
 
CraftGUI_2.MouseButton1Down:connect(function()
	CraftFrame.Visible = false
end)
 
AutoPickup.MouseButton1Down:connect(function()
	local Objects;
 
local Pickup = function(Character)
    local myPos = Character.HumanoidRootPart.Position
    local Objects = {}
    for i,v in pairs(workspace:GetChildren()) do
        if v:FindFirstChild("Pickup") ~= nil and v.ClassName == "Part" then
            local Pos = v.Position
            local Distance = (myPos - Pos).magnitude
            if Distance < 40 then
                table.insert(Objects, v)
            end
            elseif v:FindFirstChild("Pickup") ~= nil and v:FindFirstChild("Part") ~= nil and v.Part.ClassName == "Part" then
            local Pos = v.Part.Position
            local Distance = (myPos - Pos).magnitude
            if Distance < 40 then
                table.insert(Objects, v)
            end
             elseif v:FindFirstChild("Pickup") ~= nil and v.ClassName == "UnionOperation" then
             local Pos = v.Position
            local Distance = (myPos - Pos).magnitude
            if Distance < 40 then
                table.insert(Objects, v)
            end
        end
    end
    for i,v in pairs(Objects) do
    for i=1,10 do
    v.Position = myPos
    game:GetService("ReplicatedStorage").Events.Pickup:FireServer(v)
    end
    end
end
wait(1)
local mouse = game:GetService("Players").LocalPlayer:GetMouse()
 
mouse.KeyDown:connect(function(key)
    if key == "y" then
print'howdi neighbor'
Pickup(game.Players.LocalPlayer.Character)
end
end)
end)
 
Important = {Players = game:GetService("Players"), Workspace = game:GetService("Workspace"), CoreGui = game:GetService("CoreGui")}
 
local enabledesp = false
 
function CreateESP(plr)
 
    if plr ~= nil then
 
        local GetChar = plr.Character
        if not GetChar then return end
 
        local GetHead do
 
            repeat wait() until GetChar:FindFirstChild("Head")
 
        end
        GetHead = GetChar.Head        
 
        local bb = Instance.new("BillboardGui", Important.CoreGui)
        bb.Adornee = GetHead
        bb.ExtentsOffset = Vector3.new(0, 1, 0)
        bb.AlwaysOnTop = true
        bb.Size = UDim2.new(0, 5, 0, 5)
        bb.StudsOffset = Vector3.new(0, 3, 0)
        bb.Name = "ESP_PLAYER_" .. plr.Name
 
        local displayframe = Instance.new("Frame", bb)
        displayframe.ZIndex = 10
        displayframe.BackgroundTransparency = 1
        displayframe.Size = UDim2.new(1,0,1,0)
 
        local name = Instance.new("TextLabel", displayframe)
        name.Name = "Name"
        name.ZIndex = 10
        name.Text = plr.Name
        name.Visible = true
        name.TextColor3 = Color3.new(170,0,0)
        name.BackgroundTransparency = 1
        name.Size = UDim2.new(1,0,10,0)
        name.Font = Enum.Font.SourceSansLight
        name.TextSize = 20
        name.TextStrokeTransparency = .5
 
    end
 
end
 
ESPTrack.MouseButton1Click:connect(function()
	 for i,v in pairs(Important.Players:GetChildren()) do
 
        CreateESP(v)
 
    end
end)
 
DropItem.MouseButton1Down:connect(function()
local item = ItemDrop.Text -- change this to the item you want to drop
local amount = 1000 -- change this to the amount you want to drop
 
local i = 0
while i <= amount do
    game.ReplicatedStorage.Events.DropBagItem:FireServer(item)
    i = i + 1
end
end)
 
MinOpen.MouseButton1Down:connect(function()
	MinimizeFrame.Visible = false
	Frame.Visible = true
end)
