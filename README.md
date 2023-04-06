local key = _G.Key
local check = "https://github.com/garnoog/Key/edit/main/README.md?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://github.com/garnoog/KingOfGod"))()
else
game.Players.LocalPlayer:Kick("Invalid Key! Please Rejoin And Try Again.")
end
