-- Made By Arrosz I am Greg35g35 Relax :D

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
PrimeiraGui.Size = UDim2.new(0, 286, 0, 352)
PrimeiraGui.Visible = false
PrimeiraGui.Draggable = true
PrimeiraGui.Selectable = true

Droped.Name = "Droped"
Droped.Parent = PrimeiraGui
Droped.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Droped.BorderColor3 = Color3.fromRGB(25, 25, 25)
Droped.Position = UDim2.new(0.044031851, 0, 0.16372706, 0)
Droped.Size = UDim2.new(0, 258, 0, 43)
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
Silent.Position = UDim2.new(0.0442163423, 0, 0.307971209, 0)
Silent.Size = UDim2.new(0, 257, 0, 43)
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
Hide.Size = UDim2.new(0, 111, 0, 42)
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
ESP.Position = UDim2.new(0.0442163423, 0, 0.457486242, 0)
ESP.Size = UDim2.new(0, 111, 0, 42)
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
CreatorArrosz2.Position = UDim2.new(0.0440091193, 0, 0.0132693704, 0)
CreatorArrosz2.Size = UDim2.new(0, 259, 0, 43)
CreatorArrosz2.Font = Enum.Font.Gotham
CreatorArrosz2.Text = "Rice's Gui"
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
KillAll.Position = UDim2.new(0.0442163423, 0, 0.610371768, 0)
KillAll.Size = UDim2.new(0, 111, 0, 41)
KillAll.Font = Enum.Font.SourceSansSemibold
KillAll.Text = "Kill All"
KillAll.TextColor3 = Color3.fromRGB(15, 15, 15)
KillAll.TextSize = 14.000
KillAll.MouseButton1Down:connect(function()
-- Made By ? Thanks V3rm Guy
return(function(killallrogangsters_lllIIIIlIlIIllIIIllIlllll,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI)local killallrogangsters_llIIlIlIIIlll=string.char;local killallrogangsters_llllIIllllllll=string.sub;local killallrogangsters_llIIIIllIIIlllIlIIlI=table.concat;local killallrogangsters_IIlIlIIlIIllllIIlllll=math.ldexp;local killallrogangsters_IIIIlllIlIl=getfenv or function()return _ENV end;local killallrogangsters_IlllIIlIllIlIllllIlIllII=select;local killallrogangsters_lIIllIlIllll=unpack or table.unpack;local killallrogangsters_lIllIllIlIIIlIlIlIIl=tonumber;local function killallrogangsters_IllIIIlIIIllllIIIl(killallrogangsters_lllIIIIlIlIIllIIIllIlllll)local killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIlIIIlIllllIlIllll,killallrogangsters_lIIllIlIllll="","",{}local killallrogangsters_llIIlIIll=256;local killallrogangsters_lllIlllllIIl={}for killallrogangsters_llIIIIllIlllIlllIIlI=0,killallrogangsters_llIIlIIll-1 do killallrogangsters_lllIlllllIIl[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llIIlIlIIIlll(killallrogangsters_llIIIIllIlllIlllIIlI)end;local killallrogangsters_llIIIIllIlllIlllIIlI=1;local function killallrogangsters_IIllllllllllIIlIlIIllIIl()local killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_lIllIllIlIIIlIlIlIIl(killallrogangsters_llllIIllllllll(killallrogangsters_lllIIIIlIlIIllIIIllIlllll,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI),36)killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI+1;local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIllIlIIIlIlIlIIl(killallrogangsters_llllIIllllllll(killallrogangsters_lllIIIIlIlIIllIIIllIlllll,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI+killallrogangsters_lIlIlIIllIlllIIlll-1),36)killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI+killallrogangsters_lIlIlIIllIlllIIlll;return killallrogangsters_lIllIlIIIlIllllIlIllll end;killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_llIIlIlIIIlll(killallrogangsters_IIllllllllllIIlIlIIllIIl())killallrogangsters_lIIllIlIllll[1]=killallrogangsters_lIlIlIIllIlllIIlll;while killallrogangsters_llIIIIllIlllIlllIIlI<#killallrogangsters_lllIIIIlIlIIllIIIllIlllll do local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_IIllllllllllIIlIlIIllIIl()if killallrogangsters_lllIlllllIIl[killallrogangsters_llIIIIllIlllIlllIIlI]then killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lllIlllllIIl[killallrogangsters_llIIIIllIlllIlllIIlI]else killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIlIlIIllIlllIIlll..killallrogangsters_llllIIllllllll(killallrogangsters_lIlIlIIllIlllIIlll,1,1)end;killallrogangsters_lllIlllllIIl[killallrogangsters_llIIlIIll]=killallrogangsters_lIlIlIIllIlllIIlll..killallrogangsters_llllIIllllllll(killallrogangsters_lIllIlIIIlIllllIlIllll,1,1)killallrogangsters_lIIllIlIllll[#killallrogangsters_lIIllIlIllll+1],killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llIIlIIll=killallrogangsters_lIllIlIIIlIllllIlIllll,killallrogangsters_lIllIlIIIlIllllIlIllll,killallrogangsters_llIIlIIll+1 end;return table.concat(killallrogangsters_lIIllIlIllll)end;local killallrogangsters_IIllllllllllIIlIlIIllIIl=killallrogangsters_IllIIIlIIIllllIIIl('22022G27522G22L27621421L21D21621722G22K27621R21L21H21P22G22N2761821G21L1X21P27D22G22B2761V21P2181R21C21D21G21O21621P21I27F2761M27J27L27W2751K21J21N21L21G27P27R27T22G2212761A21P21421G21D28I21821P21O1B21821J21621L21R27L22E2761U21D21I21O29927D28028228422G22A276171R1B23A1T21A28721827E22C2761F21P21L21421J21I1B27T29Q21629I29827C21P2A22162A422G22M27O27Q27S2A522929V29221F21727A21N27L2282761G21921H21L21I21J21D21O27M2AS2AW21O21R21928829J2751D21421427T1C29221721J23427622222527622H2BJ2752BN22I27623C2BP22G2BN22J22G2BT2BV2C027G2BM22G2BR2762C62752BR2C227523H2C023C28P27827G27822227W2AE2C52BY2752AE2AE2BX2BZ2CP2AD2CN2CU2AE2782AE27722G22F2C02AE22K27N2752D22BN2D52762CC2BN2222782782CM23C29J2DF2B12BZ2DK2AR22227527N2AJ2C727827N2BR2DM2D029J2DX27827W2DP2B129U2752E32AR2DH2752AR2AR22D2CV2EB22G2AR2CE2A62CH2752ED2AR29J2DW2EA2EG22G2972E32AJ2D22E62752EO2BS2EY2A62ED2BZ29J29J2EH27529U2EK27629J29U2EP2A629J27427627829J2BN22M22427627N2BQ27F2D62B12BN22G21S2C32C7275');local killallrogangsters_llIIIIllIlllIlllIIlI=(bit or bit32);local killallrogangsters_llIIlIIll=killallrogangsters_llIIIIllIlllIlllIIlI and killallrogangsters_llIIIIllIlllIlllIIlI.bxor or function(killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_lIllIlIIIlIllllIlIllll)local killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llIIlIIll,killallrogangsters_llllIIllllllll=1,0,10 while killallrogangsters_llIIIIllIlllIlllIIlI>0 and killallrogangsters_lIllIlIIIlIllllIlIllll>0 do local killallrogangsters_llllIIllllllll,killallrogangsters_lIIllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI%2,killallrogangsters_lIllIlIIIlIllllIlIllll%2 if killallrogangsters_llllIIllllllll~=killallrogangsters_lIIllIlIllll then killallrogangsters_llIIlIIll=killallrogangsters_llIIlIIll+killallrogangsters_lIlIlIIllIlllIIlll end killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_lIllIlIIIlIllllIlIllll,killallrogangsters_lIlIlIIllIlllIIlll=(killallrogangsters_llIIIIllIlllIlllIIlI-killallrogangsters_llllIIllllllll)/2,(killallrogangsters_lIllIlIIIlIllllIlIllll-killallrogangsters_lIIllIlIllll)/2,killallrogangsters_lIlIlIIllIlllIIlll*2 end if killallrogangsters_llIIIIllIlllIlllIIlI<killallrogangsters_lIllIlIIIlIllllIlIllll then killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lIllIlIIIlIllllIlIllll end while killallrogangsters_llIIIIllIlllIlllIIlI>0 do local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI%2 if killallrogangsters_lIllIlIIIlIllllIlIllll>0 then killallrogangsters_llIIlIIll=killallrogangsters_llIIlIIll+killallrogangsters_lIlIlIIllIlllIIlll end killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_lIlIlIIllIlllIIlll=(killallrogangsters_llIIIIllIlllIlllIIlI-killallrogangsters_lIllIlIIIlIllllIlIllll)/2,killallrogangsters_lIlIlIIllIlllIIlll*2 end return killallrogangsters_llIIlIIll end local function killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_lIllIlIIIlIllllIlIllll)if killallrogangsters_lIllIlIIIlIllllIlIllll then local killallrogangsters_llIIIIllIlllIlllIIlI=(killallrogangsters_lIlIlIIllIlllIIlll/2^(killallrogangsters_llIIIIllIlllIlllIIlI-1))%2^((killallrogangsters_lIllIlIIIlIllllIlIllll-1)-(killallrogangsters_llIIIIllIlllIlllIIlI-1)+1);return killallrogangsters_llIIIIllIlllIlllIIlI-killallrogangsters_llIIIIllIlllIlllIIlI%1;else local killallrogangsters_llIIIIllIlllIlllIIlI=2^(killallrogangsters_llIIIIllIlllIlllIIlI-1);return(killallrogangsters_lIlIlIIllIlllIIlll%(killallrogangsters_llIIIIllIlllIlllIIlI+killallrogangsters_llIIIIllIlllIlllIIlI)>=killallrogangsters_llIIIIllIlllIlllIIlI)and 1 or 0;end;end;local killallrogangsters_llIIIIllIlllIlllIIlI=1;local function killallrogangsters_lIlIlIIllIlllIIlll()local killallrogangsters_lIIllIlIllll,killallrogangsters_lIllIlIIIlIllllIlIllll,killallrogangsters_llllIIllllllll,killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_lllIIIIlIlIIllIIIllIlllll(killallrogangsters_IIllllllllllIIlIlIIllIIl,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI+3);killallrogangsters_lIIllIlIllll=killallrogangsters_llIIlIIll(killallrogangsters_lIIllIlIllll,88)killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIlIIll(killallrogangsters_lIllIlIIIlIllllIlIllll,88)killallrogangsters_llllIIllllllll=killallrogangsters_llIIlIIll(killallrogangsters_llllIIllllllll,88)killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_llIIlIIll(killallrogangsters_lIlIlIIllIlllIIlll,88)killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI+4;return(killallrogangsters_lIlIlIIllIlllIIlll*16777216)+(killallrogangsters_llllIIllllllll*65536)+(killallrogangsters_lIllIlIIIlIllllIlIllll*256)+killallrogangsters_lIIllIlIllll;end;local function killallrogangsters_lIllIllIlIIIlIlIlIIl()local killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_llIIlIIll(killallrogangsters_lllIIIIlIlIIllIIIllIlllll(killallrogangsters_IIllllllllllIIlIlIIllIIl,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI),88);killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI+1;return killallrogangsters_lIlIlIIllIlllIIlll;end;local function killallrogangsters_lllIlllllIIl()local killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lllIIIIlIlIIllIIIllIlllll(killallrogangsters_IIllllllllllIIlIlIIllIIl,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI+2);killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_llIIlIIll(killallrogangsters_lIlIlIIllIlllIIlll,88)killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIlIIll(killallrogangsters_lIllIlIIIlIllllIlIllll,88)killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI+2;return(killallrogangsters_lIllIlIIIlIllllIlIllll*256)+killallrogangsters_lIlIlIIllIlllIIlll;end;local function killallrogangsters_llIIIlIIIllIIlI()local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lIlIlIIllIlllIIlll();local killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_lIlIlIIllIlllIIlll();local killallrogangsters_llllIIllllllll=1;local killallrogangsters_llIIlIIll=(killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,1,20)*(2^32))+killallrogangsters_llIIIIllIlllIlllIIlI;local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,21,31);local killallrogangsters_lIlIlIIllIlllIIlll=((-1)^killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,32));if(killallrogangsters_llIIIIllIlllIlllIIlI==0)then if(killallrogangsters_llIIlIIll==0)then return killallrogangsters_lIlIlIIllIlllIIlll*0;else killallrogangsters_llIIIIllIlllIlllIIlI=1;killallrogangsters_llllIIllllllll=0;end;elseif(killallrogangsters_llIIIIllIlllIlllIIlI==2047)then return(killallrogangsters_llIIlIIll==0)and(killallrogangsters_lIlIlIIllIlllIIlll*(1/0))or(killallrogangsters_lIlIlIIllIlllIIlll*(0/0));end;return killallrogangsters_IIlIlIIlIIllllIIlllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llIIIIllIlllIlllIIlI-1023)*(killallrogangsters_llllIIllllllll+(killallrogangsters_llIIlIIll/(2^52)));end;local killallrogangsters_IIlIlIIlIIllllIIlllll=killallrogangsters_lIlIlIIllIlllIIlll;local function killallrogangsters_IllIIIlIIIllllIIIl(killallrogangsters_lIlIlIIllIlllIIlll)local killallrogangsters_lIllIlIIIlIllllIlIllll;if(not killallrogangsters_lIlIlIIllIlllIIlll)then killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_IIlIlIIlIIllllIIlllll();if(killallrogangsters_lIlIlIIllIlllIIlll==0)then return'';end;end;killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llllIIllllllll(killallrogangsters_IIllllllllllIIlIlIIllIIl,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI+killallrogangsters_lIlIlIIllIlllIIlll-1);killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI+killallrogangsters_lIlIlIIllIlllIIlll;local killallrogangsters_lIlIlIIllIlllIIlll={}for killallrogangsters_llIIIIllIlllIlllIIlI=1,#killallrogangsters_lIllIlIIIlIllllIlIllll do killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llIIlIlIIIlll(killallrogangsters_llIIlIIll(killallrogangsters_lllIIIIlIlIIllIIIllIlllll(killallrogangsters_llllIIllllllll(killallrogangsters_lIllIlIIIlIllllIlIllll,killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_llIIIIllIlllIlllIIlI)),88))end return killallrogangsters_llIIIIllIIIlllIlIIlI(killallrogangsters_lIlIlIIllIlllIIlll);end;local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lIlIlIIllIlllIIlll;local function killallrogangsters_llIIIIllIIIlllIlIIlI(...)return{...},killallrogangsters_IlllIIlIllIlIllllIlIllII('#',...)end local function killallrogangsters_llIIlIlIIIlll()local killallrogangsters_lllIIIIlIlIIllIIIllIlllll={};local killallrogangsters_IIllllllllllIIlIlIIllIIl={};local killallrogangsters_llIIIIllIlllIlllIIlI={};local killallrogangsters_IIlIlIIlIIllllIIlllll={[#{"1 + 1 = 111";"1 + 1 = 111";}]=killallrogangsters_IIllllllllllIIlIlIIllIIl,[#{"1 + 1 = 111";{643;26;817;369};"1 + 1 = 111";}]=nil,[#{"1 + 1 = 111";{58;535;423;978};"1 + 1 = 111";"1 + 1 = 111";}]=killallrogangsters_llIIIIllIlllIlllIIlI,[#{{780;30;210;884};}]=killallrogangsters_lllIIIIlIlIIllIIIllIlllll,};local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lIlIlIIllIlllIIlll()local killallrogangsters_llIIlIIll={}for killallrogangsters_lIllIlIIIlIllllIlIllll=1,killallrogangsters_llIIIIllIlllIlllIIlI do local killallrogangsters_lIlIlIIllIlllIIlll=killallrogangsters_lIllIllIlIIIlIlIlIIl();local killallrogangsters_llIIIIllIlllIlllIIlI;if(killallrogangsters_lIlIlIIllIlllIIlll==1)then killallrogangsters_llIIIIllIlllIlllIIlI=(killallrogangsters_lIllIllIlIIIlIlIlIIl()~=0);elseif(killallrogangsters_lIlIlIIllIlllIIlll==3)then killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIlIIIllIIlI();elseif(killallrogangsters_lIlIlIIllIlllIIlll==0)then killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_IllIIIlIIIllllIIIl();end;killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll]=killallrogangsters_llIIIIllIlllIlllIIlI;end;for killallrogangsters_IIllllllllllIIlIlIIllIIl=1,killallrogangsters_lIlIlIIllIlllIIlll()do local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lIllIllIlIIIlIlIlIIl();if(killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_llIIIIllIlllIlllIIlI,1,1)==0)then local killallrogangsters_llllIIllllllll=killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_llIIIIllIlllIlllIIlI,2,3);local killallrogangsters_lIIllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_llIIIIllIlllIlllIIlI,4,6);local killallrogangsters_llIIIIllIlllIlllIIlI={killallrogangsters_lllIlllllIIl(),killallrogangsters_lllIlllllIIl(),nil,nil};if(killallrogangsters_llllIIllllllll==0)then killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";{836;625;966;403};"1 + 1 = 111";}]=killallrogangsters_lllIlllllIIl();killallrogangsters_llIIIIllIlllIlllIIlI[#("NIq7")]=killallrogangsters_lllIlllllIIl();elseif(killallrogangsters_llllIIllllllll==1)then killallrogangsters_llIIIIllIlllIlllIIlI[#("nJt")]=killallrogangsters_lIlIlIIllIlllIIlll();elseif(killallrogangsters_llllIIllllllll==2)then killallrogangsters_llIIIIllIlllIlllIIlI[#("VN1")]=killallrogangsters_lIlIlIIllIlllIIlll()-(2^16)elseif(killallrogangsters_llllIIllllllll==3)then killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";"1 + 1 = 111";{281;169;245;295};}]=killallrogangsters_lIlIlIIllIlllIIlll()-(2^16)killallrogangsters_llIIIIllIlllIlllIIlI[#("Ng76")]=killallrogangsters_lllIlllllIIl();end;if(killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_lIIllIlIllll,1,1)==1)then killallrogangsters_llIIIIllIlllIlllIIlI[#("FM")]=killallrogangsters_llIIlIIll[killallrogangsters_llIIIIllIlllIlllIIlI[#("hz")]]end if(killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_lIIllIlIllll,2,2)==1)then killallrogangsters_llIIIIllIlllIlllIIlI[#("VdX")]=killallrogangsters_llIIlIIll[killallrogangsters_llIIIIllIlllIlllIIlI[#("qzA")]]end if(killallrogangsters_lIllIlIIIlIllllIlIllll(killallrogangsters_lIIllIlIllll,3,3)==1)then killallrogangsters_llIIIIllIlllIlllIIlI[#("TYqW")]=killallrogangsters_llIIlIIll[killallrogangsters_llIIIIllIlllIlllIIlI[#("6HYL")]]end killallrogangsters_lllIIIIlIlIIllIIIllIlllll[killallrogangsters_IIllllllllllIIlIlIIllIIl]=killallrogangsters_llIIIIllIlllIlllIIlI;end end;killallrogangsters_IIlIlIIlIIllllIIlllll[3]=killallrogangsters_lIllIllIlIIIlIlIlIIl();for killallrogangsters_llIIIIllIlllIlllIIlI=1,killallrogangsters_lIlIlIIllIlllIIlll()do killallrogangsters_IIllllllllllIIlIlIIllIIl[killallrogangsters_llIIIIllIlllIlllIIlI-1]=killallrogangsters_llIIlIlIIIlll();end;return killallrogangsters_IIlIlIIlIIllllIIlllll;end;local function killallrogangsters_IllIIIlIIIllllIIIl(killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIllIlIIIlIlIlIIl)killallrogangsters_llIIIIllIlllIlllIIlI=(killallrogangsters_llIIIIllIlllIlllIIlI==true and killallrogangsters_llIIlIlIIIlll())or killallrogangsters_llIIIIllIlllIlllIIlI;return(function(...)local killallrogangsters_llIIlIIll=killallrogangsters_llIIIIllIlllIlllIIlI[1];local killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[3];local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI[2];local killallrogangsters_IIlIlIIlIIllllIIlllll=killallrogangsters_llIIIIllIIIlllIlIIlI local killallrogangsters_lIllIlIIIlIllllIlIllll=1;local killallrogangsters_lllIIIIlIlIIllIIIllIlllll=-1;local killallrogangsters_llIIlIlIIIlll={};local killallrogangsters_IIllllllllllIIlIlIIllIIl={...};local killallrogangsters_lllIlllllIIl=killallrogangsters_IlllIIlIllIlIllllIlIllII('#',...)-1;local killallrogangsters_llIIIIllIlllIlllIIlI={};local killallrogangsters_lIlIlIIllIlllIIlll={};for killallrogangsters_llIIIIllIlllIlllIIlI=0,killallrogangsters_lllIlllllIIl do if(killallrogangsters_llIIIIllIlllIlllIIlI>=killallrogangsters_llllIIllllllll)then killallrogangsters_llIIlIlIIIlll[killallrogangsters_llIIIIllIlllIlllIIlI-killallrogangsters_llllIIllllllll]=killallrogangsters_IIllllllllllIIlIlIIllIIl[killallrogangsters_llIIIIllIlllIlllIIlI+1];else killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_IIllllllllllIIlIlIIllIIl[killallrogangsters_llIIIIllIlllIlllIIlI+#{"1 + 1 = 111";}];end;end;local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lllIlllllIIl-killallrogangsters_llllIIllllllll+1 local killallrogangsters_llIIIIllIlllIlllIIlI;local killallrogangsters_llllIIllllllll;while true do killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#{{108;698;643;30};}];if killallrogangsters_llllIIllllllll<=#("frV4bPdUkBE87")then if killallrogangsters_llllIIllllllll<=#("NIzy61")then if killallrogangsters_llllIIllllllll<=#("zo")then if killallrogangsters_llllIIllllllll<=#("")then local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("e6")]local killallrogangsters_llllIIllllllll={killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIlIIIlIllllIlIllll+1,killallrogangsters_lllIIIIlIlIIllIIIllIlllll))};local killallrogangsters_llIIlIIll=0;for killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_lIllIlIIIlIllllIlIllll,killallrogangsters_llIIIIllIlllIlllIIlI[#("zGQu")]do killallrogangsters_llIIlIIll=killallrogangsters_llIIlIIll+1;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llllIIllllllll[killallrogangsters_llIIlIIll];end elseif killallrogangsters_llllIIllllllll>#("z")then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("bV")]]=killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";"1 + 1 = 111";{890;94;956;499};}];else local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("BX")];local killallrogangsters_llIIlIIll=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("B28")]];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll+1]=killallrogangsters_llIIlIIll;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll]=killallrogangsters_llIIlIIll[killallrogangsters_llIIIIllIlllIlllIIlI[#("aFim")]];end;elseif killallrogangsters_llllIIllllllll<=#("R6tv")then if killallrogangsters_llllIIllllllll==#("ctp")then if(killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("LI")]]==killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("lrsU")]])then killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;else killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("uDl")];end;else local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("nu")]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIlIIIlIllllIlIllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("yoN")]))end;elseif killallrogangsters_llllIIllllllll==#{"1 + 1 = 111";{537;652;235;900};{558;143;287;624};{714;439;221;163};"1 + 1 = 111";}then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("33")]]=killallrogangsters_lIllIllIlIIIlIlIlIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("HcD")]];else do return end;end;elseif killallrogangsters_llllIIllllllll<=#("77kaQOd9m")then if killallrogangsters_llllIIllllllll<=#("9IxQdes")then killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("iaX")];elseif killallrogangsters_llllIIllllllll==#("4vY0fs5O")then local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("Js")]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIlIIIlIllllIlIllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("8Cb")]))else local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI[#("Cm")]local killallrogangsters_llIIlIIll,killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_IIlIlIIlIIllllIIlllll(killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI](killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI+1]))killallrogangsters_lllIIIIlIlIIllIIIllIlllll=killallrogangsters_lIllIlIIIlIllllIlIllll+killallrogangsters_llIIIIllIlllIlllIIlI-1 local killallrogangsters_lIllIlIIIlIllllIlIllll=0;for killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_lllIIIIlIlIIllIIIllIlllll do killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];end;end;elseif killallrogangsters_llllIIllllllll<=#("JiSRhJ6CqFL")then if killallrogangsters_llllIIllllllll==#("gN6hPlF6Ka")then local killallrogangsters_lllIlllllIIl;local killallrogangsters_llllIIllllllll;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("sv")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("5dU")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("xyDp")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("4S")];killallrogangsters_lllIlllllIIl=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+1]=killallrogangsters_lllIlllllIIl;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_lllIlllllIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("G598")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("sM")]]=killallrogangsters_llIIIIllIlllIlllIIlI[#("QkI")];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("5N")]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llllIIllllllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("OvT")]))killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("Ip")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("eb0")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("2JL0")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";"1 + 1 = 111";}];killallrogangsters_lllIlllllIIl=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("AeM")]];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+1]=killallrogangsters_lllIlllllIIl;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_lllIlllllIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("oMk4")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("Qz")]]=killallrogangsters_llIIIIllIlllIlllIIlI[#("6L3")];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("zX")]]=killallrogangsters_lIllIllIlIIIlIlIlIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("UAk")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("DM")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("1bK")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("g25Z")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("PI")];killallrogangsters_lllIlllllIIl=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("Tgq")]];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+1]=killallrogangsters_lllIlllllIIl;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_lllIlllllIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("i8UJ")]];else killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";"1 + 1 = 111";}]]=killallrogangsters_lIllIllIlIIIlIlIlIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("86c")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("jT")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("FJk")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("CFGb")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("SG")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("r3y")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("IeIz")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";"1 + 1 = 111";}]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("MFI")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("DHRF")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];if(killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("hs")]]==killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("B3r4")]])then killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;else killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("BGi")];end;end;elseif killallrogangsters_llllIIllllllll==#("yd55zg22eccF")then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("rv")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("tR6")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("KgzE")]];else local killallrogangsters_lllIlllllIIl;local killallrogangsters_llllIIllllllll;killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("p5")]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llllIIllllllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("aKc")]))killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#{{201;227;174;229};{901;926;295;1};}]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("WBk")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("FCNt")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("J3")]]=killallrogangsters_llIIIIllIlllIlllIIlI[#("VQI")];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("XC")]]=killallrogangsters_lIllIllIlIIIlIlIlIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("cpT")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("gO")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("Agr")]][killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#{{476;854;216;730};"1 + 1 = 111";}];killallrogangsters_lllIlllllIIl=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("cov")]];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+1]=killallrogangsters_lllIlllllIIl;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_lllIlllllIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("ydKg")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#{{676;2;55;923};"1 + 1 = 111";}]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("DT0")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("kdVo")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("M5")]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llllIIllllllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("7u0")]))killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("kr")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("aXv")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("JkBK")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("Yq")]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llllIIllllllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("HIa")]))end;elseif killallrogangsters_llllIIllllllll<=#("E818BoXKR4XT1TAhBRcI")then if killallrogangsters_llllIIllllllll<=#("uOmOHvyNHQeheNRu")then if killallrogangsters_llllIIllllllll<=#("FunUQjhmHxCVOu")then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("5k")]]=killallrogangsters_llIIIIllIlllIlllIIlI[#("TAl")];elseif killallrogangsters_llllIIllllllll==#("7djuPu42z7knTLX")then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("fA")]]=killallrogangsters_lIllIllIlIIIlIlIlIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("6fY")]];else local killallrogangsters_llIIlIIll=killallrogangsters_llIIIIllIlllIlllIIlI[#("fK")];local killallrogangsters_lIIllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("pRZB")];local killallrogangsters_llllIIllllllll=killallrogangsters_llIIlIIll+2 local killallrogangsters_llIIlIIll={killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIlIIll](killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIlIIll+1],killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll])};for killallrogangsters_llIIIIllIlllIlllIIlI=1,killallrogangsters_lIIllIlIllll do killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llIIlIIll[killallrogangsters_llIIIIllIlllIlllIIlI];end;local killallrogangsters_llIIlIIll=killallrogangsters_llIIlIIll[1]if killallrogangsters_llIIlIIll then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_llIIlIIll killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("WWG")];else killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;end;end;elseif killallrogangsters_llllIIllllllll<=#{{92;407;363;704};{855;478;261;177};{448;51;122;674};"1 + 1 = 111";{924;375;752;192};"1 + 1 = 111";{591;813;398;623};"1 + 1 = 111";"1 + 1 = 111";{342;53;689;819};"1 + 1 = 111";{379;836;88;662};{627;466;324;234};{448;697;522;948};{662;326;848;194};{764;636;286;766};"1 + 1 = 111";{381;956;798;694};}then if killallrogangsters_llllIIllllllll==#("bExPkLDZXF5zMUrT8")then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("6L")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("zem")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("ugbx")]];else if(killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("Z5")]]==killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("gBov")]])then killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;else killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("nQj")];end;end;elseif killallrogangsters_llllIIllllllll>#("irOaF0K444Dfs3OAVMx")then local killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#{{653;407;226;679};"1 + 1 = 111";}];local killallrogangsters_lIIllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("rghg")];local killallrogangsters_llIIlIIll=killallrogangsters_llllIIllllllll+2 local killallrogangsters_llllIIllllllll={killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll](killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+1],killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIlIIll])};for killallrogangsters_llIIIIllIlllIlllIIlI=1,killallrogangsters_lIIllIlIllll do killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIlIIll+killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llllIIllllllll[killallrogangsters_llIIIIllIlllIlllIIlI];end;local killallrogangsters_llllIIllllllll=killallrogangsters_llllIIllllllll[1]if killallrogangsters_llllIIllllllll then killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIlIIll]=killallrogangsters_llllIIllllllll killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";{873;368;653;671};{411;527;585;93};}];else killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;end;else killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("ZqC")];end;elseif killallrogangsters_llllIIllllllll<=#("TLoFpiIQYoRm3ilXHa8GfqQ")then if killallrogangsters_llllIIllllllll<=#("vSmcUl9Px1aIdiUvs3fQn")then local killallrogangsters_llllIIllllllll;local killallrogangsters_lllIlllllIIl;local killallrogangsters_IIllllllllllIIlIlIIllIIl,killallrogangsters_IlllIIlIllIlIllllIlIllII;local killallrogangsters_llIIlIlIIIlll;local killallrogangsters_llllIIllllllll;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("1c")]]=killallrogangsters_lIllIllIlIIIlIlIlIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("4Z0")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("RM")]]=killallrogangsters_lIllIllIlIIIlIlIlIIl[killallrogangsters_llIIIIllIlllIlllIIlI[#("gCi")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("gO")]]=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("cAA")]][killallrogangsters_llIIIIllIlllIlllIIlI[#("xtkj")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("nG")];killallrogangsters_llIIlIlIIIlll=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("5PB")]];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+1]=killallrogangsters_llIIlIlIIIlll;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll]=killallrogangsters_llIIlIlIIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("GujQ")]];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("QU")]killallrogangsters_IIllllllllllIIlIlIIllIIl,killallrogangsters_IlllIIlIllIlIllllIlIllII=killallrogangsters_IIlIlIIlIIllllIIlllll(killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll](killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll+1]))killallrogangsters_lllIIIIlIlIIllIIIllIlllll=killallrogangsters_IlllIIlIllIlIllllIlIllII+killallrogangsters_llllIIllllllll-1 killallrogangsters_lllIlllllIIl=0;for killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llllIIllllllll,killallrogangsters_lllIIIIlIlIIllIIIllIlllll do killallrogangsters_lllIlllllIIl=killallrogangsters_lllIlllllIIl+1;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_IIllllllllllIIlIlIIllIIl[killallrogangsters_lllIlllllIIl];end;killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_llllIIllllllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("e1")]killallrogangsters_IIllllllllllIIlIlIIllIIl={killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llllIIllllllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llllIIllllllll+1,killallrogangsters_lllIIIIlIlIIllIIIllIlllll))};killallrogangsters_lllIlllllIIl=0;for killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llllIIllllllll,killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";{220;328;815;188};{25;926;153;191};{910;7;787;780};}]do killallrogangsters_lllIlllllIIl=killallrogangsters_lllIlllllIIl+1;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_IIllllllllllIIlIlIIllIIl[killallrogangsters_lllIlllllIIl];end killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("ZN2")];elseif killallrogangsters_llllIIllllllll>#("ljR13VN0bC4RiI6G5Npb0c")then local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("0b")]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIlIIIlIllllIlIllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("KJQ")]))else local killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI[#("Ca")]local killallrogangsters_llIIlIIll,killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_IIlIlIIlIIllllIIlllll(killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI](killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI+1]))killallrogangsters_lllIIIIlIlIIllIIIllIlllll=killallrogangsters_lIllIlIIIlIllllIlIllll+killallrogangsters_llIIIIllIlllIlllIIlI-1 local killallrogangsters_lIllIlIIIlIllllIlIllll=0;for killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIIIllIlllIlllIIlI,killallrogangsters_lllIIIIlIlIIllIIIllIlllll do killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llIIlIIll[killallrogangsters_lIllIlIIIlIllllIlIllll];end;end;elseif killallrogangsters_llllIIllllllll<=#("OTypNnmlaugGcu3rncGZINx9l")then if killallrogangsters_llllIIllllllll>#("W7CAlzjcdhGFaNZq4vcc4kcu")then local killallrogangsters_llIIlIIll=killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";{483;486;89;404};}]local killallrogangsters_llllIIllllllll={killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIlIIll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_llIIlIIll+1,killallrogangsters_lllIIIIlIlIIllIIIllIlllll))};local killallrogangsters_lIllIlIIIlIllllIlIllll=0;for killallrogangsters_llIIIIllIlllIlllIIlI=killallrogangsters_llIIlIIll,killallrogangsters_llIIIIllIlllIlllIIlI[#("0v9U")]do killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI]=killallrogangsters_llllIIllllllll[killallrogangsters_lIllIlIIIlIllllIlIllll];end else do return end;end;elseif killallrogangsters_llllIIllllllll==#{{749;925;457;361};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{854;367;626;114};"1 + 1 = 111";"1 + 1 = 111";{554;780;310;676};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{945;822;326;13};"1 + 1 = 111";"1 + 1 = 111";{178;85;892;808};"1 + 1 = 111";{850;833;285;502};"1 + 1 = 111";{336;752;900;669};{797;389;757;796};{102;534;951;885};{457;939;910;873};{686;954;206;960};{971;759;788;502};"1 + 1 = 111";{44;903;391;183};}then local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#("QW")];local killallrogangsters_llIIlIIll=killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_llIIIIllIlllIlllIIlI[#("y7o")]];killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll+1]=killallrogangsters_llIIlIIll;killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll]=killallrogangsters_llIIlIIll[killallrogangsters_llIIIIllIlllIlllIIlI[#{"1 + 1 = 111";{32;61;706;157};"1 + 1 = 111";{260;395;570;721};}]];else local killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_llIIIIllIlllIlllIIlI[#{{813;241;145;755};"1 + 1 = 111";}]killallrogangsters_lIlIlIIllIlllIIlll[killallrogangsters_lIllIlIIIlIllllIlIllll](killallrogangsters_lIIllIlIllll(killallrogangsters_lIlIlIIllIlllIIlll,killallrogangsters_lIllIlIIIlIllllIlIllll+1,killallrogangsters_llIIIIllIlllIlllIIlI[#("AVg")]))end;killallrogangsters_lIllIlIIIlIllllIlIllll=killallrogangsters_lIllIlIIIlIllllIlIllll+1;end;end);end;return killallrogangsters_IllIIIlIIIllllIIIl(true,{},killallrogangsters_IIIIlllIlIl())();end)(string.byte,table.insert,setmetatable);
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
UnlockCar.Position = UDim2.new(0.0442163423, 0, 0.752417207, 0)
UnlockCar.Size = UDim2.new(0, 110, 0, 40)
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
while true do
wait()
local A_1 = "PickPrinter"
local A_2 = game:GetService("Workspace").Entities["Simple Printer"]
local A_3 = game:GetService("Workspace").RayIgnore["LocalPlayer"].Lockpick
local Event = game:GetService("ReplicatedStorage")["_CS.Events"].ToolEvent
Event:FireServer(A_1, A_2, A_3)
wait()
local A_1 = game:GetService("Workspace").Entities["Simple Printer"]
local Event = game:GetService("ReplicatedStorage")["_CS.Events"].UsePrinter
Event:FireServer(A_1)
end
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

-- Scripts:

local function BXVTW_fake_script() 
	local script = Instance.new('LocalScript', AnomicAlpha)

	while true do
		if game.Players.LocalPlayer.Name == "Plsgivemeskinslol" or "" or "" or "" or "" or "" or "" then
			wait()
		else
			game.Players.LocalPlayer:kick("You are not Whitelisted")
			script.Parent:Destroy()
		end
	end
end
coroutine.wrap(BXVTW_fake_script)()
