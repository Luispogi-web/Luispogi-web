-- Create the ScreenGui
local menuGui = Instance.new("ScreenGui")
menuGui.Name = "random script-All not mine"
menuGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

-- Create the Frame to hold the menu
local menuFrame = Instance.new("Frame")
menuFrame.Name = "random script-All not mine"
menuFrame.Size = UDim2.new(0, 200, 0, 300)
menuFrame.Position = UDim2.new(0.5, -100, 0.5, -150)
menuFrame.BackgroundColor3 = Color3.new(0.2, 0.2, 0.2)
menuFrame.BorderSizePixel = 2
menuFrame.Parent = menuGui

-- Create buttons for the menu
local button1 = Instance.new("loadstring(game:HttpGet('https://raw.githubusercontent.com/wenny69420/KirbswareScripts/main/MobileV3'))()")
button1.Name = "VascalSHM"
button1.Size = UDim2.new(0, 180, 0, 50)
button1.Position = UDim2.new(0.5, -90, 0.1, 0)
button1.BackgroundColor3 = Color3.new(0.4, 0.4, 0.4)
button1.TextColor3 = Color3.new(1, 1, 1)
button1.Text = "VascalSHM"
button1.Parent = menuFrame

local button2 = Instance.new("loadstring(game:HttpGet('https://raw.githubusercontent.com/wenny69420/KirbswareScripts/main/MobileV3'))()")
button2.Name = "Kirbsware"
button2.Size = UDim2.new(0, 180, 0, 50)
button2.Position = UDim2.new(0.5, -90, 0.3, 0)
button2.BackgroundColor3 = Color3.new(0.4, 0.4, 0.4)
button2.TextColor3 = Color3.new(1, 1, 1)
button2.Text = "kirbsware"
button2.Parent = menuFrame

-- Function to handle button clicks
local function onButtonClick()
    print("Button clicked!")
    -- Add your desired functionality here
end

-- Connect button click events to the function
button1.MouseButton1Click:Connect(onButtonClick)
button2.MouseButton1Click:Connect(onButtonClick)
