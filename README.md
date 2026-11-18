# Haji Duo Tournament · Season 2

Interactive tournament hub for a duo **Arena Breakout: Infinite (PC)** tournament.

Live page: https://claude.ai/artifact/6mYakaFo5UUZdsRMEs6XkX

## Sign-ups
Players sign up with just their name at https://ecomforges.com/haji-duo-tournament-s2-register/
(a public Breakdance form, no login). While the organizer has the tournament page open on
claude.ai, it reads new form entries through the ecomforges connector every 30 seconds and
adds them to the Duo draw player pool, skipping duplicate names.

## Duo draw
Duos are random. The organizer puts every player in the pool and spins the wheel live
on the **Duo draw** tab: one spin picks a duo's first player, the next spin picks the
partner. Everyone with the page open sees the same spin at the same time. When the draw
is done, the **Bracket draw** wheel places each duo into the next bracket slot, one live
spin at a time; the finished order becomes the bracket.

## Format
Single elimination, head-to-head. Both duos run one raid; the duo whose two players
extract the higher total loot value (Koen, from the end-of-raid summary) advances.
A player who dies or fails to extract scores 0. Any number of duos works: empty
bracket slots become byes for the top seeds.

## Pages
- **Bracket draw**: second live wheel that seeds the drawn duos into the bracket
- **Duo draw**: live spin wheel, drawn duos, player pool (organizer adds players, spins, undoes, restarts; stream mode for screen sharing)
- **Overview**: countdown to the draw or next raid, live raid, stats, biggest hauls
- **Bracket**: live bracket; organizers click a raid to enter loot, map, time and live status
- **Standings**: every duo ranked by how far they got, then total loot
- **Schedule**: raids by day in the viewer's local time
- **Rules & prizes**, **Hall of fame** (Season 2 champion fills in automatically)
- **Admin** (page owner only): results & schedule, player pool and sign-up sync, duo names and players, seeds, event info, hall of fame

## Files
- `haji-duo-s2.html`: the page (published as a claude.ai artifact; shared data lives in the artifact database)
- `seed/`: placeholder event info and the example bracket the database was first filled with
