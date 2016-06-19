<h2>HOST, CO HOST, MENAGER</h2>
   <table class="cmd-menager" id="table">
			<thead>
				<tr>
					<th>Command</th>
					<th>Argument</th>
					<th>Description</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>!swap</td>
					<td>[@user1] [@user2]</td>
					<td>Swap the users on wait list</td>
				</tr>
				<tr>
					<td>!dance</td>
					<td>null</td>
					<td>Automatically vote every song</td>
				</tr>
				<tr>
					<td>!meh</td>
					<td>null</td>
					<td>Bot will meh current song</td>
				</tr>
				<tr>
					<td>!afklimit</td>
					<td>[time]]</td>
					<td>Sets the maximum afk time</td>
				</tr>
					<td>!refresh</td>
					<td>null</td>
					<td>Refreshes the browser of whoever runs the bot</td>
				</tr>
				<tr>
					<td>!skippos</td>
					<td>[position]</td>
					<td>Set the position to which skip and lockskip moves the dj</td>
				</tr>
				<tr>
					<td>!clearchat</td>
					<td>null</td>
					<td>Clears the chat</td>
				</tr>
				<tr>
					<td>!cycle</td>
					<td>null</td>
					<td>Toggle DJ cycle</td>
				</tr>
				<tr>
					<td>!cycletimer</td>
					<td>[time]</td>
					<td>Set the maximum DJ cycle time for when cycleguard is enabled</td>
				</tr>
				<tr>
					<td>!locktimer</td>
					<td>[time]</td>
					<td>Set the maximum time the waitlist can be locked if lockguard is enabled</td>
				</tr>
				<tr>
					<td>!maxlength</td>
					<td>[time]</td>
					<td>Specify the maximum length a song can be when timeguard is enabled</td>
				</tr>
				<tr>
					<td>!logout</td>
					<td>null</td>
					<td>Logs out account bot is hosted on</td>
				</tr>
				<tr>
					<td>!refresh</td>
					<td>null</td>
					<td>Refreshes the browser of whoever runs the bot</td>
				</tr>
				<tr>
					<td>!usercmdcd</td>
					<td>[time]</td>
					<td>Set the cooldown on commands by grey users</td>
				</tr>
				<tr>
					<td>!usercommands</td>
					<td>null</td>
					<td>Toggle user commands</td>
				</tr>
				<tr>
					<td>!voteskip</td>
					<td>null or [time]</td>
					<td>When no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit.</td>
				</tr>
				<tr>
					<td>!mehautoban</td>
					<td>[number of songs]</td>
					<td>Toggle auto ban after specified number of songs , if none is specified default is 5</td>
				</tr>
			</tbody>
		</table>
		<h2>BOUNCER</h2>
		<table class="cmd-bouncer">
			<thead>
				<tr>
					<th>Command</th>
					<th>Argument</th>
					<th>Description</th>
				</tr>
			</thead>
			<tbody>
	             <tr>
					<td>!add</td>
					<td>[@user]</td>
					<td>aAdd user to the waitlist</td>
				</tr>
				<tr>
					<td>!afkremoval</td>
					<td>null</td>
					<td>Toggles the afk check</td>
				</tr>
				<tr>
					<td>!autoskip</td>
					<td>null</td>
					<td>Skips songs automatically when they're done (use when the circles-bug happens)</td>
				</tr>
				<tr>
					<td>!deletechat</td>
					<td>[@user]</td>
					<td>Delete all the chats by a certain user</td>
				</tr>
				<tr>
					<td>!lock</td>
					<td>null</td>
					<td>Lock the waitlist</td>
				</tr>
				<tr>
					<td>!lockdown</td>
					<td>null</td>
					<td>Lock down the room: only staff can chat</td>
				</tr>
				<tr>
					<td>!move</td>
					<td>[@user] [position]</td>
					<td>Moves user to position X on the waitlist</td>
				</tr>
				<tr>
					<td>!remove</td>
					<td>[@user]</td>
					<td>Remove user from the waitlist</td>
				</tr>
					<tr>
					<td>!roulette</td>
					<td>null</td>
					<td>Start a roulette</td>
				</tr>
				<tr>
					<td>!songstats</td>
					<td>null</td>
					<td>Toggle song statistics (Default off)</td>
				</tr>
				<tr>
					<td>!unlock</td>
					<td>null</td>
					<td>Unlock the waitlist</td>
				</tr>
				<tr>
					<td>!welcome</td>
					<td>null</td>
					<td>Toggle the welcome message on user join</td>
				</tr>
				<tr>
					<td>!active</td>
					<td>[time]</td>
					<td>Shows how many users chatted in the past X minutes. If no X specified, 60 is set as default</td>
				</tr>
				<tr>
					<td>!afkreset</td>
					<td>[@user]</td>
					<td>Resets the afk time of user</td>
				</tr>
				<tr>
					<td>!afktime</td>
					<td>[@user]</td>
					<td>Shows how long user has been afk</td>
				</tr>
					<tr>
					<td>!ban</td>
					<td>[@user]</td>
					<td>Bans user for 1 day</td>
				</tr>
				<tr>
					<td>!blacklist / !bl</td>
					<td>[name]</td>
					<td>Add the song to the specified blacklist (after reloading bot song is removed)</td>
				</tr>
				<tr>
					<td>!commanddeletion</td>
					<td>null</td>
					<td>Toggles if bot commands gets deleted</td>
				</tr>
				<tr>
					<td>!blinfo</td>
					<td>null</td>
					<td>Get information required to blacklist a song</td>
				</tr>
				<tr>
					<td>!cycleguard</td>
					<td>null</td>
					<td>Toggles the cycleguard</td>
				</tr>
				<tr>
					<td>!dclookup</td>
					<td>[@user]</td>
					<td>Do dclookup for user</td>
				</tr>
				<tr>
					<td>!eta</td>
					<td>[@user] or null</td>
					<td>Shows when user will reach the booth</td>
				</tr>
					<tr>
					<td>!filter</td>
					<td>null</td>
					<td>Toggles the chat filter</td>
				</tr>
				<tr>
					<td>!forceskip</td>
					<td>null</td>
					<td>Forceskips the current song</td>
				</tr>
				<tr>
					<td>!historyskip</td>
					<td>null</td>
					<td>Toggles the history skip</td>
				</tr>
				<tr>
					<td>!jointime</td>
					<td>[@user]</td>
					<td>Shows how long the user has been in the room</td>
				</tr>
				<tr>
					<td>!kick</td>
					<td>[time]</td>
					<td>Kicks user for X minutes, default is 0.25 minutes (15 seconds)</td>
				</tr>
				<tr>
					<td>!stop​</td>
					<td>null</td>
					<td>Turn off the bot​</td>
				</tr>
				<tr>
					<td>!lockskip</td>
					<td>[reason]</td>
					<td>Skips, locks and moves the dj back up (the position can be set with !skippos)</td>
				</tr>
					<tr>
					<td>!motd</td>
					<td>[message] or [time] or null</td>
					<td>When no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message</td>
				</tr>
				<tr>
					<td>!mute</td>
					<td>[@user] [time] or null</td>
					<td>Mute user, for X minutes if X is specified, otherwise for an undefined period</td>
				</tr>
				<tr>
					<td>!reload</td>
					<td>null</td>
					<td>Reload bot in case there are some problems</td>
				<tr>
				<tr>
					<td>!restricteta</td>
					<td>null</td>
					<td>Toggles the restriction on eta: grey users can use it once an hour</td>
				</tr>
				<tr>
					<td>!sessionstats</td>
					<td>null</td>
					<td>Display stats for the current session</td>
				</tr>
				<tr>
					<td>!skip</td>
					<td>[reason]</td>
					<td>Skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos)</td>
				</tr>
				<tr>
					<td>!status</td>
					<td>null</td>
					<td>Display the bot's status and some settings</td>
				</tr>
				<tr>
					<td>!timeguard</td>
					<td>null</td>
					<td>Toggle the timeguard</td>
				</tr>
				<tr>
					<td>!togglebl</td>
					<td>null</td>
					<td>Toggle the blacklist</td>
				</tr>
				<tr>
					<td>!togglemotd</td>
					<td>null</td>
					<td>Toggle the motd</td>
				</tr>
				<tr>
					<td>!togglevoteskip</td>
					<td>null</td>
					<td>Toggle the voteskip</td>
				</tr>
				<tr>
					<td>!unban</td>
					<td>[@user]</td>
					<td>Unban user</td>
				</tr>
				<tr>
					<td>!unmute</td>
					<td>null</td>
					<td>Unmute user</td>
				</tr>
				<tr>
					<td>!voteratio</td>
					<td>[@user]</td>
					<td>Display the vote statistic for a user</td>
				</tr>
				<tr>
					<td>!whois</td>
					<td>[@user]</td>
					<td>Returns plug related information about user</td>
				</tr>
				<tr>
					<td>!prc</td>
					<td>[@user]</td>
					<td>Give it a try</td>
				</tr>
				<tr>
					<td>!slow</td>
					<td>(X)</td>
					<td>Turn on Slow mode in room </td>
				</tr>
			</tbody>
		</table>
		<h2>RESIDENTDJ</h2>
		<table class="cmd-rdj">
			<thead>
				<tr>
					<th>Command</th>
					<th>Argument</th>
					<th>Description</th>
				</tr>
			</thead>
			<tbody>
	             <tr>
					<td>!link</td>
					<td>null</td>
					<td>Give a link to the current song</td>
				</tr>
				<tr>
					<td>!download</td>
					<td>null</td>
					<td>Get a link to download current song</td>
				</tr>
				<tr>
					<td>!vdownload</td>
					<td>null</td>
					<td>Get a link to download video now playing</td>
				</tr>
				<tr>
					<td>!mediaid</td>
					<td>null</td>
					<td>Get ID of now playing song</td>
				</tr>
			</tbody>
		</table>
        <h2>USERS</h2>
        <table class="cmd-user">
      <thead>
        <tr>
          <th>Command</th>
          <th>Argument</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>!dc</td>
          <td>null</td>
          <td>Use it if you got disconnected to get back on your place in WL</td>
        </tr>
        <tr>
          <td>!8ball</td>
          <td>[question]</td>
          <td>Ask the bot a question, the bot will return random variations of a yes or no answer</td>
        </tr>
        <tr>
          <td>!autowoot</td>
          <td>null</td>
          <td>Link for autowoot scripts</td>
        </tr>
        <tr>
          <td>!ba</td>
          <td>null</td>
          <td>Explains the Brand Ambassador rank</td>
        </tr>
        <tr>
          <td>!commands</td>
          <td>null</td>
          <td>Gives a link to the commands page</td>
        </tr>
        <tr>
          <td>!cookie</td>
          <td>[@user]</td>
          <td>Give a cookie to user</td>
        </tr>
        <tr>
          <td>!emoji</td>
          <td>null</td>
          <td>A link to a list with emoji's</td>
        </tr>
        <tr>
          <td>!eta</td>
          <td>null</td>
          <td>Shows how long before you reach the booth</td>
        </tr>
        <tr>
          <td>!fb</td>
          <td>null</td>
          <td>Links to the room's Facebook group</td>
        </tr>
        <tr>
          <td>!ghostbuster</td>
          <td>[@user]</td>
          <td>Checks if user is ghosting</td>
        </tr>
        <tr>
          <td>!gif</td>
          <td>[tag]</td>
          <td>Returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided.</td>
        </tr>
        <tr>
          <td>!help</td>
          <td>null</td>
          <td>link for some info if are new user</td>
        </tr>
        <tr>
          <td>!join</td>
          <td>null</td>
          <td>Join the roulette if it's up</td>
        </tr>
        <tr>
          <td>!leave</td>
          <td>null</td>
          <td>Leave the roulette if you joined</td>
        </tr>
        <tr>
          <td>!link</td>
          <td>null</td>
          <td>When the user is the DJ, give a link to the current song</td>
        </tr>
        <tr>
          <td>!op</td>
          <td>null</td>
          <td>Links to the OverPlayed list</td>
        </tr>
        <tr>
          <td>!ping</td>
          <td>null</td>
          <td>Pong</td>
        </tr>
        <tr>
          <td>!rules</td>
          <td>null</td>
          <td>Links to the rules</td>
        </tr>
        <tr>
          <td>!subscribe</td>
          <td>null</td>
          <td>Get a link to subscribe on plug.dj</td>
        </tr>
        <tr>
          <td>!thor</td>
          <td>null</td>
          <td>Users get moved to position 1 in the waitlist if they're worthy of Thor's hammer. If not they are moved to last place on WL</td>
        </tr>
        <tr>
          <td>!website</td>
          <td>null</td>
          <td>Links to the room's website</td>
        </tr>
        <tr>
          <td>!youtube</td>
          <td>null</td>
          <td>Links to the room's youtube page</td>
        </tr>
        <tr>
          <td>!ask</td>
          <td>null</td>
          <td>Link to our ask.fm profile</td>
        </tr>
        <tr>
          <td>!stumblr</td>
          <td>null</td>
          <td>Link to Selma tumblr</td>
        </tr>
        <tr>
          <td>!roomhelp</td>
          <td>null</td>
          <td>Help for new users in room</td>
        </tr>
        <tr>
          <td>!rouletteinfo</td>
          <td>null</td>
          <td>Get some info about roulette and how it works</td>
        </tr>
        <tr>
          <td>!gift</td>
          <td>[@user]</td>
          <td>Gift someone something (Random)</td>
        </tr>
        <tr>
          <td>!fortunecookie</td>
          <td>null</td>
          <td>Check your fortune cookie</td>
        </tr>
        <tr>
          <td>!truth</td>
          <td>null</td>
          <td>Play truth game with bot, be honest when you answering</td>
        </tr>
        <tr>
          <td>!source</td>
          <td>null</td>
          <td>Who are bot editors</td>
        </tr>
      </tbody>
    </table>