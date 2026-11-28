## v0.94: Water Electrolysis

- New tier 6 building: **Electrolysis Hall** (6×4, $150,000, 300 kW, built on site from 12 steel plate, 30 copper cable and 2 control panels). It turns 20 filtered water into 30 oxygen + 60 hydrogen every 4 s.
- New research: **Water Electrolysis** (180,000, after Chlor-Alkali).

## v0.93: Build sounds

- Buildings land with a heavy thump when you place them, and pipes with a softer one.

## v0.92: Sun in the corner, tidier profiles

- The sun or moon now sits in the top-right corner, bigger, with no countdown.
- Profiles: the activity calendar is gone, and the stats sit in one cleaner strip.

## v0.91: Wind turbines and grid batteries

- New **Wind Turbine** (2×2, 50 to 348 kW): one turbine, early. Research **Wind Turbines**.
- New **Grid Battery** (4×3): stores 360,000 kJ, 1000 kW in or out. Research **Grid Storage**.
- The wind never stops: wind power always gives at least 14.5% of its rating, and about 57% on average.
- Solar Farm: 1400 kW by day (was 400), $75,000. Smog lowers its output.
- Wind Farm: up to 1390 kW (was 300), $80,000. It now also needs Wind Turbines.
- Wind turbines are drawn from above.

## v0.90: Solar and wind farms

- New **Solar Farm** (5×5, 400 kW): full power by day, nothing at night. Research **Solar Farms**.
- New **Wind Farm** (5×5, up to 300 kW): output rises and falls with the wind. Research **Wind Power**.
- Day and night: 10 minutes of each. The top bar shows the sun or moon and the time to sunset or sunrise.

## v0.89: New intro music

- The intro music is played on new instruments: plucked strings, electric piano, marimba and a drum kit, in a smaller room. Same tune, same beat.

## v0.88: New click sounds

- New button click sound.
- Continue, Play and Create world have their own start sound.

## v0.87: Co-op world settings

- Co-op worlds no longer have a room code. **Host co-op** is gone from them: the game menu has **Co-op world settings [K]** instead, where you see every member and invite players by Discord handle. Players join only by accepting an invite.
- The world's owner sets what each member may do: **Build**, **Buy** (new buildings and land), **Mass delete** (removing a whole selection at once), or **Viewer** (watch only).
- Solo worlds still host a temporary room with a code, as before.

## v0.86: Button clicks

- Buttons now make a soft click when you press them.

## v0.85: Intro polish

- Visual bug fixes.

## v0.84: Start screen

- The intro now opens on a **Click to start** screen, so it plays with sound from the first frame.
- The intro only plays on your first visit; after that the game loads straight in. Add `?intro` to the address to watch it again.

## v0.83: Play button

- The intro now waits on its logo with a **Play** button once the game is ready (Enter, Space or Esc work too), then fades the picture and music out instead of cutting off.
- The intro no longer stutters at the start: the game downloads while it plays and starts once the logo is up.

## v0.82: Intro fix

- Clicking the intro to turn on sound no longer restarts it or cuts it short.

## v0.81: Faster world loading

- Worlds open much faster: the recipe book and the wiki are put together the first time you open them instead of while the world loads.
- The intro shows a gold loading bar while the game downloads; it fades out once the game is ready.

## v0.80: Intro, new buttons, cheaper land

- The page opens with an animated intro while the game downloads (click or press a key for sound; Esc skips once the game is ready).
- Buttons are raised, with a lit top edge and a darker lip, and press down when clicked.
- Land on 144×144 worlds costs less as you grow: plot 10 is $160k (was $200k), plot 25 $1.2M (was $1.6M) and the last plot about $12M (was $19M). The first few plots barely change.
- Fixed memory building up each time you load another world without reloading the page.

## v0.79: Smoother menus

- Fixed research slowing to a crawl while saving up for the last topics: points now come in at full rate until the bank holds as much as the dearest topic you can research.
- The **Electrorefinery** plates a cathode every second instead of every 6 s.
- The title screen slides and fades: its menu comes in on opening, pages slide in from the right and out again, and dialogs ease in.
- The loading screen has a gold bar with moving stripes, a conveyor of goods underneath, and a line saying what is being loaded.

## v0.78: Tower Crane, nuclear power removed

- **Tower Crane** (3×3, research Cement): pipe items into its base and it lifts them, 10 a second, into any construction site within 16 tiles.
- Construction sites now take their build materials only from a Tower Crane; pipes into their edges no longer deliver. Their panels and the shop say so.
- Chlor-Alkali now also needs Displays and Cement, Deep Mining needs Cement and Assembly Lines, and Uranium Milling needs Precast Concrete, so their buildings' materials can be made once they're researched.
- Nuclear power is gone: the Pressurised Reactor, Steam Generator, Spent Fuel Pool, the Control Room and meltdowns. Worlds that had them get back what the buildings cost, and the points spent on Nuclear Power. Fuel rods are still made and sold.
- Deposits outside your land now show at Medium and Low graphics too, so the map matches the new-world preview.
- The new-world form shows Sandbox's starting money as ∞.

## v0.77: Nuclear power

- **Pressurised Reactor** (11×11, research **Nuclear Power**): a 7×7 core of Low-Enrichment Fuel Rods and control rods in 4 groups. Its hot Primary Coolant goes to **Steam Generators** (12 MW each) and comes back cooled; their steam turns Large Steam Turbines.
- **Control room** (Enter on the reactor): core map, heat and rod temperatures, graphs, rod groups, rod speed, pump and **SCRAM** (End).
- Refuel with the **lid** (U): it opens only with every rod in and cool. Spent rods go to the **Spent Fuel Pool**.
- Rods over 700 °C are damaged; at 1,200 °C the core melts down, destroying everything within 6 tiles and the turbines it feeds. The wreck pollutes and blocks building around it until 5,000 concrete seals it.
- Primary Coolant and spent rods are radioactive: tanks, storage, sellers and dumps refuse them.

## v0.76: Uranium and zirconium

