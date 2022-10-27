# Flavor

A world of constant war. Even the races fight amongst themselves. However, a prophecy was told long ago that a hero would rise to unite their people and bring an Age of Peace.

Are you the hero the prophecy foretold?

# Objective

At least 75% of the map is under the player's control.

*Control could be conquering land, forcing it to be a vassel state, or diplomatic supremacy.*

# World

## Tier One

World map, broken into hexes. Fog of war. Must explore and gain control over the map.

### Examples

Muster and move armies. Attack opposing armies or settlements. Manage resources. Move hero.

## Tier Two

Roam the battlefield in 3rd person as the general of an army in a pitch battle. Cannot directly fight in battle, but can (de)buff units to influence the outcome.

### Examples

Deploy troop formations to the battlefield. Heal a unit. Poision an enemy unit. Rally fleeing troops. (Passively) Increase troop resistance to fear when you are near.

## Tier Three

Take your hero and a warband of 1-12 onto special missions. The success or failure of the mission influences gameplay on Tier One or Two.

### Examples

Sabotage enemy supply lines. Assassinate a high ranking officer. Bribe a captain of the guard to open the city gates for your sieging army.

## Races

- Human
- Undead
- Dwarf
- Elf

# Game Loop

- The "Risk" style game in Tier One is where things churn. Something like a Turn is comprised of Rounds, and different Rounds have different Phases. idk, spitballin.
- Within each Tier One turn, opportunities will arise for the player to use their hero in Tier Two or Three to benefit their gameplay in Tier One.
    - e.g. Sabotage an enemy army (Tier Three) before you attack with your army (initiated on Tier One and played out in Tier Two)
- All Tiers will have an "auto resolve" function where their Hero takes no action and the AI resolves the Turn/Round/Phase for them.
- When playing with friends, allow players to submit a set of Tier One actions they want to take. After all players have submitted their actions (or the pre-determined timer expires, forcing auto resolve for anyone who has not responded), then the game "plays out" all player actions.
- Certain events will cause PVP conflicts, such as opposing armies occupying the same hex. In that case, a battle will need to be fought in Tier Two to resolve the outcome of the Tier One conflict. Additionaly, a Player may have the opportunity before or after the battle to play a Tier Three round which could influence either the Tier Two or Tier One result of the conflict.
- Any Tier Two or Three PVP conflict can be played out in live-action by both players. Or, one Player could participate live-action while the other "auto resolves" the conflict. Or, both Players could "auto resolve".

## Features

- Each race has access to 8 heroes and you start as one of them.
- After about a 1/3 of the game, you unlock a second hero from the remaining pool of 7 for your race.
- You control them just like your hero, fighting their Tier Two or Three conflicts
- The next 1/3 of the game you unlock 2 more heroes from the remaining pool
- Once 4 heroes are under your control, it unlocks a snowball mechanic
    - Therefore, if there is someone in the clear lead, then end the game faster while making them feel uber powerful
    - Or, if even matched you'll get to 4 heroes around the same time and have an epic slugfest to end things

- If you play with friends 2v2, then each person starts with a hero and is expect to unlock one more each to achieve 4 for the snowball effect.
- If you play something crazy like 4v4, then just start everything at slugfest and make the full game short but action packed
- The idea being, the more people that play the faster you get to snowball which creates fewer Turns that need to happen and therefore shorter games (ideal for big groups)

- At start of game, all players agree on various time contraints that impact the pace of the game.
    - e.g. When a new turn starts, all Players have X hours to submit their actions. Failing to do so will cause the AI to generate a set of actions for you.
    - e.g. When a PVP conflict occurs, each Player is given X hours to schedule a date/time within Y hours/days that the Tier Two or Three live-action conflict will begin.
        - If both Players present at start, then sweet PVP action.
        - If only one Player, then PVE which should give them an advantage
        - If no Players, then both sides "auto resolve"
- A game should be able to churn by itself, without the interaction of any player, and eventually arrive at a Winning state for one of the Players
- If a Tier Two/Three conflict is happening with your hero, you can just "drop-in" at that exact moment of the conflict and begin controling the hero.
    - Let's say you schedule a time for battle to start with friend and they are on time but you show up 1 minute after the battle started. Rather than being locked out, you'll just drop-in at that moment and take control of your Hero away from the AI.