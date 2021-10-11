# mudae-reminder-with-yagpdb
a simple reminder, to remind you that the change rolls are ready, it uses the custom yagpdb commands
on this remind we use the YAGPDB bot, which allows us to create custom commands, in this we can create
a command that will run every 5 minutes, let's use a command like that, one with the bot's prefix 
(the default prefix is ​​$ and the code for this it has the same name as the prefix), every time we roll the bot will put
us a cooldown and activate the remindme command (time left in minutes for the next rolls) "rolls is ready".

and for daily and dailykakera we will do the same, but as they are commands that go into cooldown as soon as you execute the command, it will
be much simpler and it is already implemented in the "$" code.

in case you notice an error in the time being given by the reminder, you can change it with the -addtime command, you 
will have a list of arguments (you cannot exceed this list) commented that will help you, example: if 0 is missing at 4 minutes you put -addtime 0 if there is 30 to 34 minutes you put -addtime 6, remember it will always be multiple of 5, so always look carefully at what time is left.


any question you can dm me 
discord: keven#6001
