local Gui = Instance.new('ScreenGui')
local frame = Instance.new('Frame')
local button1 = Instance.new('TextButton',frame)
local button2 = Instance.new('TextButton',frame)
local button3 = Instance.new('TextButton',frame)
local button4 = Instance.new('TextButton',frame)
local button5 = Instance.new('TextButton',frame)
local button6 = Instance.new('TextButton',frame)
local button7 = Instance.new('TextButton',frame)
local button8 = Instance.new('TextButton',frame)
local button9 = Instance.new('TextButton',frame)
local button10 = Instance.new('TextButton',frame)
local button11 = Instance.new('TextButton',frame)
local button12 = Instance.new('TextButton',frame)
local button13 = Instance.new('TextButton',frame)

print("Trix Hub Loaded !")

game.StarterGui:SetCore("SendNotification", {
    Title = "Lol hub",
    Text = "Lol Hub loaded !",
    Duration = "2"
})

frame.Visible = true


Gui.Parent = game.CoreGui
Gui.Name = "Best mm2 Gui"

frame.Parent = Gui
frame.Name = "MainFrame"
frame.Size = UDim2.new(0,450,0,350)
frame.BackgroundColor3 = Color3.fromRGB()
frame.AnchorPoint = Vector2.new(0.5, 0.5)
frame.Position = UDim2.new(0.5, 0, 0.5, 0)
frame.Draggable = true
frame.Active = true

button1.Text = "E-Hoax V2"
button1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button1.BorderColor3 = Color3.new(0, 0, 0)
button1.Font=Enum.Font.Ubuntu
button1.TextScaled = true
button1.Size = UDim2.new(0,450,0,20)
button1.Position = UDim2.new(0, 0, 0, 50)
button1.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet(("https://cdn.julman.fr/scripts/33.lua"), true))()
end)

button2.Text = "Op Script"
button2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button2.BorderColor3 = Color3.new(0, 0, 0)
button2.Font=Enum.Font.Ubuntu
button2.TextScaled = true
button2.Size = UDim2.new(0,450,0,20)
button2.Position = UDim2.new(0, 0, 0, 75)
button2.MouseButton1Click:Connect(function()
    pcall(loadstring(game:HttpGet("https://pastebin.com/raw/RjLQKZxZ")))
end)

button3.Text = "ReaperX"
button3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button3.BorderColor3 = Color3.new(0, 0, 0)
button3.Font=Enum.Font.Ubuntu
button3.TextScaled = true
button3.Size = UDim2.new(0,450,0,20)
button3.Position = UDim2.new(0, 0, 0, 100)
button3.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/HydraVirgo/ninjalegendsfreegui/main/obfusc", true))()
end)

button4.Text = "Ninja Hub"
button4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button4.BorderColor3 = Color3.new(0, 0, 0)
button4.Font=Enum.Font.Ubuntu
button4.TextScaled = true
button4.Size = UDim2.new(0,450,0,20)
button4.Position = UDim2.new(0, 0, 0, 125)
button4.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Be3pis/NinjaLegends/main/Script.lua"))()
end)

button5.Text = "Nja Leg Script"
button5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button5.BorderColor3 = Color3.new(0, 0, 0)
button5.Font=Enum.Font.Ubuntu
button5.TextScaled = true
button5.Size = UDim2.new(0,450,0,20)
button5.Position = UDim2.new(0, 0, 0, 150)
button5.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet("https://pastebin.com/raw/7LdQXg9F"))()
end)

button6.Text = "Project Autismo"
button6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button6.BorderColor3 = Color3.new(0, 0, 0)
button6.Font=Enum.Font.Ubuntu
button6.TextScaled = true
button6.Size = UDim2.new(0,450,0,20)
button6.Position = UDim2.new(0, 0, 0, 175)
button6.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet("https://pastebin.com/raw/JsqsKyyb"))()
end)

button7.Text = "Vinyxu's"
button7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button7.BorderColor3 = Color3.new(0, 0, 0)
button7.Font=Enum.Font.Ubuntu
button7.TextScaled = true
button7.Size = UDim2.new(0,450,0,20)
button7.Position = UDim2.new(0, 0, 0, 200)
button7.MouseButton1Click:Connect(function()
    loadstring(game:GetObjects("rbxassetid://4229359911")[1].Source)()
end)

button8.Text = "Glurak Hub"
button8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button8.BorderColor3 = Color3.new(0, 0, 0)
button8.Font=Enum.Font.Ubuntu
button8.TextScaled = true
button8.Size = UDim2.new(0,450,0,20)
button8.Position = UDim2.new(0, 0, 0, 225)
button8.MouseButton1Click:Connect(function()
    pcall(loadstring(game:HttpGet("https://raw.githubusercontent.com/TrixAde/scripts/main/ninjalegends2.lua")))
end)

button9.Text = "Allinity"
button9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button9.BorderColor3 = Color3.new(0, 0, 0)
button9.Font=Enum.Font.Ubuntu
button9.TextScaled = true
button9.Size = UDim2.new(0,450,0,20)
button9.Position = UDim2.new(0, 0, 0, 250)
button9.MouseButton1Click:Connect(function()
    loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Allinity/Allinity-Hub/main/AllinityHubv.1.lua"))()
end)

button10.Text = "Nja Rbx Script"
button10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button10.BorderColor3 = Color3.new(0, 0, 0)
button10.Font=Enum.Font.Ubuntu
button10.TextScaled = true
button10.Size = UDim2.new(0,450,0,20)
button10.Position = UDim2.new(0, 0, 0, 275)
button10.MouseButton1Click:Connect(function()
    pcall(loadstring(game:HttpGet("https://pastebin.com/raw/w1si3pmr")))
end)

button11.Text = "Bloody"
button11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button11.BorderColor3 = Color3.new(0, 0, 0)
button11.Font=Enum.Font.Ubuntu
button11.TextScaled = true
button11.Size = UDim2.new(0,450,0,20)
button11.Position = UDim2.new(0, 0, 0, 300)
button11.MouseButton1Click:Connect(function()
    pcall(loadstring(game:HttpGet("https://pastebin.com/raw/V7CeHpPr")))
end)

button12.Text = "Nja Gui"
button12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button12.BorderColor3 = Color3.new(0, 0, 0)
button12.Font=Enum.Font.Ubuntu
button12.TextScaled = true
button12.Size = UDim2.new(0,450,0,20)
button12.Position = UDim2.new(0, 0, 0, 325)
button12.MouseButton1Click:Connect(function()
    loadstring(game:GetObjects('rbxassetid://4245416549')[1].Source)()
end)

button13.Text = "Nja 2"
button13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button13.BorderColor3 = Color3.new(0, 0, 0)
button13.Font=Enum.Font.Ubuntu
button13.TextScaled = true
button13.Size = UDim2.new(0,450,0,20)
button13.Position = UDim2.new(0, 0, 0, 350)
button13.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet("https://sinnyno1.github.io/King-Hack/Script/Ninja-Legend-2.lua",true))();
end)