- **Uranium Ore** and **Borax** deposits, rare and far from the start. The **Deep Mine** (4×4) blasts 20 uranium ore from 1 ANFO every 10 s and stops without it; the **Borax Quarry** digs borax.
- **Uranium milling**: the Crusher crushes uranium ore. The **Ore Leaching Plant** (8×8): 20 crushed ore + 10 sulfuric acid + 10 caustic soda → 6 uranium oxide concentrate + 20 sand + 60 tailings. The **Precipitator**: 6 concentrate + 5 ammonia → 4 yellowcake + 10 wastewater.
- **Zirconium**: the **Mineral Separator** takes 1 zircon out of 10 sand. The Smelter bakes 2 zircon + 1 coke into zirconium carbide, the Chlorinator turns it with 20 chlorine into 10 zirconium tetrachloride, the **Kroll Reactor** reduces that under 5 nitrogen to zirconium sponge, and the Rolling Mill rolls a sponge into 4 zircaloy tubes.
- The **Fuel Assembler** seals 20 yellowcake into a zircaloy tube: a **Low-Enrichment Fuel Rod**, sold for $9,000.
- The **Fluorine Cell**: 10 hydrofluoric acid → 5 fluorine + 5 hydrogen. The Acid Plant makes boric acid: 10 sulfuric acid + 10 water + 2 borax → 10.
- Research: Fluorochemistry, Deep Mining, Zirconium, Uranium Milling and Nuclear Fuel.
- The Chlorinator takes silicon at its left input as before, but its recipes list chlorine, then the solid, then hydrogen.

## v0.75: Atomic Chemistry begins

- **Tier 6, Atomic Chemistry.** New research **Chlor-Alkali** (150,000) and **Siemens Process** (250,000).
- **Evaporation Pond** (5×5, no power): 20 water → 1 salt every 4 s.
- **Chlor-Alkali Cell** (4×3, 300 kW): 2 salt + 10 filtered water → 10 chlorine + 10 caustic soda + 10 hydrogen.
- **PVC** in the Polymer Reactor: 10 ethylene + 10 chlorine → 2. The Assembler makes copper cable from it: 8 wire + 1 PVC → 2 cable.
- **Chlorinator** (3×3): 10 chlorine + 10 hydrogen + 1 silicon → 20 trichlorosilane. The **Polysilicon Reactor** turns 20 trichlorosilane + 10 hydrogen + 1 silicon into 2 polysilicon.
- **Construction sites**: a bought tier 6 building goes down as a site and only runs once its build materials are piped into its edges. Its panel shows what has arrived. Removing a site gives back its price and the value of what was delivered.

## v0.74: Chains that meet

- **Chip Fab** now also takes **Photoresist** (new: Polymer Reactor, 10 benzene + 5 ethylene → 2) and 5 nitrogen per batch. The **Crystal Puller** takes 10 nitrogen per boule.
- **Fluorite** deposits, mined by the new **Fluorite Quarry** (research Fluorite Mining). The **Acid Plant** digests it: 10 sulfuric acid + 10 water + 2 fluorite → 10 hydrofluoric acid + 1 gypsum. Hydrofluoric acid etches 6 chips a batch instead of 4; gypsum can replace slag in the **Cement Kiln**.
- **Control Panels** and **Servo Actuators** are made in the **Advanced Assembler** (6 s and 7 s). Servos use 2 **Nylon Gears** (Injection Molder: 2 nylon → 3) instead of ball bearings, and sell for $3,000.
- The Assembler can make copper cable from nylon: 8 wire + 1 nylon → 2 cable.
- **ANFO**: the Asphalt Plant mixes 9 ammonium nitrate + 5 fuel oil into 2.
- Chip Fabrication now needs Polymers and Catalytic Reforming, Silicon Wafers needs Air Separation, and Advanced Assembly needs Nylon and Injection Molding.

## v0.73: Bigger maps, typed split valves

- New worlds are **144×144** (81 plots) and start with the 3×3 plots round the centre. Land gets dearer more gently: plot 10 costs about $200k, the last about $22M. Existing worlds keep their size and prices.
- The **Split Valve** takes a typed share: select it, press **Tab** (or click the box), type the percent to divert out the side and press Enter. A box of split valves takes it all at once.
- The **Overflow Valve** shows which end is the inlet and which is the main outlet.
- Sandbox worlds have infinite money.

## v0.72: Copy, paste and rows

- **Copy and paste**: box-select some buildings and press **F6** (or **Copy** in the panel) to pick up a copy. Each click builds it again, with facing, pinned recipes, valve and T-fitting settings, closed pipe sides and the wires inside the box. **F7** picks up the last copy again.
- **Rows**: drag with a bigger building held to lay a row of them; **-** and **=** change the gap.
- **Q** now also copies the building's pinned recipe and setting.
- A box of one machine type shows its recipe buttons, and **Tab** sets them all; a box of split valves sets their share together. **F4** (or **All of type**) selects every building of that type.
- **E** empties every pipe in a box selection; **Shift+E** empties the whole joined run.
- **Research queue**: **Shift+Enter** (or **Queue**) adds a topic after the target; the next one starts when the target is done.
- **Camera bookmarks**: **Shift+4** to **Shift+9** set one, **4** to **9** fly back. Saved with the world.
- **F9** (or **Stalled** in **Info views**) jumps to the next machine that's short of input, blocked or without power.

## v0.71: Endless research, bottleneck numbers

- Fixed Research Stations throwing items away when the research bank is full: they now refuse them and show **Bank full**, so the line backs up. Their panel shows the bank and the rate points come in at.
- **Endless research**: once the whole tree is done, four topics can be researched again and again (up to level 10): **Process Optimisation** (machine speed), **Logistics** (item pipe speed), **Grid Efficiency** (line loss) and **Market Contacts** (sale prices).
- The top bar shows **Working N / M** machines instead of the building count.
- A machine's panel shows its rates per minute at full speed, what it made over the last minute, and its uptime over the last two minutes.
- Build menu keys: **,** and **.** switch tabs; with nothing held, **[** and **]** pick a card and **Enter** takes it.
- The Blast Furnace now pollutes (1 a batch). Venting sulfur dioxide pollutes much more; dumping water, steam or filtered water doesn't pollute.
- Pollution fines show in the fee figure next to INCOME, and dropping back under the limit resets the fine clock and the warning.
- The **Best income** leaderboard is now per second, held over 10 minutes, so it starts fresh. A solo world's scores only count for the account that first sent them.
- Shorter status and port texts.

