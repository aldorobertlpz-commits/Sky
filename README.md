-- SKYBOX SCRIPT
local id = "97316649206788" -- cambia el ID aquí
local sky = Instance.new("Sky")
local url = "rbxassetid://" .. id

sky.SkyboxBk = url
sky.SkyboxDn = url
sky.SkyboxFt = url
sky.SkyboxLf = url
sky.SkyboxRt = url
sky.SkyboxUp = url
sky.Parent = game.Lighting

