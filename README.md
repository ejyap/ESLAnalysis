# ESLAnalysis

[Original reddit thread](https://www.reddit.com/r/FortniteCompetitive/comments/ayh26a/data_analysis_of_the_esl_katowice_solo_event/)

Hey, guys. You might remember me from this [post](https://www.reddit.com/r/FortniteCompetitive/comments/asa8vy/data_analysis_of_the_secret_skirmish_full/). This time I'm analyzing the results for the ESL Solo event. It was even harder to get the killfeed data for this event as I mainly had to rely on POV streams of players such as Chap, Ryux and Kinstaar. In total, it took me about 12 hours to collect all the data. Again, someone had to do it.

Once again, as a disclaimer, my native language is not english and I'm not a data science guy, but I try to present the data as best as I possibly could. Hopefully, you find it insightful or entertaining.

# Solo Event Results and Comparing Them to Secret Skirmish Results

First, we'll show the full detailed standings of all the players, showing their kills and avg. placement.

[Full Standings](https://imgur.com/a/Tueszkl)

One thing I noticed while creating this list was that my scoring didn't match the points shown in the ESL Website. Indeed, there was a scoring error from their part and I brought enough attention to get it fixed [here](https://www.reddit.com/r/FortniteCompetitive/comments/ax10jq/there_was_a_scoring_error_in_katowice_solo_event/).

Notable underperformers include Saf (65th), Aspect (69th), Chap (74th) and Poach (87th). Highest placing controller player: Kamo (27th). Viallinen was the only player not able to get a single point. 

[Teams sorted by Avg. Placement](https://imgur.com/GaODOT3)

[Countries sorted by Avg. Placement](https://imgur.com/mTn2sZe)

Note: I only count teams and countries with more than 1 player.

LeStream is the top performing team with all of their 4 players in Top 20 and an average placement of 12. USA is the country with most players in Top 20 (5). However, the best performing country in terms of avg. placement is the United Kingdom (23) with their 6 players placing relatively high. 

[Top 10 Avg. Placement](https://imgur.com/o0UEnCa)

As we can see, the format heavily rewards good placement in each match. High average placement is a good indicator of how well you'll do in this format. We visualize this in the following graph, and compare it to the results of the Secret Skirmish.

[Graph](https://imgur.com/mj8ZmBy)

We can see a strong correlation between average placement and rank, while for the Secret Skirmish, it's less linear. The ESL format definitely does a good job in properly rewarding placement. 

[Top 10 Kills](https://imgur.com/a/eRJeNug)

As we can see, emphasis on kills is very reduced in this format. 6 out of the top 10 killers did not make it to Top 20. Not even close. 

RizArt and Viallinen are the only players without a single kill. Vinny1x and Magin are the only players who make it to both of these lists, so their standings are well deserved. Interestingly enough, Magin was #1 in kills and #4 in avg. placement, while Vinny was #1 in Avg. Placement and #4 in kills.

We can take it a step further and see how the top 20 changes under Secret Skirmish rules. See if anything changes.

[ESL Top 20 under Secret Skirmish Format](https://imgur.com/TrbuXJI)

A lot changes. Magin takes it over Vinny, and Julez, Aydan, and Jarkos enter the Top 10 because of their kills. Aydan's aggressive early-game playstyle is completely invalidated by the ESL Format. A lot of people with great avg. placement do worse as expected, because only top 10 counts for points.

So, while the ESL format rewards avg. placement and consistency, the Secret Skirmish format rewards high kills and popping off. In my opinion, I would like to see a format that meets somewhere in the middle. One that equally rewards early-game slayers and late-game survivors in order to promote more variety in playstyle. But, that's just me.

# Winning Playstyles

We can try to infer the playstyles of the top 20 Players by looking at how their kills are distributed across early, mid, and late-game. In the following graph, blue dots represent kills and red dots represent deaths. Each box represents the distribution of kills for each player.

[Graph](https://imgur.com/CXxFkLt)

For reference, I consider early game to end around the 13th minute mark (2nd zone ends) and end game to start around the 17:00 minute mark (5th zone starts). 

Most of the Top 10 players had a lack of early and mid-game kills, focusing only on the end game plaement. For example, all of Vinny1x's 16 kills were towards the end-game. What separates him from the rest of the other players who played the same way was his high number of kills and top 50 placements in all matches.

We can actually see a lack of early-game kills and deaths across the whole Top 20. This emphasizes the importance of landing uncontested or disengaging from early game fights. One early death can mean the difference to make it to Top 20. You really, really have to play for end-game to rack up those placement points.  As we can see, the kills inevitably come as you reach the final zones. Try to think of kills as a measure to get resources and health, not as points. (All of this with storm surge under consideration).

We can still see other types of play styles. Players such as Magin, Hoopek and histtory did go for a lot of mid game fights and they payed off as they were able to win almost all of them. Go for mid-game fights if you're comfortable and certain that you can win, just know that it's risky for your overall placement. 

I know often times players are put into situations where they have no choice but to fight early. It's unfortunate as this is mainly due to a lack of mobility, getting contested, far away zones or psychopaths, things that are not always under a player's control.

It's also important to note that not a single Top 20 player got there because they "popped off" just one game. All of them have 3 or more great late-game finishes.

# Weapon Distribution

I was not able to get the cause of deaths for 35 deaths. It simply wasn't possible. The deaths I did record should still provide an accurate representation of the weapon distribution. 

[Weapon Distribution](https://imgur.com/iGAgkY1)

### Fun Facts

- Ghost Dmo got the only cannon kill, and it was on Ghost Kamo.
- Liquid Chap with the only Pickaxe kill on MarkiLokuras. This was off spawn.
- 72hrs died 4 times to storm.
- A total of 9 players had game crashes that didn't allow them to play a game. Nate's game crash was the only one that occurred mid-game (Funkbomb accidentally kicked Nate's power switch).
- Biggest rivalry of the tournament was Myth vs Noward. Noward was able to kill Myth 3 times off-spawn, while Myth only once.
- Farthest kill was a 226m snipe from Ryux to Bloodx.
- Ghost Issa was the most aggressive early-game player with 6 kills before Zone 2.
-  Secret_Milan is probably the unluckiest player getting 51st, 51st, 53rd, and 60th in 4 matches, just outside placement points.

# Match Pacing

Next, I created a graph visualizing the amount of players alive as each match progressed.

[Graph](https://imgur.com/oLXVzj1)

Deadliest zone was Zone #1 with 130 deaths. No surprise there. Not far behind, the second deadliest zone was Zone #6 (lasts 90 seconds) with 122 deaths.

I was actually more interested in how the pacing of ESL matches compared to the pacing of the Secret Skirmish games. I graphed the first 3 games of both tournaments.

[Graph](https://imgur.com/ze85i8T) 

Not enough of a difference to reach any conclusion, despite ESL's emphasis on placement. Perhaps, the Storm Surge does work in applying an upper bound of players alive each zone, leading to a very predictable quantity of players each zone.

edit: [Death Count for each Zone](https://imgur.com/vA8OrRS)

# The End

Anyway, that's all the ideas I had. Hopefully I can do analysis of Duos. Depends if I can get the killfeed data for all the matches, which will be even harder. I accept any type of help! But anyway, let me know if there's anything else you'd like to see or if there's anything I got wrong.

EDIT: [ESL Top 20 under Gauntlent Solo Format](https://imgur.com/PlPq8V6)