## v0.70: Steam in two loops

- Fixed a Large Steam Turbine running on a single boiler. It now needs at least half of its 270 steam/s, so at least two boilers.
- The **Large Steam Turbine** makes up to **1,600 kW** on 400 °C steam.
- New **Fired Heater** (Power tab, Steam Power research): burns coal, coke or petroleum coke to heat water to 300 °C or 400 °C.
- **Boilers** no longer burn fuel. Hot water from a heater runs through their heating loop and warms them; plain water boils into 90 steam/s at the boiler's temperature once it is at 100 °C or more. Both outlets must be piped somewhere, or the boiler stops.
- Existing boilers have a new heating outlet on their left and take hot water where coal used to go: give them a heater.

## v0.69: Heavy refining, co-op from the start

- Fixed the game crashing for a player joining a co-op room.
- **New world** has a **Players** choice: pick **Co-op** and the world starts as a co-op world, with its room open.

- Five new refinery buildings turn **Heavy Residue** into money: the **Vacuum Tower** (gas oil and lube oil), **Catalytic Cracker** (gasoline), **Hydrotreater** (diesel and sulfur, using hydrogen), **Delayed Coker** (petroleum coke and gas oil) and **Asphalt Plant** (residue and sand into asphalt).
- The **Steam Cracker** and **Catalytic Reformer** now also leave 2 residue a batch, from a new outlet on their right side. Existing ones stop once it backs up, so pipe it away.
- Petroleum coke fires a Boiler like coke.
- New research: Vacuum Distillation, Catalytic Cracking, Hydrotreating, Delayed Coking and Asphalt.

## v0.68: New game menu, first-study bonus, faster loading feedback

- The game menu (Esc) is redesigned: the world's name, a SOLO or CO-OP tag and its difficulty, money and play time at the top, a gold **Resume**, the common actions in pairs, co-op actions in their own group, and the ways out at the bottom.
- The **first 50** of each item type studied at a Research Station pay **5×** research points. The station lists each item's bonus units left.
- Opening a co-op world or joining a room shows the loading screen straight away, instead of the title backdrop while it connects.
- Leaderboards and profiles show placeholder rows while they load.
- No more "Made with Unity" screen when the game starts.
- A co-op world you're playing alone is saved to the server only when it saves (autosave, F5, leaving); with other players in the room it still uploads every minute.
- Opening a co-op world takes the server's newer copy automatically. **Pull from server** is gone from the game menu.

## v0.67: Invites by handle fixed

- Players who signed in with Discord before v0.66 couldn't be invited or found by their @handle. Opening the game once now fixes that (it signs you in again for a moment).
- Co-op buttons and tags are a darker teal, so their text is readable.

## v0.66: Make co-op world, player profiles

- **Host co-op [K]** on a solo world opens a **temporary room** straight away. Its card has **Make co-op world [M]**, which says what changes and asks before it does. The game menu has **Make co-op world [M]** too, and so does each solo world's row in **Load world** (**Make co-op**).
- Co-op and solo worlds look different everywhere: in Load world a co-op world has a teal stripe, a **CO-OP** tag with its code and its members' pictures, and a solo world says **SOLO**. The game menu says **Solo world**, **Co-op world CODE** or **Co-op guest**.
- Invites use the **Discord handle** (@name), not the display name.
- **Player profiles**: your picture in the top-right opens yours. Click anyone on a leaderboard, or search a @handle, to see theirs: worlds, day streak, active days, play time, total earned, best place, a year of activity, every world with its play time, and leaderboard places.
- Co-op worlds show every member's picture on the leaderboards, in Load world and on profiles.

## v0.65: Co-op worlds, invites

- **Host co-op [K]** now asks how: **Host once [1]** opens a room under a new code for this session only, and guests keep no copy. **Co-op world [2]** (Discord sign-in) makes the world a co-op world for good, with its code reserved for it.
- A co-op world's card has **Invite [I]**: type a Discord username. The invited player gets a banner on the title screen and an **Invites** page with Accept and Decline. Accepting makes them a member and opens the world.
- Only members keep a copy of a co-op world, or open it by its code when nobody is online. Anyone with the code can still join while a member hosts.
- On the leaderboards a co-op world shows once, with all its members' names, and counts for each of them.
- Worlds already shared before this update become co-op worlds the next time they upload.
- The wiki shows the pollution each recipe and generator makes a cycle.

## v0.64: Air Scrubber rework, Water Filter

- The **Air Scrubber** is now 3x3 and runs on water. Pipe water into its back; every 4 s it uses 2 water and puts out 4 **Wastewater** at the front, which needs somewhere to go, like a Fluid Dump. With no water, or with its wastewater backed up, it stops.
- It takes out **0.6** pollution a second on **Filtered Water**, and **0.3** on plain water (it was 3 a second).
- Its panel shows **Water in** a second, **Scrubbing** a second and **Removed**.
- New **Water Filter** (3x3, $1,800, unlocked with Air Scrubbing): 4 water → 3 filtered water every 2 s.
- **Boilers** take filtered water too, for a tenth more steam: 88 a batch on coal, 176 on coke.
- Placed scrubbers grow to 3x3. One with no room around it goes back into your inventory.

## v0.63: Shared worlds fixed, Pull from server

- Shared co-op worlds now really save to the server. Before this, other players and devices never got the newest copy.
- Two players can no longer both host the same shared world and overwrite each other's progress. If someone else already has the room open, you join them as a guest.
- A shared world uploads when you save (F5, menu Save, autosave) and when the tab goes into the background, not only once a minute.
- Joining waits longer (15 s) before giving up on a slow connection.
- **Pull from server [Y]** in the game menu replaces your copy of a shared world with the newest one on the server.
- If the server has a newer copy when you open a shared world, the game menu opens on **Pull server copy · rev N (this M) [Y]** instead of swapping it in. Close the menu to keep playing your copy.

