# Saffron Drift: backlog (named Glasswind until 0.7.1)

Updated 2026-11-18. BC decides the order. Plan: `PLAN.md`. Brief: `BRIEF.md`.

## Done

- v0.8.1 (2026-11-19): the Tester tools gate was missing from the 0.7.3 and 0.8.0 builds (make_debug_gate.py not run). Fixed. Run it before every export.

- v0.8.0 (2026-11-19): The Drift. Tavi, five keepers at the basin's landmarks (BC: reuse landmarks): Mira the Step at the Leaning Tower, Rana the Sun at the Nomad Camp market, Kip the Spiral at the wind vanes, Pell the Water at the Oasis, Sef the Star at the Buried Ship. Grandmother's carpet starts faded and wakes per piece, woven marks on the carpet, Elder Suna's send-off and the middle-piece ending. Tokens and sigil forging retired (old sigil gifts kept). New `tests/drift_check.gd`.

- v0.7.3 (2026-11-19): fixes from BC's playtest sweep, on Godot 4.7.2 (G6.19, the first existing game moved). Climbing follows each wall's real box shape (tower, hull, statue, pillar), hangs 0.3 m off the face, pulls up onto ledges and the roof. The tower's roof and ledges follow its lean. The deck slopes with the hull. Boost: a kick, a whoosh, rumble, faster speed-up, a wider view and a bigger two-corner trail. The riding camera eases round behind the carpet at up to 1.0 rad/s. New tests: `tests/climb_check.gd`, `tests/ride_check.gd`.

- v0.7.2 (2026-11-18): start screen title (G5.21 Title, asked for by BC). The name sits in the dead center, above the buttons, in Aref Ruqaa (SIL Open Font License 1.1), on the start screen, the game page and the Game Shelf card. Kit 1.15.0.

