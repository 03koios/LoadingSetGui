wait(1)
game.StarterGui:SetCore("SendNotification", {
Title = "Loaded Scripts"; 
Text = "Loaded";
Duration = 1; 
})

wait(1)
spawn(function()
    game.StarterGui:SetCore("SendNotification", {
	Title = "Anti Afk Always On"; 
	Text = "Anti Afk Always On";
	Icon = ""; 
	Duration = 1; 
})
end) 

for i,v in pairs(getconnections(game.Players.LocalPlayer.Idled)) do
v:Disable()
end

wait(2)
bc = BrickColor.new("White")
game.StarterGui:SetCore("ChatMakeSystemMessage", {
	Text = "Pog Hub No Carte | discord.gg/x4gGhjVxXz";
	Font = Enum.Font.Cartoon;
	Color = bc.Color;
	FontSize = Enum.FontSize.Size96;	
})

wait(5)
game.StarterGui:SetCore("SendNotification", {
Title = "Key System"; 
Text = "Key System Credits To Adminus#1220";
Duration = 1; 
})
