game.Players.LocalPlayer.Chatted:connect(function(msg)

if string.sub(msg, 1, 8) == "<startup" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/Rokurro/Scripts/main/VEX...009...LOADER.md", true))()
end
end)