- 2026-11-18: 0.7.1 New name. Glasswind is now Saffron Drift (BC's pick) to fit the magic carpet and the Drift story. The start screen, the page, the APK name and the Game Shelf card all say Saffron Drift. The page moved to https://bclark10121-cloud.github.io/saffron-drift/ . Saves, settings and the Android install carry over: the save names and the app id keep the old name on purpose.

- 2026-11-18: 0.7.0 The magic carpet. The hover bike is now a flying carpet of our own design: a woven terracotta rug with a sand border, dark brown zigzags and tassels, rippling faster as it speeds up. The rider stands on it surf style and leans into turns. Kip's upgrades, Rana's dyes, the three pieces at Home Camp, every line and the start screen now say carpet. Fixed: the black dot at the start of the boost trail (the particle node drew it). The trail is now a hand-made puff trail.

- 2026-11-18: 0.6.1 Coins and looks. Fixed: Boost, Jump, Bike and Act did nothing on a phone while a thumb held the stick (only the first finger acts as a mouse), so there was no boost smoke. The four buttons now read every finger. 95 gold coins in 12 trails (Home Camp road, the Old Road, up the Dry Falls ramp, round the Oasis and a statue, the ship's deck, an air arc off the Leaning Tower). Rana at the Nomad Camp sells 4 bike paints and 3 boost smoke colors. Smoke moved clear of the tail.

- 2026-11-18: 0.6.0 Smaller world, more to do. The basin is 55 percent the size (about 800 m across): every place is closer and old saves move with it. Eight small ruins (broken walls, sunken statues, wind vanes, tall pillars, an empty camp), each with a scrap cache on top. 34 loose scrap pieces. Kip the tinker at Home Camp with four upgrades of three levels (engine, boost tank, hover springs, gliding stone). Requests also give 3 scrap. A scrap counter in the HUD (BC: smaller world, more to do, collect and upgrade).

- 2026-11-18: 0.5.1. Fixed: the Menu stayed on top of Settings. Every Menu row (Settings, How to play, Map, Journal, Records) now opens in place of the Menu, and Back brings the Menu back. The starter base got the same fix and the bus layout file, so new games start with both.

- 2026-11-18: 0.5.0 Sound and fires. Fixed: no music or sound in the browser (the sound buses now come from a bus layout file). Fixed: jumping while running, with a short grace after leaving the ground and a jump pressed just before landing. Boost smoke behind the bike (BC's test). The Old Fires request from Ilo, star stones that make climbing last longer, the journey postcard in the Journal and rumble on landings, summits, fires and stones (backlog 23, 25, 30, 35).

- 2026-11-18: 0.4.0 Easier climbs. Climbs start on purpose (push a moment or jump at the wall), holding still on a wall is free, a jump at a wall grabs it higher, the camera pulls back on climbs and frames both people in a talk, a Camera behind you button, the Journal of open requests and four updrafts that lift the glide (backlog 9, 10, 11, 12, 15, 19).

- 2026-11-18: 0.3.0 The journey. Four more requests (Pell at the Oasis, Sef at the Buried Ship, the Old Road arches, the flute, the mast), the Scout's and Courier's sigils with a small ability each, the ending choice with Elder Suna, six star stones, the Map with travel, the title track (Ancient Winds, BC's pick), wind, bike hum, footsteps and the glide sound, a low-poly hover bike in code, a softer sand light and the Game Shelf card.

- 2026-11-18: 0.2.0 Climb and glide. Climbing steep ground, the Leaning Tower (two ledges) and the Buried Ship with a gentle stamina limit, sliding down when tired, a No climbing limit assist, the glide bubble, the bike-parts tutorial at Home Camp, Elder Suna, the Nomad Camp (Taro, Mira, Ilo, Noor) and the first two requests with Courier and Scout tokens.

- 2026-11-18: 0.1.1. The real rider from Gemini and Meshy replaces the box figure, with idle, walk, run, jump and a seated ride pose.

- 2026-11-18: 0.1.0 Gray box shipped. The basin (1.5 km floor, 1.7 km with the rim), Home Camp, the Leaning Tower, the Buried Ship, the Dry Falls with a ramp up the south side, the Oasis and the Nomad Camp as gray boxes. The hover bike, walking, calling the bike from anywhere, jumps, boost, the chase and over-the-shoulder camera, touch controls, Auto accelerate, the day one pieces and ten achievements.

## Now

- Playtest sweep results (BC, 2026-11-19, 8:59 PM):
  - Good: frame rate on his phone, the upright view and touch buttons.
  - Fixed in v0.7.3: carpet feel (steering, speed, jump, boost smoke), climbing and gliding (stamina, sliding when tired, glide bubble), camera (pull back on climbs, Camera behind you).
  - 0.8.0 picks: rider name Tavi. Elder Suna stays as the caravan elder who sends you off and welcomes you home. Keepers: move current people (BC, 9:05 PM). Mira keeps Red Steps, Rana Glass Flats Market, Kip Spiral Ridge, Pell Dry Lake Wells, Sef Star Arch. Taro, Ilo and Noor stay in camp.
  - Needs work details (BC, 9:05 PM): boost feels weak or its smoke is hard to see. Climbing a wall puts the rider through the wall. The camera swings too much in turns.
- BC tests now: 0.8.0 The Drift (and 0.7.3's climbing, boost and turn camera).
- The rider is in the game (0.1.1). Still to come: the Meshy bike, and the climb motion in 0.2. A young nomad, about 16, coral and teal wrap, long gold scarf, goggles (BC, 2026-11-18). Name still open.

## Next (BC picks after his test)

- Done in v0.8.0: The Drift (see Done). Still open from its outline: tassel charms as the hidden keepsakes, a dusk homecoming once day and night exist, the site names (Red Steps and the rest) if BC wants them.
- Was: 0.8.0 The Drift (BC, 2026-11-18): the new story. Every nomad of the Hearth Caravan takes the Drift at 16, a solo journey on the family carpet across the Ochre Basin. You go home once your carpet carries a pattern of your own.
  - The carpet: grandmother's old carpet, faded to sand color. It wakes a little more with each pattern piece. Rests on sunlit stones (fits the star stones and stone stamina).
  - Five sites and keepers, one motif each: Red Steps (old climber, Step motif, climbing), Glass Flats Market (the dyer, Sun motif, coin shop: fits Rana), Spiral Ridge (the tinker, Spiral motif, scrap upgrades: fits Kip), Dry Lake Wells (oasis caretaker, Water motif: fits Pell at the Oasis), Star Arch (stargazer at night, Star motif).
  - Pattern pieces replace the Scout and Courier sigils as the story thread. Tassel charms on the carpet fringe become the hidden keepsakes.
  - Ending: fly back to the caravan at dusk, arrange the pattern pieces into your own design, and it becomes the carpet's final look. Replaces the ending choice with Elder Suna. Free roam after.
  - Open for BC: the rider's name (ideas Sami, Ren, Esa, Tavi, Kesh. Noor is taken by a Nomad Camp NPC), which current people become keepers, and whether Elder Suna stays as the caravan elder.

- BC's feel check on 0.7.0: bike, climbing, gliding, camera, frame rate.
- A Meshy cross-legged sit or a crouch-on-boost motion for the carpet rider (G8.5), if the standing pose needs more.
- Meshy people for Elder Suna and the nomads.
- Real landmark shapes for the tower, the ship and the falls (the art pass, G8.6 reference first).
- Day and night (PLAN.md section 6).
- The full name check before a wider release (G4.8).

## Ideas to choose from (BC picks by number)

1. Photo mode, copied from Keeper of the Hollow.
2. A bike garage: paint, parts and a horn, earned from requests.
3. Races against your own ghost on time-trial routes, personal bests only (G4.4).
4. Sand surfing: ride the bike down a big dune for speed and air.
5. Weather: a sandstorm you can shelter from, then clear skies with a long view.
6. A second region after BC says the riding feels right: salt flats or a canyon.
7. Night sky reading: constellations that point to hidden places.
8. A camp you set up anywhere, to save and rest by a fire.

## From the Sable review (2026-11-18): QoL and gameplay ideas (BC picks by number)

Sources: reviews of Sable, A Short Hike, Tchia and Lil Gator Game. Size: S small, M medium, L large. Starred items are the suggested first picks.

### Quality of life

9. * Climb only on purpose: a climb starts after you push into a wall for a moment or jump at it, so a brush against a rock never spends stamina. S Done in 0.4.0.
10. * Hang still for free: holding still on a wall costs no stamina, so you can look around and plan a route. S Done in 0.4.0.
11. Jump-start a climb: jumping at a wall gives a free couple of meters before stamina drains. S Done in 0.4.0.
12. * Camera care: the camera pulls back and up while climbing, frames both people during a talk and has a recenter button (right stick click). M Done in 0.4.0.
13. Stamina ring by the rider instead of the bar at the bottom of the screen. S
14. Map pins and a compass strip: drop a pin on any spot you look at, and see pins and found places along the top of the screen. Off by default. M
15. * Request journal in the Menu: each open request, who asked and where to go. S Done in 0.4.0.
16. The bike rides over to you when called (when it is in view) instead of appearing beside you. M
17. Glide by choice: a Settings switch so the bubble opens on a press instead of on its own. S
18. Lookouts fill the Map: reaching the top of the tower or the mast marks nearby places, like Sable's cartographers. M

### Movement and fun

19. * Updrafts: warm air over the Dry Falls and big dunes lifts the glide bubble, so a long glide can climb again. M Done in 0.4.0.
20. Bike tricks in the air: a spin or a flip off a crest, with a little boost as the reward. M
21. Sand surfing on foot: slide down steep sand on your cloak. Pairs with idea 4 for the bike. M
22. A flop button: tumble down a dune for fun. No damage. S
23. Star stones grow stamina: every two stones make climbing last longer, so finds matter (A Short Hike's feathers, Sable's chum eggs). S Done in 0.5.0.
24. Rock-top perch: the climber stands neatly on top of a thin rock or post when they reach it. S

### Things to do

25. * Fewer fetch requests: small climbing puzzles, such as lighting three braziers on the falls or turning old wind vanes to wake a machine. M Done in 0.5.0.
26. More life in the basin: beetles and lizards on the sand, birds that lift off as you ride by and a trader who wanders between camps. M
27. Something every 200 meters: small ruins, a lone campfire, a half-buried statue, a lookout post. M
28. Hidden caves under the dunes, each with one relic. L
29. More callings: Machinist (fix the beacon's gears) and Cartographer (map the rim), each with three requests and a sigil. L
30. A journey postcard at the ending: places found, stones, distance ridden and longest glide. S Done in 0.5.0.
31. Outfits as rewards: wrap and scarf colours from requests and finds. Pairs with idea 2, the bike garage. M
32. A desert fox that follows you after you help it and rides on the bike. M

### Sound, look and speed

33. Music swells at a summit and the first time you ride out of Home Camp. S
34. A sand trail behind the bike and a scarf that streams in the wind. M
35. Rumble on landings, boost and climbing over the top (Xbox controller and phone). S Done in 0.5.0.
36. * Frame-rate budget: simpler far rocks and a phone check every release (Sable's stutter was its biggest complaint). M

## From the Journey review (2026-11-19): ideas (BC added all nine)

Source: Journey (thatgamecompany, 2012). Borrow structure, never content (G4.8): no Journey art, glyph designs or music. Size: S small, M medium, L large.

### Movement

37. Dune surfing on the carpet: long downhill dune runs where the carpet skims the sand fast with a spray trail and warm sunset light. Builds on ideas 4 and 21. M
38. Glowing carpet tassels: hidden glyphs make the tassels longer, and longer tassels mean a longer glide. Works next to scrap upgrades and star stones (idea 23). M
39. Cloth kites: loose carpet scraps and desert kites drift in the air and refill boost or glide when you pass near them. M

### Story and world

40. One landmark on the horizon: a distant tower or glowing peak, seen from everywhere, as the goal of The Drift. No map needed to know where to go. M
41. Wordless story at camps: wall paintings at rest stops tell the family carpet's history, one panel per camp. Fits the story-later call. M
42. Chirp button: one button sends out a sound and a ring of light. It wakes glyphs, calls kites (idea 39) and lights hidden paths. S

### Feel

43. Sparkling sand: a sand shader that glitters and shifts color with the sun. Phone frame-rate check first (idea 36, E3). M
44. Music that follows your speed: extra music layers come in as you go faster or reach key spots. Needs the Patch.gg tracks split into parts (stems). Pairs with idea 33. M
45. Reward for finishing: a gold carpet dye after the ending, bought with nothing, earned by finishing. Fits coins-buy-looks. S

Not taken: Journey's silent online companion (needs servers and moderation). A safe offline version, a computer-run nomad who rides with you for a stretch, is open for BC as a later idea.

## Not planned (they break the pillars)

- Combat, enemies or bosses.
- Fall damage, death or a fail state.
- Fuel or water limits that strand you.

## Decisions from BC

- 2026-11-18: new name Saffron Drift (picked from Threadwind, Dune Post, The Drift, Saffron Drift, Pattern of Home, keeping Glasswind). Story direction "The Drift" for 0.8.0. Name now, story next. Page address changes to saffron-drift.
- 2026-11-18: the bike becomes a magic carpet, like Aladdin but our own design. Rider stands surf style. Starting look: terracotta desert (terracotta rug, sand border, dark brown zigzags). Black dot on first boost reported (fixed in 0.7.0).

- 2026-11-18: still no boost smoke on the phone (fixed in 0.6.1). Some pickups should be coins: coins buy looks (bike paint and smoke colors), scrap stays for Kip's upgrades (BC picked the recommended option).

- 2026-11-18: "move to next release, smaller world with more things to do, and collect and upgrade". Built as 0.6.0.

- 2026-11-18: "move forward with your best judgement for the next releases". 0.4.0 took the starred climbing and camera items, 0.5.0 the fires, stone stamina, postcard and rumble.
- 2026-11-18 browser test: can't jump while running, no sound or music, add smoke behind the bike on boost. All three fixed in 0.5.0.
- 2026-11-18: yes to the bus layout file in the shared starter base. The Menu should go away when Settings opens (fixed in 0.5.1).

- 2026-11-18: named Glasswind. Build the 3D driving starter first, then Glasswind from it. Low-poly flat color. Bike sigils as keepsakes.
- 2026-11-18: keep going to 0.3 and the Game Shelf, then BC tests. Title track B (Ancient Winds). Shelf picture A (riding an arch).
- 2026-11-18: "go" on Glasswind with the defaults: a gentle climbing stamina limit and the repo slug `glasswind`. The rider waits on BC.
- 2026-11-19, 1:48 PM: "Add all nine to backlog". Ideas 37 to 45 from the Journey review added.
