-- Gui to Lua
-- BY SCORPION

-- REDDYN FUCKER

local Screen = Instance.new("ScreenGui")
local reddyneocaralho = Instance.new("Frame")
local Musica = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Lag = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local UICorner_3 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
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

Musica.Name = "Musica"
Musica.Parent = reddyneocaralho
Musica.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Musica.BorderColor3 = Color3.fromRGB(0, 0, 0)
Musica.BorderSizePixel = 0
Musica.Position = UDim2.new(0.0705003738, 0, 0.256410271, 0)
Musica.Size = UDim2.new(0.346606374, 0, 0.134615391, 0)
Musica.Font = Enum.Font.SourceSans
Musica.Text = "Musica midia"
Musica.TextColor3 = Color3.fromRGB(0, 0, 0)
Musica.TextScaled = true
Musica.TextSize = 14.000
Musica.TextWrapped = true

UICorner.Parent = Musica

Lag.Name = "Lag"
Lag.Parent = reddyneocaralho
Lag.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
Lag.BorderColor3 = Color3.fromRGB(0, 0, 0)
Lag.BorderSizePixel = 0
Lag.Position = UDim2.new(0.0705003738, 0, 0.0736635625, 0)
Lag.Size = UDim2.new(0.346606523, 0, 0.111799218, 0)
Lag.Font = Enum.Font.SourceSans
Lag.Text = "LagarServidor"
Lag.TextColor3 = Color3.fromRGB(0, 0, 0)
Lag.TextScaled = true
Lag.TextSize = 14.000
Lag.TextWrapped = true

UICorner_2.Parent = Lag

UICorner_3.Parent = reddyneocaralho

TextBox.Parent = reddyneocaralho
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 127)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.418762594, 0, 0.801282048, 0)
TextBox.Size = UDim2.new(0.502515137, 0, 0.15384616, 0)
TextBox.Font = Enum.Font.SourceSans
TextBox.PlaceholderText = "ID musica"
TextBox.Text = "ID musica"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

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
TextLabel_2.Text = "v1.4.2"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(48, 12, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_2.Parent = TextLabel_2

-- Scripts:

local function KJJCRU_fake_script() -- Screen.LocalScript 
	local script = Instance.new('LocalScript', Screen)

	--
	script.Parent.reddyneocaralho.Musica.MouseButton1Down:Connect(function()
	    local sound = true 
		local ID = "rbxassetid://"..script.Parent.reddyneocaralho.TextBox.Text 
		local Name = "Ambiente" 
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
	--
	script.Parent.reddyneocaralho.Lag.MouseButton1Click:Connect(function()
		
	end)
	--
end
coroutine.wrap(KJJCRU_fake_script)()
