local SCpl = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Botao1 = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local BotaoDesc = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local Botao2 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local Botao3 = Instance.new("TextButton")
local msg = Instance.new("TextBox")
local Botao4 = Instance.new("TextButton")
local plr = Instance.new("TextBox")
local Botao5 = Instance.new("TextButton")
local onoff = Instance.new("TextButton")
SCpl.Name = "SCpl"
SCpl.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
SCpl.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = SCpl
Frame.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
Frame.BackgroundTransparency = 0.450
Frame.BorderColor3 = Color3.fromRGB(255, 0, 0)
Frame.BorderSizePixel = 2
Frame.Position = UDim2.new(0.367843747, 0, 0.293388426, 0)
Frame.Size = UDim2.new(0.263852239, 0, 0.413223147, 0)

Botao1.Name = "Botao1"
Botao1.Parent = Frame
Botao1.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Botao1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Botao1.BorderSizePixel = 0
Botao1.Position = UDim2.new(0.109999999, 0, 0.0599999987, 0)
Botao1.Size = UDim2.new(0.333333343, 0, 0.155000001, 0)
Botao1.Font = Enum.Font.SourceSans
Botao1.Text = "Votos Internos"
Botao1.TextColor3 = Color3.fromRGB(255, 255, 255)
Botao1.TextScaled = true
Botao1.TextSize = 14.000
Botao1.TextWrapped = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.186666667, 0, -0.25, 0)
TextLabel.Size = UDim2.new(0.666666687, 0, 0.25, 0)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Reddyn Fucker xD v0.1"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextStrokeTransparency = 0.000
TextLabel.TextWrapped = true
TextLabel.TextYAlignment = Enum.TextYAlignment.Bottom

BotaoDesc.Name = "BotaoDesc"
BotaoDesc.Parent = Frame
BotaoDesc.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
BotaoDesc.BorderColor3 = Color3.fromRGB(0, 0, 0)
BotaoDesc.BorderSizePixel = 0
BotaoDesc.Position = UDim2.new(1.08333337, 0, 0, 0)
BotaoDesc.Size = UDim2.new(0.720000029, 0, 0.610000014, 0)
BotaoDesc.Visible = false

TextLabel_2.Parent = BotaoDesc
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Size = UDim2.new(1, 0, 1, 0)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

Botao2.Name = "Botao2"
Botao2.Parent = Frame
Botao2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Botao2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Botao2.BorderSizePixel = 0
Botao2.Position = UDim2.new(0.553333342, 0, 0.0599999987, 0)
Botao2.Size = UDim2.new(0.333333343, 0, 0.155000001, 0)
Botao2.Font = Enum.Font.SourceSans
Botao2.Text = "Musicas"
Botao2.TextColor3 = Color3.fromRGB(255, 255, 255)
Botao2.TextScaled = true
Botao2.TextSize = 14.000
Botao2.TextWrapped = true

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0, 0, 1, 0)
TextLabel_3.Size = UDim2.new(1, 0, 0.25, 0)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Feito por / Made by: @vscxrpion -> Discord"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextStrokeTransparency = 0.000
TextLabel_3.TextWrapped = true
TextLabel_3.TextYAlignment = Enum.TextYAlignment.Top

Botao3.Name = "Botao3"
Botao3.Parent = Frame
Botao3.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Botao3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Botao3.BorderSizePixel = 0
Botao3.Position = UDim2.new(0.646666646, 0, 0.814999998, 0)
Botao3.Size = UDim2.new(0.333333343, 0, 0.155000001, 0)
Botao3.Font = Enum.Font.SourceSans
Botao3.Text = "Enviar mensagem ao servidor"
Botao3.TextColor3 = Color3.fromRGB(255, 255, 255)
Botao3.TextScaled = true
Botao3.TextSize = 14.000
Botao3.TextWrapped = true

msg.Name = "msg"
msg.Parent = Frame
msg.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
msg.BorderColor3 = Color3.fromRGB(0, 0, 0)
msg.BorderSizePixel = 0
msg.Position = UDim2.new(0.646666646, 0, 0.629999995, 0)
msg.Size = UDim2.new(0.333333343, 0, 0.144999996, 0)
msg.Font = Enum.Font.SourceSans
msg.PlaceholderText = "Mensagem"
msg.Text = "Mensagem"
msg.TextColor3 = Color3.fromRGB(255, 255, 255)
msg.TextScaled = true
msg.TextSize = 14.000
msg.TextWrapped = true

Botao4.Name = "Botao4"
Botao4.Parent = Frame
Botao4.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Botao4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Botao4.BorderSizePixel = 0
Botao4.Position = UDim2.new(0.0233333334, 0, 0.814999998, 0)
Botao4.Size = UDim2.new(0.333333343, 0, 0.155000001, 0)
Botao4.Font = Enum.Font.SourceSans
Botao4.Text = "Muitos Votos"
Botao4.TextColor3 = Color3.fromRGB(255, 255, 255)
Botao4.TextScaled = true
Botao4.TextSize = 14.000
Botao4.TextWrapped = true

plr.Name = "plr"
plr.Parent = Frame
plr.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
plr.BorderColor3 = Color3.fromRGB(0, 0, 0)
plr.BorderSizePixel = 0
plr.Position = UDim2.new(0.0233333334, 0, 0.629999995, 0)
plr.Size = UDim2.new(0.333333343, 0, 0.144999996, 0)
plr.Font = Enum.Font.SourceSans
plr.PlaceholderText = "Quem"
plr.Text = "Quem"
plr.TextColor3 = Color3.fromRGB(255, 255, 255)
plr.TextScaled = true
plr.TextSize = 14.000
plr.TextWrapped = true

