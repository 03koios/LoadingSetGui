wait(1)
spawn(function()
    game.StarterGui:SetCore("SendNotification", {
	Title = "Anti Afk System"; 
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
	Text = "Pog Hub No Carte | discord.gg/x4gGhjVxXz | 03.s#6260";
	Font = Enum.Font.Cartoon;
	Color = bc.Color;
	FontSize = Enum.FontSize.Size96;	
})
