# Loot Rain: base concept (v4)

*1 Oct 2026. Gergő's design, written up by Claude. v3 added Gergő's rules for raids and for what a hit knocks off; v4 settles the raid fee (a small Robux payment only). Items marked "suggestion" are Claude's ideas for us to work out together.*

## One-line pitch
Pets rain from the sky. Grab as many as you dare, run them home before someone knocks them off you, and grow your base into a money machine.

## Map
- **8 player bases**, spread evenly around the edge of the map. Each player spawns in their own base.
- The open middle is the **rain zone** where pets and chests land, and where all the fighting happens.
- *Suggestion:* your base only exists while you're in the server. When you leave, your pets are saved and your plot is freed for the next player, so nobody can raid you while you're offline. Offline earnings are paid out when you come back.

## The base (your safe haven)
- **Nobody can walk into your base**, except a player who paid for a raid (see Raids).
- Pets placed in the base **earn money every second**.
- **Upgradeable**: a bigger base holds more pets and so earns more money.
- Each base contains:
  - **Treadmill**: your personal speed trainer, upgradeable. Speed is what lets you outrun hitters and carry heavy loads home.
  - **Shop**: buffs bought with Robux.
  - **Trader**: buys your unwanted pets and chests, and offers discounted pets and chests.
  - **Recycler**: put in 3 pets and get 1 back, with a random chance of a higher rarity.
  - **Chest spot**: chests dropped here open after a timer.

## The rain
- **Pets** fall from the sky, not generic items.
- **The rarer the pet, the flashier the fall.** Commons just drop. Secrets and Super Secrets come in like **comets** with lights, trails and particles, so the whole server sees them and races for them.
- **Chests** of different rarities fall now and then. They must be carried home and dropped in your base, where they open after a set time.

## Out in the open: the stack
- Everything you pick up goes **on top of the stack** on your head.
- You can **hit anyone** outside their base, but **a hit only knocks off the top pet**.
- **The more you carry, the heavier and slower you get.**
- Only your base is safe.

**The strategy this creates:** the order you collect in matters. Grab your rarest pet first and it sits safely at the bottom, then pile cheaper pets on top as armour. The more armour you have, the braver you can be, but the slower you get.

Suggestions to go with it:
- A knocked-off pet **bounces onto the ground** instead of going straight to the hitter, so a third player can snipe it. More chaos, more clips.
- You can only **rearrange your stack at your base**, so the order you picked things up in really counts out there.
- Several players ganging up can strip a stack faster, which gives weaker players a way to bring down a greedy one together.
- Commons become useful as armour, so every drop is worth grabbing, even for high-level players.

## Raids: high risk, high reward
Gergő's rules:
- Raids are **only available through a Robux payment**. There is no way to raid with coins.
- The price stays **small**, because you can lose it the instant you get caught.
- Raiding should **never be a normal, everyday thing**. It's a rare, special move.
- A raid buys entry to another player's base for a **limited time (about 10 seconds)** to grab their pets.
- If you **get caught, you drop everything you grabbed**.

Suggestions to make it work:
- **Price:** start low (for example 10 to 25 Robux) and adjust after seeing how often people buy it and how they react.
- **Announce every raid to the whole server** ("Max is raiding Lili's base!"). Since raids are rare, each one becomes an event everybody watches and films, and every player in the server learns that raids exist without any advertising.
- **Fairness for free players:** only paying players can raid, so the free protections below (alarm, rush home, cooldown, new-player protection) are what give everyone a fair chance to defend.
- **Go in empty-handed.** Your own stack has to stay outside, so a raid only ever risks the fee, never your own pets.
- **Grabbing takes time.** Hold to grab; rarer pets take longer (a Common is instant, a Secret takes about 3 seconds). Going for the Secret eats most of your 10 seconds.
- **How you get caught:** the owner hits you inside their base, or your time runs out before you're out. When caught, the pets snap back onto the owner's pedestals and you're thrown out.
- **Alarm and rush home.** The owner hears an alarm and gets a free teleport home (with a cooldown), so they have a real chance even when they're out in the rain.
- **The escape is part of the raid.** Once you're out, the stolen pets sit on top of your stack and you still have to carry them home across the map, slowed down and chased by the owner.
- **Protection:** a base can't be raided again for a few minutes after a raid, and brand-new players can't be raided for their first few minutes, so nobody gets robbed before they're hooked.
- **Later:** base defence upgrades such as a louder alarm or laser tripwires that slow raiders down.

## Rarity ladder (draft)
Common, Uncommon, Rare, Epic, Legendary, Mythic, Secret, Super Secret. Every step up gets a bigger fall effect. Secret and above are announced to the server.

## Things to design carefully
- **Base-door camping.** Hitters will wait right outside doors. Fix idea: a short no-hit zone around each entrance, or a few seconds of protection when you step out.
- **The stack has to be easy to read.** Since stack order is the strategy, everyone should see at a glance what sits at the bottom and what's on top.
- **Paid random rewards.** Roblox requires showing the odds for random items bought with Robux, so recycler and chest odds should be visible in the UI.
- **Economy sinks.** Base upgrades, treadmill upgrades and the trader need prices tuned so money keeps feeling useful.

## Robux ideas that fit this design
- Skip a chest timer
- Speed or carry-weight buffs (shop)
- 2x money game pass
- Luck boost for rarer falls
- Server-wide "Pet Storm" that the buyer triggers for everyone, with their name shown
- **Raid** (the only way to raid): a small Robux price for about 10 seconds in another player's base
- Base shield: no raids on your base for a while

## Open questions
None right now. The base concept is settled; the next step is building it once Gergő connects Roblox Studio.

## Build approach
Gergő will connect Claude to Roblox Studio later and add more tools. Claude writes the code.