Botao5.Name = "Botao5"
Botao5.Parent = Frame
Botao5.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Botao5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Botao5.BorderSizePixel = 0
Botao5.Position = UDim2.new(0.106813461, 0, 0.264999986, 0)
Botao5.Size = UDim2.new(0.333333343, 0, 0.155000001, 0)
Botao5.Font = Enum.Font.SourceSans
Botao5.Text = "Bugar Servidor"
Botao5.TextColor3 = Color3.fromRGB(255, 255, 255)
Botao5.TextScaled = true
Botao5.TextSize = 14.000
Botao5.TextWrapped = true

onoff.Name = "onoff"
onoff.Parent = SCpl
onoff.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
onoff.BorderColor3 = Color3.fromRGB(255, 0, 0)
onoff.BorderSizePixel = 2
onoff.Position = UDim2.new(0.189094231, 0, 0.0247933883, 0)
onoff.Size = UDim2.new(0.0291005298, 0, 0.0495867766, 0)
onoff.Font = Enum.Font.SourceSans
onoff.Text = "-"
onoff.TextColor3 = Color3.fromRGB(255, 255, 255)
onoff.TextScaled = true
onoff.TextSize = 14.000
onoff.TextStrokeTransparency = 0.000
onoff.TextWrapped = true

-- Scripts:

local function EQCOAAA_fake_script() -- SCpl.MainSC 
	local script = Instance.new('LocalScript', SCpl)

	local framebase = script.Parent:WaitForChild("Frame")
	local botao1 = framebase:WaitForChild("Botao1")
	framebase.Active = true
	framebase.Draggable = true
	local minbutton = script.Parent.onoff
	minbutton.Active = true
	minbutton.Draggable = true
	local db1 = true
	minbutton.MouseButton1Click:Connect(function()
		if db1 == true then
			db1 = not db1
			framebase.Visible = false
			minbutton.Text = "+"
		elseif db1 == false then
			db1 = not db1
			framebase.Visible = true
		minbutton.Text = "-"
		end
	end)
	--
	for i, v in pairs(framebase:GetChildren()) do
		if v:IsA("TextButton")  then
			v.MouseEnter:Connect(function()
			  framebase.BotaoDesc.Visible = true
			  if v.Name == "Botao1" then
					framebase.BotaoDesc.TextLabel.Text = "Se houver um painel de votação dentro da casa onde se pode adicionar e remover votos, ao pressionar este botão você possuirá o acesso que apenas produtores possuem"
			  elseif v.Name == "Botao2" then
					framebase.BotaoDesc.TextLabel.Text = "Tenha acesso ao painel exclusivo dos produtores e controle as musicas do servidor"
			  elseif v.Name == "Botao3" then
					framebase.BotaoDesc.TextLabel.Text = "Envie uma mensagem ao servidor xD"
			  elseif v.Name == "Botao4" then
					framebase.BotaoDesc.TextLabel.Text = "Se estiver acontecendo uma votação no jogo, coloque o nick do player que você deseja colocar muitos votos e spamme o botão xD"
				elseif v.Name == "Botao5" then
					framebase.BotaoDesc.TextLabel.Text = "Tente procurar as vulnerabilidades do jogo, caso seja achado será tudo executado"
				end
			  
			  v.MouseLeave:Connect(function()
					framebase.BotaoDesc.Visible = false
			  end)
			end)
		end
	end
	--
	local debounce1 = true
	local debounce2 = true
	for i, v in pairs(framebase:GetChildren()) do
		if v:IsA("TextButton") then
			v.MouseButton1Click:Connect(function()
				if v.Name == "Botao1" then
					local localname = game.Players.LocalPlayer.Name
	
					for i, v in pairs(game.Players[localname].PlayerGui.ScreenGui:GetChildren()) do
						if v:IsA("Frame") then
							v.Visible = debounce1
							game.Players[localname].PlayerGui.ScreenGui.Frame.Visible = true
							debounce1 = not debounce1
						end
					end
				elseif v.Name == "Botao2" then
					local localname = game.Players.LocalPlayer.Name
	
					for i, v in pairs(game.Players[localname].PlayerGui.Musicas:GetChildren()) do
						if v:IsA("Frame") then
							v.Visible = debounce2
							debounce2 = not debounce2
						end	
					end
					
				elseif v.Name == "Botao3" then
					if game.ReplicatedStorage:FindFirstChild("Mensagem") then
						local evento = game.ReplicatedStorage:WaitForChild("Mensagem")
						evento:FireServer(framebase.msg.Text, "fuckniggas", game.CreatorId)
					elseif game.ReplicatedStorage:FindFirstChild("Apresentador") then
						local evento = game.ReplicatedStorage:WaitForChild("Apresentador")
						evento:FireServer(framebase.msg.Text, "fuckniggas", game.CreatorId)
					end
					
					
				elseif v.Name == "Botao4" then
					if game.ReplicatedStorage:FindFirstChild("Voto") then
						local EV = game.ReplicatedStorage.Voto
						while wait(0.1) do
							EV:FireServer(framebase.plr.Text)
						end
					elseif game.ReplicatedStorage:FindFirstChild("votacao_para_ficar") then
						local EV = game.ReplicatedStorage.votacao_para_ficar
						while wait(0.1) do
							EV:FireServer(framebase.plr.Text)
						end
					elseif game.ReplicatedStorage:FindFirstChild("Votar") then
						local EV = game.ReplicatedStorage.votacao_para_ficar
						while wait(0.1) do
							EV:InvokeServer(framebase.plr.Text)
						end
					end
				elseif v.Name == "Botao5" then
					if game.ReplicatedStorage:FindFirstChild("Iniciar") then
						game.ReplicatedStorage.Iniciar:FireServer()
					end
					
				end
				
				
				
			end)
			end
	end
	
	
end
coroutine.wrap(EQCOAAA_fake_script)()