## v0.62: Join a world by its code, any time

- A co-op world's code now works even when nobody is playing it. **Join co-op** with the code (or open its link) on any device, including one that has never had the world, and the newest saved copy opens there. You host it for anyone else who joins.

## v0.61: Faster blast furnace

- The **Blast Furnace** runs a batch every **4 s** instead of 8 s: 5 concentrate + 3 coke + 2 limestone → 50 molten iron + 3 slag. That's 12.5 molten iron a second, two and a half times as much.

## v0.60: Turbine output readout

- The steam turbine's panel starts with its real output, like **Output  800 / 2700 kW**.
- It also shows the steam coming in against what full output needs, like **Steam in  26.7 / 90 /s  (30%)**. One boiler makes 26.7 a second, so a turbine needs four for full power.
- **Shaft speed** is now called **Spin-up**.

## v0.59: Research tree rework

- The research screen is grouped into one band per tier. Cards are wider and show what they unlock, the cost and how long until you can afford it.
- Researched, available, affordable and locked topics each look different. Every prerequisite has its own line with an arrow, and lines to the picked topic light up.
- The screen opens on the cheapest topic you can research and shows **Researched N / 46**.
- Pick a locked topic to see every step on the way to it, numbered, with the total cost and time. **Enter** makes it your target: points buy each step as soon as they can. **Home** jumps back to it, and the top bar shows its name.
- The panel below a topic shows the recipes it unlocks, what it needs and what needs it (**1**-**9** jump to them).
- Every topic now costs more than the ones before it. **Quarrying** comes after Ore Crushing, **Flow Control** after Fluid Handling (1,000 points), **Air Scrubbing** after Steam Power (3,000 points), and copper no longer needs Steelmaking until Electrorefining.
- Merged topics: **Copper Converting** includes the Acid Plant, **Silicon Wafers** includes the Wafer Saw, and **Electric Motors** has the Stamping Press and Coil Winder. Points spent on the removed topics are refunded.
- The **POWER** gauge is always on the top bar again. The top bar buttons no longer show their keys.
- Fixed: fluid crossings didn't connect to machines, pumps or tanks next to them.

## v0.58: Tab icon

- The browser tab is called **Bageland** and shows the iron gear.

## v0.57: Pollution builds slowly

- Pollution only starts once **Steelmaking** is researched, and builds over hours of play. It clears by itself over about half a day.
- The pollution number is no longer on the top bar. It is in the **Pollution** info view (**Z**), which unlocks with Steelmaking.
- Above **50,000**, *every* machine slows: half speed at 150,000, never below a quarter.
- Past 50,000 a letter arrives from the Clear Skies Coalition. If it stays that high, the court fines you every 30 minutes of play: 2% of your money plus $0.10 per unit of pollution.
- **Air Scrubbing** now comes after Steelmaking (6,000 points).
- **INCOME** and residue costs show per second, like research.
- On narrower screens the **POWER** gauge moves from the top bar into **Info views [I]**, so the whole bar fits.

## v0.56: Feedback screenshots

- **Give feedback** also sends a picture of your world (without the menus), so the developer can see what you mean.

## v0.55: Pollution

- **Pollution**, on the top bar. Burning fuel makes it: coal **1** a unit, coke **0.6**, fuel oil **0.4** (Furnace, Boiler, Coke Oven, Cement Kiln and fuel-burning generators). Dumping fluid adds **5** a unit of Heavy Residue and **0.05** of anything else.
- Pollution clears by itself: about a third of it every 100 s.
- Above **1,000**, every extractor slows: half speed at 5,000, never below a quarter. The top bar shows the speed in red.
- **Air Scrubber** (Processing, $6,000, 2x2, **80 kW**, research **Air Scrubbing**: 1,500 points, after Induction Melting): takes out **3** pollution a second while there is any.
- **Pollution** info view (**Z**, or in **Info views [I]**): pollution per second over every building that makes or scrubs it, plus the totals and the biggest sources.
- **Booster Pump** costs **$150** (was $1,500).
- Updates that fix bugs must be installed to keep playing: the page shows **Update to play** (Enter, or click **Update**). Updates that only add things still show the optional banner.
- Co-op needs everyone on the same version. A player on an older version is asked to update before joining.
- Fixed: in co-op, machines, storage and generators kept piling up items (inputs and outputs far over their limits, like 400/10, or millions in a Press) and then dumped them all at once. Worlds that already have too much load with each machine at its limit.

## v0.54: Faster

- The game runs faster in the browser.
- **Low** and **Extra low** graphics now draw at normal resolution on high-density screens (from the next time the page loads), which is much lighter for weak laptops.

## v0.53: Shared co-op worlds

- Opening co-op shows the room code in big letters in the middle of the screen, with **Copy link [C]** and **Share [Enter]**. Opening the link joins the room straight away.
- Co-op worlds are now shared. Everyone who joins keeps their own copy in **Load world**, and can keep playing it alone after the others leave.
- A shared world always uses the same room code. Whoever opens it first hosts it, and anyone who opens it after joins them.
- When nobody else has the world open, you get the newest version: progress made by any player carries over to the others.

## v0.52: New art, residue costs

- New title logo, and redrawn Power Pole, Transmission Tower, Water Pump, Distillation Tower, Ingot Molder, Crusher, Solar Panel and Wire Drawer.
- Residue costs show in red next to **INCOME** on the top bar, per hour.
- Rolling Mill: copper rod now takes **4 s** (was 3).
- Bigger names on the build menu cards.
- Leaderboard tabs all fit inside the leaderboard.
- Visual bug fixes.

## v0.51: Induction furnace, leaderboards

- **Induction Furnace** (Processing, $2,400, research **Induction Melting**: 1,000 points, after Ore Crushing): melts ore or sand on electricity alone, with no coal. It has one input at the back and molten metal out the front. Every melt is a fifth quicker than in the Furnace, and it draws **60 kW** (the Furnace draws 5).
- **Leaderboards** look better: players' Discord pictures, gold, silver and bronze medals for the top three, yellow tabs and highlights, and your own row marked in yellow.
- Leaderboard tabs say what they rank: **Total earned**, **Best income/min**, **Techs researched**, **Time to $100K**, **Time to $1M**, **Time to $100M**.

