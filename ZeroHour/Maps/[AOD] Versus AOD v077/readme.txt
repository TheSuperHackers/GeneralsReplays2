Hello and welcome to...
Versus AOD

Created by kABUSE aka I^Love^Mixery 24/07/2023

### HOW TO HOST ###
Host with 1-4 human players, all faction vGLA, all in Slots 1-4.
Host with 1 vGLA Computer enemy in Lobby Slot 5.
Observers only work in lobby slots 6, 7 and 8.
Map works online, no game restart after transfer required, but recommended to correctly display briefings and counter names for everybody.
Ini file is only there to remove USA Patriot lag, no mismatch.

### DAFUQ IS THIS ###
- Gamemode: Free for all (up to 1vs1vs1vs1). You have to stop units from other human players and attack other human players with your own waves. Attack waves can be created in the middle. Wave units are owned by CPU player, thus cannot be controlled by buyer.
- Bases are attacked counter-clockwise. So top left spawns units for bottom left etc. Empty bases are skipped by the spawns. When you play alone (or when you are the only player left alive) you can test your own defenses against your own spawns.
- Send units to increase your income. Every unit increases your income by roughly 10% of its price. Unlocks and def do NOT increase your income. Income is added to your cash every 30 seconds.
- Select worker in middle and press "S" (or move-order) to send units. Pro tip: You can do both things at the same time to spam super fast. You may also select multiple workers at the same time.
- Game starts after 60 seconds or after every player has less than $1.000 left. You have 10 lives.
- Players are not ejected from the game after they have lost. This is done intentionally so that they can still use chat-features while waiting for the next round to start.

It would have been quite simple to add a feature to "reset" the map so you can restart without going back to lobby, but I have decided against it for stability reasons and so that the "stats" screen results make sense. Also it is kinda lame to always play with the same player-order. So consider switching up the slots, or you might get bored.

### SCRIPTING HIGHLIGHTS ###
- Binary Adder: Worldbuilder normally doesn't allow you to increase player cash by counter value, only by fixed value. This was circumvented using a so called binary adder. Check out the "Cash_Increaser" script folders to see how it works.
- Automation: I used a Macro recorder, notepad++ and several keyboard and mouse macros / hotkeys to bulk-copy / update scripts and teams.
- Teams replication: In this map I found out that teams can despawn themselves, then spawn a new interation of themselves at a different position. Check it out in the "Respawn_Subs" script folders to see how it works.

### Have fun playing! ###
Feel free to reach out. I will also gladly accept paypal donations: [email redacted]

Discord tag: k.abuse