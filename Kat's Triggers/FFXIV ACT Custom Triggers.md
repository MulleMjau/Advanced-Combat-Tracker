#  FFXIV ACT Custom Triggers
Here are some triggers (in shareable XML format) that I've found useful at one point or another.
To add them to [ACT](http://advancedcombattracker.com/home.php), copy the entire XML line and click "Import XML" from inside ACT.
[Here's](https://github.com/Makar8000/ACT-Discord-Triggers/wiki/First-Time-Setup-Guide) a plugin for ACT that will let ACT call in to a Discord voice channel.

##  Quality of Life
I ___always___ have these running, as without them I'm pretty much guaranteed to miss the odd pull, or miss food falling off!

	<Trigger R="has initiated a ready check" SD="Ready check" ST="3" CR="F" C="General" T="F" TN="" Ta="F" />
	<Trigger R="Battle commencing in (?&lt;length&gt;\d+) seconds! \(" SD="Pulling in ${length}" ST="3" CR="F" C="General" T="F" TN="" Ta="F" />	
	<Trigger R="Countdown canceled by " SD="Scratch That, Hold Up" ST="3" CR="F" C="General" T="F" TN="" Ta="F" />	
	<Trigger R="You lose the effect of Well Fed." SD="Food down" ST="3" CR="F" C="General" T="F" TN="" Ta="F" />

##  Others
###  [Raids](https://github.com/MulleMjau/Advanced-Combat-Tracker/blob/master/Kat's%20Triggers/Raids.md)
###  [Trials](https://github.com/MulleMjau/Advanced-Combat-Tracker/blob/master/Kat's%20Triggers/Trials.md)
###  [Others](https://github.com/MulleMjau/Advanced-Combat-Tracker/blob/master/Kat's%20Triggers/Others.md)