## v0.50: Turbine exhaust, residue, fluid dump

- **Large Steam Turbine exhaust**: the spent steam condenses and leaves as **water** from a new outlet in the middle of the front, 22.5/s at full load. That is the same amount of water its boilers boiled, so you can pipe it straight back to them. With nothing on the outlet it vents into the air, so existing turbines keep running. If you pipe it somewhere that fills up, the water backs up and the turbine stops ("Exhaust full").
- **Heavy Residue**: distilling crude now also leaves 4 residue per batch, from a new outlet low on the right side of the Distillation Tower. A refinery with nothing on that outlet stops when the residue backs up. Residue gets rid of money, not makes it:
  - Selling it at a Tanker Bay costs **$3** a unit.
  - Dumping it costs **$4** a unit.
  - It clings to pipes. Emptying a pipe or tank that holds residue costs **$8** a unit; it stays put until you can pay. Removing the piece costs the same, even into debt.
- **Fluid Dump** (Fluids, $250, no research): takes any fluid from any of its four sides and throws it away as fast as it arrives. Water, steam and the rest are free to dump; residue costs money.
- Money can now go **below zero** from residue costs. In debt you can't buy anything until you earn it back.
- **4-Way Junction** gets the T-fitting's node: select it, then drag from the middle to an opening to send items out there, or drag an opening's arrow into the middle to make it a way in. Tab no longer cycles its settings.
- **Sandbox** worlds start with **999** of every building in the inventory, topped up on every load.
- Visual bug fixes.

## v0.49: 4-way junction

- **4-Way Junction** (Item Pipes, $80, no research): openings on all four sides. Select it and press **Tab** / **Shift+Tab** to pick which are ways in and which are ways out, any mix with at least one of each (14 settings). A new one splits from the back out the other three; items going out take turns, lines coming in join.
- Min graphics: input and output markers are their real size again (v0.47 drew them stretched across the map).
- The game menu no longer shows the difficulty and leaderboard upload line. Feedback messages still carry it.
- Wiki: research costs said "RP" twice.

## v0.48: Balance

- **Power Supply is honest about steam turbines.** A turbine with a full steam tank used to count its whole rating in Supply even when one boiler fed it. Supply (top bar, wiring panel, grid details) now counts each turbine only for the power its boilers' steam keeps up, shared between turbines on the same steam line. What the turbines actually made was already limited by the steam; only the number was wrong.
- **Boilers** raise more steam: 1 coal + 20 water now makes **80** steam every 3 s (was 60), and 1 coke + 40 water makes **160** superheated steam every 6 s (was 120). A Large Steam Turbine needs about 3.4 boilers and 1.125 coal/s for 1800 kW, so it now gets a third more power from each coal than Coal Generators.
- **Wire Drawer**: 1 copper ingot → 2 wire now takes **12 s** (was 6). It paid back twice as fast as anything at its price.
- **Steel mill steps are faster** (prices unchanged): Caster steel ingot 3 → **2.4 s** and slab 5 → **4 s**, Rolling Mill plate and beam 4 → **3.2 s**, Machining Center bearings 4 → **3 s**.

## v0.47: Split valve, ports on top

- **Split Valve** (Fluids, $600, tier 3, research **Flow Control**: 3,000 points, after Fluid Handling and Ironmaking): a T-fitting where fluid comes in at the back, and a share you set goes out the right side while the rest goes out the front. Select it and press **Tab** (+10%) or **Shift+Tab** (-10%), or use its buttons; a new valve starts at 50%. If one outlet is full the other takes the fluid, unless that outlet is set to 0%.
- The Overflow Valve is now listed as tier 2, like the rest of Fluid Handling.
- Input, output and power markers are always drawn on top: a building's working animation no longer covers its ports.
- The oil pumpjack is drawn from above like every other building, so it looks right when rotated.

## v0.46: Centred grid

- The ground grid's lines now run along the cell boundaries. Before, each line sat inside its cell's left and bottom edge, so every building looked nudged left and down.

## v0.45: Give feedback

- **Give feedback [J]** in the game menu: write a message and press Enter, and it goes straight to the developer, with your world's name, the game version and its difficulty. Signed-in players' Discord names are attached; you don't need to be signed in.

## v0.44: Overflow valve

- New **Overflow Valve** (Fluid Pipes tab, $300, Fluid Handling research): fluid goes out the front first, and only what the line ahead can't take spills out the left and right, in turn. Its inspector shows whether it's passing or overflowing.

## v0.43: Difficulty in the menu

- The pause menu shows the world's difficulty under its name, whether it counts for the leaderboards (unranked for Custom worlds and co-op guests), and how the last score upload went.

## v0.42: Power lines and parts

- **Line loss**: power wires lose 0.6% per tile of length (6% over a full pole span). Machines far from their generators draw more to make up for it. The inspector shows each machine's loss, each grid's losses and each wire's.
- **Transmission Tower** (High-Voltage Lines research, after Steelmaking): a 2×2 steel tower whose wires reach 28 tiles and lose a tenth as much.
- Machines take one wire, so power spreads through poles rather than from machine to machine. Generators and batteries still take three. Existing wires stay.
- Steel parts are worth less, so building with them pays more than selling them: steel ingot $176 (was $185), slab $352 ($361), plate $130 ($139), beam $194 ($209), bearing $102 ($121), bolts $26 ($28.50), laminations $36 ($39.50). Frames, motors, stators and girders keep their prices.
- Plastic is made from ethylene and **hydrogen** (5 per batch) instead of water. Plastic lines need a hydrogen pipe in place of the water one.
- Refined copper rod draws into 30 copper wire at the component manufacturer.
- New **Air Compressor** ($1,850): motor, two bearings and a plastic casing, at the assembler.

## v0.41: Living title screen

- Your last world runs behind the title menu: its machines working and pipes carrying items, with the camera drifting over it. Nothing there is saved.
- A first visit shows a small starter factory instead: excavator and coal mine, furnace, ingot molder and depot on solar power.

