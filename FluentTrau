local Blur = Instance.new("BlurEffect")
Blur.Size = 100
Blur.Enabled = true
Blur.Parent = game.Lighting

if not game.CoreGui:FindFirstChild("ThunderScreen") then
    local ThunderScreen = Instance.new("ScreenGui")
    local ThunderToggleUI = Instance.new("TextButton")
    local ThunderCornerUI = Instance.new("UICorner")
    local ThunderImageUI = Instance.new("ImageLabel")
    local TestLabelEN = Instance.new("TextLabel")
    local TestLabelVN = Instance.new("TextLabel")

    ThunderScreen.Name = "Copy Discord Link (New Link)"
    ThunderScreen.Parent = game.CoreGui
    ThunderScreen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

    ThunderToggleUI.Name = "ThunderToggleUI"
    ThunderToggleUI.Parent = ThunderScreen
    ThunderToggleUI.BackgroundColor3 = Color3.fromRGB(244, 244, 0)
    ThunderToggleUI.Position = UDim2.new(0.5, -75, 0.0952890813, 0)  -- Đã căn giữa
    ThunderToggleUI.Size = UDim2.new(0, 150, 0, 30)
    ThunderToggleUI.Font = Enum.Font.SourceSansSemibold
    ThunderToggleUI.Text = "Copy Discord Link"
    ThunderToggleUI.TextColor3 = Color3.fromRGB(0, 0, 0)
    ThunderToggleUI.TextSize = 19
    ThunderToggleUI.Draggable = true

    TestLabelEN.Name = "TestLabelEN"
    TestLabelEN.Parent = ThunderScreen
    TestLabelEN.BackgroundTransparency = 1
    TestLabelEN.Size = UDim2.new(0, 200, 0, 50)
    TestLabelEN.Position = UDim2.new(0.5, -100, 0.4, -25)
    TestLabelEN.Font = Enum.Font.SourceSansBold
    TestLabelEN.Text = "English: Script Down Join Discord To Get New Scripts"
    TestLabelEN.TextColor3 = Color3.fromRGB(255, 255, 255)
    TestLabelEN.TextSize = 30

    TestLabelVN.Name = "TestLabelVN"
    TestLabelVN.Parent = ThunderScreen
    TestLabelVN.BackgroundTransparency = 1
    TestLabelVN.Size = UDim2.new(0, 200, 0, 50)
    TestLabelVN.Position = UDim2.new(0.5, -100, 0.5, -25)
    TestLabelVN.Font = Enum.Font.SourceSansBold
    TestLabelVN.Text = "Việt: Script Đã Lỗi Thời Vui Lòng Vào Discord Để Nhận Script Mới"
    TestLabelVN.TextColor3 = Color3.fromRGB(255, 255, 255)
    TestLabelVN.TextSize = 30

    ThunderToggleUI.MouseButton1Click:Connect(function()
        setclipboard("https://discord.com/invite/hcJ8PHtkfy")
    end)
end

repeat wait() until game:IsLoaded()
wait()

for _, v in next, getconnections(game:GetService("Players").LocalPlayer.Idled) do
    v:Disable()
end
