Pokemon Showdown Auction Bot Commands 
==
For managers:
.bid <amount> or .<amount> - Bids a specified amount, in thousands (e.g. typing .4.5 bids 4500 on a player)
.nom or .nominate <player> - Nominates a player. Name must match all capitalization and punctuation from imported list.
.withdraw - Leaves a draft once a team no longer once to nominate
 
For host:
.draft init - Begins the configuration for a draft. Must be used before any other draft commands.
.draft addteam <name>, <manager> - Adds a team to the draft. Teams can also be specified automatically in the script itself. Only one manager can be specified using this command, but more can be added later.
.draft load <url> - Loads the players for a draft. The bot is designed to handle raw pastebin or hastebin links only.
.draft start - Begins the bidding process in a draft.
.draft addbidder <team>, <name> - Adds a bidder to a team.
.draft removebidder <team>, <name> - Removes a bidder from a team.
.draft override <options> - Overrides certain aspects of the draft. See below for more info.
.draft skip - Skips a team that is nominating.
.draft end - Ends the drafting session. The session's data will be saved in its file.
 
For all:
.overpay - Declares that you think a player is being overbid on :D
 
Override help:
.draft override players [add/remove] <team> <player> - Add or remove a player from a team manually
.draft override money [add/remove] <team> <amount> - Adds or removes money from a team manually
Override commands should be used only when necessary and are less secure than other commands. Team names should be specified without spaces.
 
The Pokemon Showdown Auction Bot was coded by Nineage and fender for Ecuacion's bot and based on code by sparkychild.