## v0.40: Title screen

- The corner shows the game's version; click it for the changelog.
- First visit: New world leads, with no empty Continue or Load world.
- Continue shows the world's name, money and play time.
- New world: **New map** (or click the map) rolls another one, and a colour key lists the deposits on it.
- Load world: each world has a little map of its factory. Double-click a world to play it.
- Settings, Changelog and Leaderboards sit in a smaller row under the play buttons.
- Playing or creating a world zooms into the map as the menu fades.
- The title logo moves a little.
- Sharper text everywhere.
- **Sign in with Discord** is a Discord-blue button with the Discord logo.

## v0.39: Difficulties

- New worlds pick a **Difficulty**: **Easy** (resources anywhere, comfortable starting money), **Medium** (plentiful, large deposits, comfortable money), **Hard** (normal deposits, standard money), or **Custom** for anything else.
- Leaderboards are split into Easy, Medium and Hard. Custom and sandbox worlds don't go on them.
- Worlds made before this count as whichever difficulty their settings are closest to, so they're on the leaderboards too. The world list shows each world's difficulty.

## v0.38: Button frames and loading bar

- Buttons get a gold frame while the mouse is over them.
- Creating or loading a world shows a loading screen with the world's name and a bar that fills as it's built.

## v0.37: Mouse-only title screen

- The title screen has no keyboard shortcuts or [key] labels any more. Use the mouse there; Esc still closes a page or dialog. In-game shortcuts are unchanged.

## v0.36: Bageland

- The game is now spelled **Bageland**, with one l, in the title logo, the browser tab and the guide.

## v0.35: Profile corner

- Discord sign-in moved to its own badge in the **top-right corner** of the title screen. Once signed in, it shows your Discord picture and name. Press D or click it to sign out.
- Switching a machine's recipe while it's working no longer throws away the batch in progress. The batch finishes as what it started as, then the new recipe takes over.
- Space and 1/2/3 no longer unpause or speed up the world while the menu, recipe book, research or wiki is open.
- Joining two pipe lines that hold different fluids no longer deletes one of them. They stay apart until one runs dry or is emptied (E), then they join.
- Faster with big factories: wire counts are cached, box-deleting many buildings is quicker, and saves are smaller.

## v0.34: Leaderboards

- **Sign in with Discord [D]** on the title screen. Signing in only reads your Discord name.
- **Leaderboards [B]** on the title screen: Money earned, Income per minute, Research, and fastest play time to $100K, $1M and $100M. Keys 1–6 or ←/→ switch boards.
- While signed in, your worlds send their best numbers every minute and when you leave. Sandbox worlds and worlds joined in co-op don't count.
- Worlds now keep track of money earned, best income per minute and milestone times. Older worlds start counting from now.
- **Large Steam Turbine** is now listed at its real top output, 2700 kW, reached on 400 °C coke steam. 300 °C coal steam still gives 1800 kW. Before, it said 1800 kW but made up to 2700.

## v0.33: Switch buildings in hand

- While holding a building, **[** and **]** pick up the previous or next one in its build-menu tab (straight pipe, turn, T-fitting and so on), keeping its facing.
- Co-op: the K and J keys now work in the browser.

## v0.32: Co-op

- **Play together**: open the menu (Esc) and pick **Host co-op [K]** to get a 5-letter room code. Friends pick **Join co-op [J]** on the title screen and type it in. Up to 8 players.
- Everyone builds, moves, removes, wires, buys land and researches in the same world. Each player's pointer shows in their own colour.
- The host's world is the real one and only the host saves it. Other players go back to the title screen when the host leaves.
- The menu doesn't pause the world while you're in co-op. Keep the host's tab visible: browsers slow down background tabs.

## v0.31: Shop stats

- Hovering a building in the build menu now shows its numbers: power made or used, fuel and water per minute or second, storage, and how many recipes it runs.

## v0.30: Tanker Bay and steam rebalance

- **Tanker Bay** (Selling tab, 4×3): sells any fluid piped in at the back. A tanker holds 600 of one fluid and drives off when full, or after 20 s with nothing coming in, and you're paid for the load as it leaves. The next truck parks 8 s later.
- **Steam rebalanced**: a boiler now boils 20 water into 60 steam every 3 s, so a turbine needs four or five boilers, three water pumps and 1.5 coal/s. Coke boilers: 1 coke + 40 water every 6 s → 120 steam at 400 °C.
- **Oil Generator** now makes 1200 kW (was 300).
- The building count in the top bar leaves out pipes and power poles.

## v0.29: Heat

- **Every fluid has a temperature**, set where it's made: water 15 °C, steam 300 °C, molten iron 1550 °C, molten steel 1650 °C, liquid oxygen −183 °C, liquid nitrogen −196 °C and more. It travels with the fluid, mixes in pipes and tanks, and is lost a little at every joint, so long lines run cooler. Select a pipe to see it.
- **Steam turbines run on heat**: nothing from steam at 100 °C or below, the full 1800 kW at 300 °C, and up to 1.5× on hotter steam. Keep boilers close to their turbines.
- **Superheated steam**: a boiler burning coke (1 coke + 2 water every 8 s) makes 400 °C steam, enough for 2700 kW from one turbine.
- Turbines spin up over about 6 s and run down over 10 s when the steam stops.

## v0.28: Smaller status box

- The box at the bottom left only shows while you're holding something (a building, wires, the land tool), and is sized to what it says. The full list of controls is on the wiki's Controls page [H].

## v0.27: Info views

- **Info views [I]** under the menu button opens a list of views: **Pipe view [V]** and **Ground lens [G]**. One shows at a time.
- The smooth art style is gone from Settings; the game is always pixel art.

## v0.26: Changelog on the title screen

- **Changelog [C]** on the title screen: every update, newest first. W/S or the arrow keys scroll it.
- The wiki's Updates page is now called **Changelog**.

## v0.25: Empty pipe

- **Empty pipe [E]**: select an item or fluid pipe and press E (or the button above Rotate) to throw away everything inside that one pipe.

