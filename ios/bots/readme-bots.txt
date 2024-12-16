IOS Bots - Nov 2003 - Routetwo.

To add a bot you need to display the Half-Life console.

To add some bots to the game and let the bots choose team and position, enter the command:

iosbot add


You can specify which team you would like the bots to join using:

iosbot add team1
iosbot add team2


You can specify a position on the field using the command

iosbot add 2-11

where 2-11 correspond to the 'shirt number' position. .e.g. iosbot add 7

You can combine these commands:

iosbot  add  team1   7
iosbot  add  team2   9


You can also name the individual bot by adding a name to any of the above commands:

iosbot add beckham
iosbot add team1 beckham
iosbot add team1 7 beckham


NOTES: 

1. Because the bots "play their position" if you add only a few bots (say all in defense) then they WILL NOT run up field and attack.
I have found the best thing to do is to manually add some "Forwards" (9 and 10) and a bunch of defenders (2,3,4,5). Then the bots
will be able to cover most of the pitch, but there will still be areas where you will have to help them out.

2. Bots will NOT be picked for Throwins, Corners, FreeKicks, Penalties etc, so the game will choose YOU if it's for your team.
If there is no human player on the other team these will be ignored and you will have to play on (even if the ball went out).
Because of this IOS_Indoor is quite a good map for playing against bots :)

3. Because IOS doesn't award goals to bot keepers and players, often if a bot scores it will give the goal to the human player.
If a bot on the other team scores it may award you with an OWN GOAL.
I'm not changing this because it intereferes with "normal IOS" too much.

4. As mentioned above you can give the bots a name, if you don't it randomly picks one from 'names.txt'. I have put in some premiership players
but you can edit it to anything you want.

5. The bots were developed using Bot Man's BotSDK which was integrated into the IOS code by Rich. So big thanks to Bot Man and Rich.





