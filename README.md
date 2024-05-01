


local library = loadstring(game:HttpGet('https://raw.githubusercontent.com/cueshut/saves/main/criminality%20paste%20ui%20library'))()

-- // Window \\ --
local window = library.new('WITHWISHX                                                           SUBSCRIBE ME ON YOUTUBE!', 'Professor')

-- // Tabs \\ --
local tab = window.new_tab('rbxassetid://4483345998')

-- // Sections \\ --
local section = tab.new_section('Apocalypse Tycoon🧟‍♂️')

-- // Sector \\ --
local sector = section.new_sector('ENJOY!', 'Left')

-- // Elements \\ -- (Type, Name, State, Callback)
local button = sector.element('Button', 'INF ON', nil, function()
    _G.F = true
    while _G.F do wait()
        game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("Robbery"):FireServer()
    end
end)

local button = sector.element('Button', 'INF OFF', nil, function()
    _G.F = false
end)