## v0.24: Extra low graphics and building labels

- **Graphics: Extra low**, below Low: every building, pipe, deposit and the ground is drawn as a plain block of its average colour, with no textures. Otherwise it works like Low.
- **Building labels** (Settings): names written across every building of 2×2 tiles or more, shrunk to fit. Pipes and single tiles have none.

## v0.23: Graphics setting and two-way crossings

- **Graphics: High, Medium or Low** in Settings (title screen or the game menu). It applies straight away.
  - **High:** everything, as before.
  - **Medium:** working animations at half their frame rate and only for buildings on screen; deposits drawn only on your land and on plots for sale; capped at 60 fps.
  - **Low:** no working animations; deposits drawn only on your land (plots for sale too while the land tool is open); capped at 30 fps.
- Working animations now skip buildings that are off screen at every setting.
- **Crossings can run either way:** select one and a node appears with a red arrow for its back-to-front line and a blue arrow for its left-to-right line. Press anywhere on the crossing and drag toward any side to send that side's line that way; the other line stays as it was. **Tab** / **Shift+Tab** cycle the four ways it can be set.

## v0.22: Easier T-fittings and a ground lens

- **T-fitting drags:** drag from the middle node toward any opening, roughly that way, and items go out there. If that opening was the only way in, or one of two ways out, it becomes the one way out and the other two take items in.
- **Pipe view:** the 4 slot pips run along the pipe, so a vertical pipe shows a column, and they fill from the front end where items pile up. Items moving through pipes now only show while the pipe view is on.
- **Ground lens (G, or the button under Pipe view):** a tag at the cursor names the deposit in the cell under it. Deposits you haven't researched a miner for stay hidden.

## v0.21: Pipe view and research rate

- **Items flow through item pipes:** every item shows as a dot of its colour sliding along the pipe.
- **Pipe view (V, or the button under the menu):** item pipes turn green when flowing, red when blocked and grey when empty, with a pip for each of their 4 slots. Fluid pipes show how full they are. Where a jam starts, the pipe gets a pulsing red ring and whatever it feeds gets an orange one; machines with a stuck output get a red ring.
- **Research per second** shows next to your research points in the top bar.

## v0.20: In-game wiki

- **Wiki in the game:** press H (or **Wiki** in the top bar). It has the guide pages and a page for every building, item, fluid and research topic, with search.
- **Building pages** show price, size, power use or output, fuel and water, wire reach, ports, the research that unlocks it, and every recipe with its cycle time, items per minute in and out, and value added per minute.
- **Item pages** show sell value, research points, where it is found, what makes it and what uses it. Click any item or machine to jump to its page; Backspace goes back.

## v0.19: Working animations

- **Every building animates while it works:** drills spin, pump jacks nod, fires flicker, rollers turn, robot arms swing, stacks puff smoke. Idle, blocked or unpowered buildings stand still.

## v0.18: Cement, overflow fittings and a power gauge

- **Slag is useful now.** A Cement Kiln burns limestone, slag and coal into cement; a Concrete Mixer turns cement, sand and water into concrete; a Precast Yard casts concrete round steel beams into Precast Girders. New research: Cement and Precast Concrete.
- **Overflow Fitting:** items go straight on while the front takes them, and only the rest go out the sides.
- **Power gauge** in the top bar: kW in use against kW available, with a bar that turns red when machines are short of power.

## v0.17: Crank handle
- A hand crank's handle now turns: it follows the mouse while you hold it and keeps spinning while the flywheel runs.
- A still crank's handle glows, and with the mouse over a crank two arrows circle its handle.

## v0.16: Fluid pipe pieces, hand cranking, cheaper start
- Fluid pipes now come in pieces like item pipes: Straight, Left Turn, Right Turn, T-Fitting, a four-way Joint and a Crossing.
- Drag to lay a fluid line and turn pieces go in at the corners by themselves. R rotates a piece.
- Pieces join only where their openings face each other, so lines side by side stay apart.
- Fluid still flows like pressure, either way along a line. Booster pumps work as before.
- The Fluid Crossing lets two fluid lines cross without mixing.
- Fluid pipes in older saves become the piece with the same openings.
- Hand cranks are turned by hand now: hold the mouse button (or F) on one and circle the mouse around it.
- Each half turn adds half a second of running, and the flywheel holds 3 seconds, so a crank only runs while you keep turning it.
- A crank now gives 30 kW while turning, up from 10 kW.
- New Mixed Crossing ($40): a fluid pipe and an item pipe cross on one tile. R rotates it.
- Early machines cost less: mines and pumps, the furnace, ingot molder, crusher, press, grinder, wire drawer, depot, storage, research station and coal generator.
- While you hold an extractor, the cells it can mine pulse on the map.
- Limestone and crude oil stay hidden on the map until you research the building that mines them.

## v0.15: More starting money
- New worlds on Standard funds start with $5,000.

## v0.14: Molten metal, chemistry and pressure pipes back
- The Furnace now melts ore into Molten Iron or Molten Copper, and sand into Molten Glass. It leaves through a fluid pipe.
- New Ingot Molder (3x2): casts molten metal into ingots and molten glass into glass. Two units of melt make one ingot.
- The blast furnace's product is now called Hot Metal (molten pig iron). It still goes to the Oxygen Converter.
- New worlds start with $2,050 instead of $1,750, enough for the molder.
- Fluid pipes work like before v0.12 again: round pipes that join into a network and even out like pressure. The Booster Pump is back.
- You still lay fluid pipes by dragging, like item pipes. A pipe joins only the pipes you dragged it from and to.
- Fluid pipes are now grey, rounded tubes instead of blue, so they are easy to tell apart from item pipes.
- One-way fluid pipes from v0.12 and v0.13 load as round pipes, open only where the old piece was.
- New endgame chemistry, with six research topics:
  - Catalytic Reformer: naphtha into benzene and hydrogen.
  - Air Separation Unit: makes nitrogen and some oxygen, using cooling water.
  - Ammonia Converter: nitrogen and hydrogen into ammonia.
  - Nitric Acid Plant: ammonia and oxygen into nitric acid.
  - Prilling Tower: ammonia and nitric acid into Ammonium Nitrate.
  - Nylon Plant: benzene, hydrogen, nitric acid and ammonia into Nylon.

## v0.13: Steam power
- New Boiler (4x4): burns coal and turns water into steam. One unit of water makes 90 units of steam.
- New Large Steam Turbine (6x4): makes 1800 kW from 90 steam a second, taken in at three inlets along the back. Short of steam, it makes power in step with the steam it gets.
- Steam Power is a new research topic (2,500 RP, after Fluid Handling) that unlocks both.
- The Coal Generator no longer needs research.
- The Metal Press no longer needs research.
- New Wire Drawer (3x2): draws copper ingots into wire. No research needed.
- The Coal Power and Metal Forming topics are gone. If you had researched them, their points are back in your bank.
- Coking, Solar Panels and Precision Parts no longer need another topic first. Electrolysis needs only Fluid Handling, and Rolling only Steelmaking.

## v0.12: One-way fluid pipes, research cap and groundwater
- Research points now have a cap: 1.25 times the dearest topic you can research right now. Above half the cap, points come in slower and slower, and at the cap only 0.01% gets through. A factory left running fills the bank for your next topic but can't save up for the whole tree. Spend points to speed it back up.
- The top bar and the research window show the cap. Your points turn orange as they slow down.
- Water is now underground. It only shows on the map while you are placing a Water Pump or have one selected. Pumps work as before.
- Fluid pipes now work like item pipes. They carry fluid one way, back to front, and come as a straight, left and right turns, a T-fitting and a crossing. Drag to lay a line; corners get turn pieces.
- Fluid pipes are steel grey instead of blue. A dot in each pipe shows the colour of what it carries.
- The Booster Pump is gone, since one-way pipes need no pressure.
- In existing worlds, fluid pipes are turned to point the way fluid was flowing: away from pumps and machine outputs, toward what used them. Boosters become pipes. Check lines that had two sources feeding one pipe.
- The "New update" banner has an X to dismiss it.

## v0.11: Autosave icon
- A small disk blinks in the top-right corner whenever the game autosaves.

## v0.10: Bagelland
- The game is now spelled **Bagelland**, and the title logo reads "Bagelland" with only the B in capitals.

## v0.9: The research tree
- Buildings past tier 1 now have to be researched before you can buy them. Press **U** or the Research button in the top bar to open the tree.
- 38 topics follow the real production chains. Ore Crushing leads to Ore Washing, Ore Washing to Quarrying, and Quarrying plus Coking to Ironmaking. From there the tree goes on to Steelmaking, Rolling, Machining and up to Chip Fabrication.
- Pick a topic with the mouse or the arrow keys and press **Enter** to spend the points.
- Locked cards in the build menu are greyed out and show their cost in RP. Clicking one opens its topic in the tree.
- Existing worlds keep everything they have built or stored: the research behind those buildings is granted on load. Sandbox worlds start with everything researched.
- New title logo.
- The Manufacturing tab label no longer wraps onto two lines.
- The Acid Plant is now tier 4.

## v0.8: No more picking seeds
- New worlds always get a random map. The seed box and Shuffle button are gone from the New world screen.

## v0.7: New prices and the Research Station
- All sell prices are reworked from what the machines cost. A furnace or mine earns back its price in about 15 minutes; big late machines take 40-70. Parts that only go into other recipes pay back slower than finished goods. Early goods sell for much less and late goods for much more.
- New **Research Station** (Selling tab, $1,500): it takes items like a depot but pays research points instead of money, 1 RP for every $10 of value. The top bar shows your points.
- Research topics are coming next. Points you earn now will be kept.
- New worlds start with $1,750, enough for one small ingot line (Tight: $800).
- Removed two recipes that lost money at the new prices: cast iron ingots and wire from copper rod.
- Circuit boards are now made in the Advanced Assembler. The Assembler is now tier 3 and costs $110,000.
- New worlds always have iron, coal and water on the land you start with. Existing worlds keep their map.

## v0.6: Tiers, build search and the Crossing
- Buildings and recipes are sorted into five tiers, from **Basics** to **High Tech**. The build menu and recipe book show them in that order.
- Search the build menu: type in the box left of the tabs, or press **/**.
- New **Crossing** pipe: two lines cross without mixing (back to front, left to right).
- The big pipe arrows are back, and turn arrows now have a whole arrowhead.
- T-Fitting: drag from the node roughly toward an opening to turn it out; drag an arrow into the node to turn it in.
- Port arrows on buildings are drawn at twice the detail.

## v0.5: Arrow plates and safer updates
- Each item pipe now has a small square plate with a sharp arrow showing its flow.
- Clicking the update banner saves your game before the page reloads.
- The update banner and this box use the game's font.

## v0.4: T-Fitting arrows flip one at a time
- Dragging a T-Fitting arrow now only flips that arrow; the others stay put.
- The T-Fitting node and its arrows use the normal pixel art.
- Turn pieces show one bent arrow instead of three.

## v0.3: Clearer pipe arrows, drag to set a T-Fitting
- Pipe arrows are drawn at twice the pixel detail, so turns and T-Fittings are easy to read.
- Select a T-Fitting: a node appears in its middle. Drag from the node out to an opening to merge into it, or from an opening into the node to split from it.
- **Tab** still cycles a T-Fitting's flow; the list of six buttons is gone.

## v0.2: Pipe pieces and update notes
- Item pipes are now four pieces: **Straight**, **Left Turn**, **Right Turn** and **T-Fitting**.
- Each piece only takes items where its arrows point in. Big yellow arrows show which way items flow.
- Dragging a line puts turn pieces at the corners for you.
- Select a T-Fitting to set its flow: split one line into two, or merge two into one (**Tab** cycles).
- Pipe lines in existing worlds are converted to the new pieces.
- This "What's new" box now appears after each update.

## v0.1: Land plots
- Every world is 96×96; you start with the middle 32×32.
- Press **P** (or **Land**) to buy the plots next to yours. Each one costs more than the last.
- A banner tells you when a new update is out.
