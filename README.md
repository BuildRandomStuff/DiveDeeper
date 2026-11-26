# DIVE DEEPER

**An underwater survival adventure on the alien ocean world Nerathis-9.** Play it in any modern web browser with keyboard and mouse, or in **VR on a Meta Quest** using Gorilla Tag–style arm movement. Up to 8 players can dive together.

Your colony ship, the *Odyssey-7*, falls out of the sky. You escape in a pod and wake up bobbing on an endless sea. Survive, explore a 2.7 km ocean from sunlit reefs to lava trenches, build bases and submarines, uncover what shot you down, and find a way off the planet.

The whole game is a single file, `index.html`. There's nothing to install or build.

![The crashed Odyssey-7](screenshots/odyssey-7.jpg)

| | |
|---|---|
| ![Sunlit reef](screenshots/reef.jpg) | ![Glowing Grand Reef](screenshots/glow-reef.jpg) |
| ![Opening cutscene](screenshots/intro.jpg) | ![Inventory](screenshots/inventory.png) |
| ![Connected habitat](screenshots/habitat.jpg) | ![Gloomwater Rift](screenshots/gloomwater-rift.jpg) |
| ![Behemoth Carrier](screenshots/behemoth.jpg) | ![Behemoth bridge](screenshots/behemoth-bridge.jpg) |
| ![Rocket tower and gantry](screenshots/rocket-tower.jpg) | ![Rocket cockpit](screenshots/rocket-cockpit.jpg) |

---

## Contents

1. [How to play it](#1-how-to-play-it)
2. [Controls](#2-controls)
3. [Starting out](#3-starting-out)
4. [Game modes](#4-game-modes)
5. [Survival](#5-survival)
6. [The story](#6-the-story-and-how-to-beat-the-game)
7. [The world and its biomes](#7-the-world-and-its-biomes)
8. [Creatures](#8-creatures)
9. [Resources](#9-resources)
10. [Inventory and the PDA](#10-inventory-and-the-pda)
11. [Crafting](#11-crafting)
12. [Blueprints and scanning](#12-blueprints-and-scanning)
13. [Tools](#13-tools)
14. [Equipment](#14-equipment)
15. [Building bases](#15-building-bases)
16. [Vehicles](#16-vehicles)
17. [The Odyssey-7](#17-the-odyssey-7)
18. [The escape rocket](#18-the-escape-rocket)
19. [Day and night](#19-day-and-night)
20. [Multiplayer](#20-multiplayer)
21. [VR on Meta Quest](#21-vr-on-meta-quest)
22. [Tips](#22-tips)
23. [Technical notes](#23-technical-notes)
24. [Put it on GitHub](#24-put-it-on-github)

---

## 1. How to play it

**In a browser:** open `index.html` in Edge, Chrome or Firefox. Double-clicking the file works for keyboard and mouse play.

**Online (needed for VR):** publish it with GitHub Pages (see [section 24](#24-put-it-on-github)) and open the link. On a Meta Quest, open the same link in the Quest Browser and press **Enter VR**. VR only works over **https**, which GitHub Pages provides.

**The main menu** shows a live view of the wrecked Odyssey-7 at sunset. It has these options:
- **Play** (or press Enter): keyboard and mouse.
- **Enter VR**: appears when a headset is detected.
- **How to play**: the controls.
- **About**: the story so far.

**The lobby:** Play takes you to a dive station lobby. Walk to the computer and click its screen to:
- start a single-player game (Survival, Freedom, Hardcore or Creative), or continue your save
- host or join a multiplayer room with a room code
- change your gorilla's name, colour, size and turning style

---

## 2. Controls

### Keyboard and mouse

| Key | Action |
|---|---|
| Click | Lock the mouse and look around (right-drag or the arrow keys also look) |
| W A S D | Swim or walk |
| Space / C | Swim up / down (Space also climbs the pod's ladder) |
| Shift | Sprint (full speed in vehicles) |
| Left mouse (hold) | Use the tool in your hand, or punch with bare hands |
| Right mouse | Cancel placement · Titan grapple · Behemoth sonar |
| 1–8, Q, mouse wheel | Choose a tool |
| E | Interact, and enter or leave vehicles |
| I | Inventory |
| Tab | PDA (inventory, status, crafting, building, logbook) |
| F | Helmet lamp on or off |
| B | Swap a vehicle's power cell, or install a cell in the Behemoth |
| R | Rotate a building piece while placing it |
| Esc | Cancel or close |
| Space / Enter / click | Skip the opening cutscene |

### Meta Quest (VR)

| Control | Action |
|---|---|
| Your arms | Move like Gorilla Tag: slap the ground or walls and push off to run and jump |
| Arm strokes | Swim through the water |
| Punching | Break resources with your fists |
| Right stick | Turn (snap or smooth, chosen in the lobby) |
| Right trigger | Use the tool in your hand |
| A / B | Next / previous tool (B also cancels placement) |
| X | PDA |
| Y | Interact, and enter or leave vehicles |
| Left stick click | Helmet lamp |
| Any button | Skip the opening cutscene |

### Vehicle controls

| Vehicle | Keyboard and mouse | VR |
|---|---|---|
| **Manta Scout** | WASD + mouse, Space / C up and down, left click fires sonar, E exits | Left stick move, right stick turn and rise, Y exits |
| **Titan Exosuit** | WASD walk, mouse turn, Space jets, left click drill, right click / G grapple, E exits | Left stick walk, right stick turn, A or grip jets, left trigger drill, right trigger grapple, Y exits |
| **Behemoth Carrier** | WASD + mouse, Space / C up and down, Shift full speed, left click torpedo, right click sonar, B installs a cell, E leaves the helm | Left stick move, right stick turn and rise, right trigger torpedo, A sonar, Y leaves |

---

## 3. Starting out

A new game opens with a cutscene. At dawn the Odyssey-7 falls burning out of the sky, the escape pods launch, and yours splashes down while the ship crashes on the horizon. Skip it any time.

You wake up inside **Escape Pod 3**. You start with **no tools**, just two Survival Food Packs and two bottles of water.

**Your first steps:**
1. Drop through the hatch in the pod's floor.
2. **Punch the glowing reef nodules** (hold left click) for titanium and copper. Every resource type has its own colour and glowing ore, and nearby ones shimmer.
3. Back in the pod, use the **fabricator** to craft a **Salvage Knife** (titanium + copper). It breaks things twice as fast as your fists.
4. Craft a **Patch Welder** and weld the pod's **three sparking leaks**. This brings the pod radio back online.

The shallow reef within **150 m of the pod is a safe zone**: no predators spawn there, and anything hunting you turns back at its edge.

The **objective** at the top of the screen (and at the bottom of the PDA) always tells you what to do next.

---

## 4. Game modes

| Mode | Food and water | Damage | Oxygen | Notes |
|---|---|---|---|---|
| **Survival** | Yes | Yes | Yes | The full experience |
| **Freedom** | No | Yes | Yes | No hunger or thirst |
| **Hardcore** | Yes | Yes | Yes | One life: dying deletes your save |
| **Creative** | No | No | No | Everything is free, all tools unlocked, nothing can hurt you |

---

## 5. Survival

- **Oxygen:** you lose air underwater and refill it at the surface, in the pod, in a habitat, in the Vehicle Bay or aboard the Behemoth. Bigger tanks hold more air (75, 135 or 210 seconds).
- **Health:** it slowly regenerates while you're fed and watered. Medical Injectors restore 50.
- **Food and water:** both drain over time. Eat cooked fish, melons or food packs, and drink purified water (made from salt).
- **Depth:** every suit has a safe depth. Go deeper and the pressure hurts you. The HUD shows your depth and current limit.
- **Hazards:**
  - **Radiation** near the Odyssey-7 debris, and around the ship after it explodes: wear a Radiation Suit.
  - **Extreme heat** in the Furnace Abyss: wear a Thermal Dive Suit or use the Titan.
  - **Lava:** don't touch it.
- **The Vyrel bloom:** an alien infection you catch from the Nairathi archive. Each stage lowers your maximum health until you're cured (see the story).
- **Blacking out:** if you die, you wake up back at your pod (or your first habitat room) and lose half your raw materials. In Hardcore, death is permanent.
- **Saving:** the game saves automatically every 90 seconds and when you close the tab. You can also save from the PDA.

---

## 6. The story and how to beat the game

1. **Fix the pod.** Weld its three leaks so the radio can pick up signals.
2. **Find the Odyssey-7 debris field** to the south and read the **Damage Report**. It unlocks the Plasma Cutter.
3. **Craft a Plasma Cutter.** It needs a diamond from dark basalt nodules in the Crimson Grasslands. Cut open the sealed bridge.
4. **Read Captain Varga's final log.** The ship was shot down by a beam from an alien tower. The log unlocks the rocket blueprints and gives you the Navigation Core.
5. **Follow the alien signal** west to the Glowing Grand Reef (about 140 m deep) and touch the **Nairathi archive**. You learn about the Vyrel bloom, and you catch it.
6. **Cut into the Nairathi laboratory** under the dark reef (about 330 m, southwest). You need a Pressure Suit or a Manta with depth modules. Read the second archive and collect the Nairathi Alloy.
7. **Craft the Resonance Key** (2 alloy, 2 kyanite, 1 glow spore).
8. **Open the Mother's sanctum** in the Scarlet Vine Trench (about 480 m, northwest). Approach the **Ancient Mother**: her enzyme cures the bloom and unlocks the **Titan Exosuit**.
9. **Build the Titan** and walk it down to the **Quarantine Spire** in the lava zone (about 760 m, southeast). Release its lock so the sky is open.
10. **Build the Launch Platform** at the surface, build the four rocket stages, then **ride the elevator up, board the capsule and launch.** You escape Nerathis-9.

Along the way, datapads, crew logs and scans fill your **logbook** (the PDA's DATA tab) with the story and blueprints.

---

## 7. The world and its biomes

The ocean is about **2.7 km across**, generated procedurally and loaded in chunks as you move. Past the edge lies **The Void**, an empty abyss where something very large patrols.

| Biome | Depth | Look | Notable |
|---|---|---|---|
| **Sunlit Reef** | ~14 m | Bright sand, coral, sunbeams | Starting area and safe zone; your pod floats here |
| **Vinewood Forest** | ~45 m | Tall green vinegrass | Vine fiber, seed clusters, Vine Stalkers |
| **Wreckfall Expanse** | ~36 m | Grey wreckage | Odyssey-7 debris, fragments, Snapbiters |
| **Crimson Grasslands** | ~62 m | Red grass, vents | Basalt nodules (diamonds), crimson oil, Sand Hunters |
| **Golden Dunes** | ~110 m | Open sand | Sea Giants and the Razorback Leviathan |
| **Glowing Grand Reef** | ~140 m | Giant glowing mushrooms | The Nairathi outpost |
| **Abyssal Grand Reef** | ~330 m | Pitch dark | The Nairathi laboratory, the Phantom Leviathan |
| **Scarlet Vine Trench** | ~480 m | Dead red vines | The Mother's sanctum |
| **Gloomwater Rift** | 700–760 m | Dark green chasm, glowing dead trees | Titan only; sulfur, Gloom Crystals, swarms of hostiles |
| **Furnace Abyss** | ~760 m | Lava, basalt columns | The Quarantine Spire, Magma Cores, the Inferno Leviathan |

Landmarks include your escape pod, the Odyssey-7 main hull (a 250 m spaceship sticking out of the sea), its debris field and sealed bridge, a small island, the Nairathi outpost and lab, the Mother's sanctum and the Quarantine Spire, whose red beam you can see from far away.

---

## 8. Creatures

Scan any creature with the BioScanner to add it to your logbook.

**Fish (food):** fish come in schools.
- **Found almost everywhere:** Bubblefish, Crescentfish, Glimmerfish.
- **Found in only one or two places:** Hoverfish (vine forest, grasslands), Ringfish (grasslands, dunes), Lensfish (glowing reef, abyss, rift) and Lava Eyefish (Furnace Abyss only).
- Catch them with a knife; they give Raw Fish.

**Peaceful:** Reef Ray, Glowray, the six-legged **Walking Sea Giants** of the dunes, and the **Ancient Mother**.

**Hostile:**

| Creature | Where | Danger |
|---|---|---|
| Snapbiter | Reef edges, wreck | Bites, retreats, comes back |
| Vine Stalker | Vinewood Forest | Fast ambusher in the vines |
| Sand Hunter | Grasslands, dunes | Hides in the sand. Watch for little yellow eye-lights |
| Phantom Ray | Glowing reef, rift | Stings anything close |
| Blood Leech | Abyss, trench, rift | Latches on and drains you; knife it off |
| Pulse Squid | Abyss, trench, rift | Electric pulses that drain vehicle power |
| Magma Grub | Furnace Abyss | Heat burst when you get close |
| **Razorback Leviathan** | Golden Dunes | 40 m armoured eel-shark |
| **Phantom Leviathan** | Abyssal reef | Nearly invisible, ambushes subs |
| **Inferno Leviathan** | Furnace Abyss | Magma-skinned giant |

**How hunting works:**
- Once a hostile notices you, it **follows you anywhere**, even across biome borders, until you **outrun it** or reach **shelter**.
- Shelter means the pod, a habitat or a vehicle. Leviathans ignore vehicles and only give up at the pod or a base.
- Small hunters tire out after a long chase.
- Creatures can't get inside the pod, rooms, corridors or the Vehicle Bay.

**Fighting back:**
- A knife drives small predators off.
- The Repulsion Blaster knocks everything away.
- A Creature Decoy distracts leviathans.
- Behemoth torpedoes kill predators and send leviathans fleeing.

---

## 9. Resources

Break resource nodes with your hands, a knife, the Titan's drill or a Plasma Cutter. Each type has its own colour and glow.

| Node | Gives | Found in |
|---|---|---|
| Reef Nodule (blue, orange and silver ore) | Titanium, copper, lead | Reef, wreck, vines |
| Grit Nodule (dark with gold flecks) | Silver, lead, gold | Vines, grasslands, dunes |
| Basalt Nodule (black with violet glints) | Diamond, gold, lithion, magnetite | Grasslands, dunes, glowing reef, abyss |
| Quartz crystals | Quartz | Reef, grasslands, glowing reef |
| Salt deposit | Salt | Reef, grasslands, dunes |
| Kyanite | Kyanite | Abyss, trench, rift, glowing reef |
| Crystal Sulfur | Sulfur | Abyss, trench, Furnace Abyss and lots in the rift |
| Uranium Ore | Uraninite | Abyss, trench, rift, furnace |
| Gloom Crystal | Gloom Crystal | Gloomwater Rift only |
| Magma Core | Magma Core (needs a Plasma Cutter or the Titan's drill) | Furnace Abyss |
| Vinegrass Sprout | Vine fiber (+ seed clusters) | Vines, reef |
| Gel Pod, Crimson Bulb, Glow Cap | Gel pods, crimson oil, glow spores | Vines, grasslands, glowing reef |

Nodes grow back after a few minutes. The Odyssey-7's supply lockers also hold salvage once the ship has exploded.

---

## 10. Inventory and the PDA

Press **I** for the inventory or **Tab** for the PDA. In VR, press X and then pick the INVENTORY tab.

- **INVENTORY:**
  - A grid of slots with an icon and count for each item, holding up to 70 items.
  - Click an item to see what it does, how many recipes use it, and buttons to **Equip**, **Hold in hand**, **Eat / drink**, **Inject**, **Throw** or **Drop**.
  - Your equipped tank, suit, fins, head and extra slots appear underneath.
  - Inside the pod or a habitat, the **Storage** button opens base storage. Materials there are used automatically when you craft nearby.
- **STATUS:** oxygen, health, food, water, base power, vehicle health and power, depth, location, infection, equipment, tool charge, Save and Exit to lobby.
- **CRAFT:** every recipe you know, grouped as Basic, Food & aid, Tools, Gear, Vehicles and Rocket, with what it costs and where to build it.
- **BUILD:** base pieces for the Habitat Architect.
- **DATA:** your logbook of story logs, creature entries and fragment progress.

---

## 11. Crafting

Recipes need the right **station**:
- **Fabricator:** in the pod, any habitat room, or aboard the Behemoth.
- **Gear Workbench:** gear upgrades.
- **Vehicle Bay:** vehicles and modules.
- **Launch Platform:** rocket stages.

**Basic materials (fabricator)**

| Item | Recipe |
|---|---|
| Titanium Ingot | 5 titanium |
| Glass | 2 quartz |
| Enameled Glass | glass + salt |
| Battery | 2 copper + salt |
| Power Cell | 2 batteries + silicone |
| Recharge Power Cell | 1 empty power cell |
| Wiring Kit | 2 silver |
| Silicone | seed cluster |
| Synthetic Fiber | 3 vine fiber |
| Lubricant | crimson oil |
| Plasteel | titanium ingot + 2 lithion |
| Logic Board | wiring + gold + quartz |
| Computer Chip\* | logic board + diamond + gold |
| Lead Plating | 3 lead |
| Reactor Rod\* | 3 uraninite + lead plating + glass |

\*Unlocked by Captain Varga's log.

**Food and aid**

| Item | Recipe |
|---|---|
| Cooked Fish | raw fish |
| Purified Water | 2 salt |
| Survival Food Pack | 2 vine fiber + raw fish |
| Medical Injector | gel pod + salt |
| Creature Decoy | wiring + 2 titanium + glow spore (unlocked by scanning a leviathan) |

Sweet Melons grow in Grow Beds.

**Tools, gear, vehicles and the rocket** are listed in the sections below.

---

## 12. Blueprints and scanning

Many things must be **unlocked before you can build them**:

- **Scan fragments:** glowing wreckage scattered around the world. Hold the **BioScanner** on one until it finishes. Scan enough of one kind to learn its blueprint:

| Blueprint | Fragments needed |
|---|---|
| Habitat Architect | 2 |
| Habitat Room | 2 |
| Observation Dome | 2 |
| Solar Panel | 2 |
| Storage Locker | 1 |
| Grow Bed | 1 |
| AquaGlide | 2 |
| Vehicle Bay | 2 |
| Manta Scout | 3 |
| Gear Workbench | 2 |
| Repulsion Blaster | 2 |
| Behemoth Carrier | 3 (near the Odyssey-7 debris) |

- **Read datapads and logs:**
  - Damage Report: Plasma Cutter.
  - Dr. Lune: Depth Rebreather.
  - Captain Varga: rocket, Computer Chip and Reactor Rod.
  - Nairathi archives: Pressure Suit, Resonance Key and Thermal Suit.
- **Story events:** the Mother unlocks the Titan Exosuit. Scanning a leviathan unlocks the Creature Decoy. Scanning a thermal vent unlocks the Thermal Plant.

Corridors need no blueprint, so you can always connect the rooms you've unlocked.

---

## 13. Tools

| Tool | Recipe | Use |
|---|---|---|
| Bare hands | — | Punch resources (half knife strength) |
| Salvage Knife | titanium + copper | Harvest faster, fight small creatures, catch fish |
| BioScanner | battery + titanium + quartz | Scan creatures, fragments and vents |
| Patch Welder | battery + 2 titanium + copper | Weld the pod's leaks |
| Glow Torch | battery + glass | A handheld spotlight |
| Habitat Architect | 2 batteries + wiring + 3 titanium | Build bases |
| Plasma Cutter | battery + diamond + 2 titanium | Cut sealed doors, break Magma Cores |
| AquaGlide | power cell + lubricant + 2 copper + titanium | Underwater propeller (water only, can't lift you into the air) |
| Repulsion Blaster | power cell + 2 magnetite + titanium ingot | Knock back creatures |

The AquaGlide, Plasma Cutter and Blaster use charge, which refills in the pod or a habitat. A newly crafted tool goes straight into your hand if your hands are empty.

---

## 14. Equipment

| Slot | Items |
|---|---|
| Tank | Standard (75 s) → Extended (135 s, 3 titanium + glass) → Maximum Capacity (210 s, at the Workbench) |
| Suit | Dive Suit (150 m) · Radiation Suit (150 m, radiation-proof) · Reinforced Pressure Suit (350 m) · Thermal Dive Suit (520 m, heat-proof, at the Workbench) |
| Fins | Current Fins (×1.18 speed, 2 silicone) → Velocity Fins (×1.38, at the Workbench) |
| Head | Helmet Lamp (glass + battery + titanium); F toggles it |
| Extra | Depth Rebreather (keeps deep dives from burning through your air) |

---

## 15. Building bases

1. Craft the **Habitat Architect** and hold it.
2. Open the **BUILD** tab, choose a piece and click to place it. **R** rotates it and right-click cancels. The ghost turns green when the spot is valid.
3. **Pieces snap together:** Habitat Rooms have a **doorway on each of their four sides**, and **Corridors** have two ends. Aim a new room or corridor near a free doorway or corridor end and it snaps on. The prompt tells you what it will connect to.
4. Walk through your base: walls are solid, corridors have floors, and every room and corridor has **air**.

| Piece | Cost | What it does |
|---|---|---|
| Habitat Room | 6 titanium + 2 glass | Air, fabricator, storage; you respawn here |
| Corridor | 2 titanium | Joins rooms |
| Observation Dome | 3 titanium + 2 enameled glass | Breathable glass dome |
| Solar Panel | 2 quartz + titanium + copper | Power from sunlight (shallow water) |
| Thermal Plant | 5 titanium + 2 magnetite + wiring | Strong power, within 25 m of a thermal vent |
| Storage Locker | 2 titanium | +40 base storage |
| Grow Bed | 2 titanium + 2 vine fiber | Grows Sweet Melons |
| Gear Workbench | titanium ingot + logic board + diamond | Upgrades gear |
| Vehicle Bay | power cell + 6 titanium + lubricant + 2 glass | Builds, docks, charges and repairs vehicles |
| Launch Platform | 4 titanium ingots + 2 lubricant + plasteel | The escape rocket (floats at the surface) |

**Base power** runs fabricators and refills oxygen and vehicles. Each room adds capacity; solar panels and thermal plants generate it.

---

## 16. Vehicles

All vehicles are built at the **Vehicle Bay** console.

### Manta Scout (small submarine)
- **Recipe:** titanium ingot + power cell + 2 glass + lubricant + 2 lead.
- **Depth:** 200 m. Depth modules MK1 / MK2 / MK3 raise it to 300 / 450 / 600 m.
- **Upgrades:** Sonar Module (200 m ping) and Thermal Plating.
- **Docking:** fly up into the Vehicle Bay's moon pool to dock, charge and repair.
- **View:** when you pilot it, the canopy glass is hidden and you sit just above the hull for a clear view.

### Titan Exosuit (walking diving suit)
- **Recipe:** 2 titanium ingots + 2 plasteel + 2 power cells + 2 lubricant + 2 kyanite + diamond. Unlocked by the Mother.
- **Depth:** 900 m, heat-proof. The **Titan Depth Module** raises it to **1300 m** (2 plasteel, 2 kyanite, 3 Gloom Crystals, 2 sulfur).
- **Equipment:** a drill that breaks anything (including Magma Cores), jump jets, and a grapple arm for climbing out of trenches.
- **Gloomwater Rift:** this is the only way to reach it.

### Behemoth Carrier (giant submarine)
A **52 m reactor-powered submarine**, the biggest and fastest vehicle in the game.
- **Unlock and build:** scan 3 Behemoth fragments, then build it at the Vehicle Bay (6 titanium ingots, 4 plasteel, 3 enameled glass, 3 lubricant, computer chip, reactor rod). It appears just outside the bay.
- **Power:** it needs **at least 6 Power Cells** installed to move, and holds up to 8. Install them with **B** or from the hatch prompt.
- **Reactor:** load **Reactor Rods** into its reactor, which keeps the cells topped up as you travel.
- **Speed and depth:** about 24 m/s cruising, **38 m/s at full speed (Shift)**, crush depth 1000 m.
- **Weapons:** **torpedoes** (left click) fire from twin tubes and converge ahead of you. They kill predators and send leviathans fleeing. Craft them at a fabricator: titanium + sulfur + copper makes 2.
- **Sonar:** right click pings everything within 200 m.
- **On board:** air and a working fabricator.
- **Bridge:** a huge glass dome gives a wide view of the ocean.

### Power cells
When the Manta, Titan or Behemoth runs low:
- Press **B** (or take the "Swap power cell" prompt in VR) to put in a fresh **Power Cell** from your inventory.
- The drained cell becomes an **Empty Power Cell**. Recharge it at a fabricator.
- The HUD warns you when vehicle power drops below 25%.

---

## 17. The Odyssey-7

Your colony ship, a 250 m spaceship, crash-landed about 550 m from your pod. Half of it sticks out of the sea and it's already damaged: a torn-off engine pod, a broken wing and burning holes.

**Its reactor melts down 15 minutes into a new game.** The HUD counts down, with warnings at 5 minutes and 1 minute and a final 30-second countdown.
- The explosion is a huge fireball and shockwave. Get at least 300 m away or into shelter.
- Afterwards the starboard side of the cargo hold is torn open below the waterline. The water around the ship is **radioactive**, and the hold is **lethal without a Radiation Suit**.
- Inside you'll find **5 supply lockers** with salvage (including a Maximum Capacity Tank and a Reactor Rod) and two logbook entries.

---

## 18. The escape rocket

1. Place the **Launch Platform** at the surface with the Habitat Architect.
2. Climb onto it from the water (interact near its edge).
3. Build the four stages at the platform:

| Stage | Recipe |
|---|---|
| Engine | magma core + 2 titanium ingots + 2 lubricant |
| Fuel Core | 2 reactor rods + 4 sulfur + 2 lithion |
| Hull | 3 plasteel + 2 lead plating + 2 enameled glass |
| Navigation | 2 computer chips + navigation core + 2 kyanite |

4. Take the **elevator** up the tower, cross the **gantry**, and **climb into the capsule**.
5. Press **LAUNCH THE ROCKET** on the cockpit console. This only works once the Spire's quarantine is released. You ride the rocket into the sky.

---

## 19. Day and night

- A full day lasts **15 minutes**. The sun rises and sets, and nights are dark with a starry sky.
- Underwater, the light fades after sunset, so bring a lamp or torch.
- The HUD shows the day and time.
- Lamps and headlights are dimmed in bright shallow water and matter most in the dark.

---

## 20. Multiplayer

From the lobby computer, choose **Host** to create a room with a code, or **Join** and type a friend's code. Up to **8 players** can play together.

- The host chooses the mode, starts the dive, and can use their saved world.
- Shared progress: base pieces, story doors and gates, pod repairs, rocket stages, the launch and the Odyssey-7 explosion.
- Everyone sees each other's gorilla avatars and vehicles (Manta, Titan and Behemoth), whether piloted or parked.
- Online rooms use PeerJS (loaded from a CDN, so you need internet). Two tabs on the same computer can also connect locally.

---

## 21. VR on Meta Quest

- Movement works like Gorilla Tag. There's no joystick: your hands are solid. Slap the seabed, rocks or walls and push to move, and push off hard then let go to launch yourself. In water, pull strokes to swim. You're slightly buoyant and float at the surface.
- Choose your gorilla's name, colour, size (small, normal or big) and turning style (snap or smooth) in the lobby.
- The opening cutscene plays in VR too, with floating captions. Press any button to skip it.
- The PDA appears as a tablet in front of you. Point and pull the trigger to use it.
- Your hands and tools show in VR, and other players see your arm movements.

---

## 22. Tips

- Use the **glowing shimmer** to spot resources: rocks don't shimmer, nodes do.
- **Craft the knife first.** Fists are slow.
- **Fix the pod before you explore far.** The radio leads you to everything else.
- **Leave the Odyssey-7 area before the 15-minute meltdown,** and come back later in a Radiation Suit for the loot.
- **Store raw materials** in the pod or a habitat. Crafting nearby uses them automatically, and you only lose half of what you carry when you black out.
- **Carry a spare Power Cell** in every vehicle trip and press B when power runs low.
- **Outrun or shelter:** if something big is chasing you, head for the pod, a base or the safe reef.
- **Decoys and the Repulsion Blaster** save lives around leviathans. In the Behemoth, use torpedoes.
- **Bring light at night,** and a lot of it in the abyss and the rift.

---

## 23. Technical notes

- **One file:** the whole game is `index.html`, written in plain JavaScript with a custom **WebGL2** renderer. It uses no game engine and no image files: every model is generated in code.
- **Graphics:** physically inspired lighting, animated caustics, sunbeams, a reflective and refracting water surface, colour-dependent underwater fog, bloom, colour grading and a day/night sky with stars.
- **Audio:** all sounds are synthesized live with the Web Audio API.
- **Saving:** saves are stored in your browser's local storage under `diveDeeper.save.v3`.
- **Requirements:** a browser with WebGL2 (any modern desktop browser or the Quest Browser). WebXR is needed for VR.
- **Windows high contrast:** the game ignores the Windows high-contrast theme so its colours always look as designed.

---

## 24. Put it on GitHub

1. Create a new repository on GitHub, for example `dive-deeper`, and make it **Public**.
2. Click **Add file → Upload files** and drag in `index.html`, `README.md` and the `screenshots` folder. Then click **Commit changes**.
3. Go to **Settings → Pages**. Set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, then click **Save**.
4. About a minute later the game is live at `https://<your-username>.github.io/dive-deeper/`.

There is no license file yet. If you want others to be able to reuse the code, add one with **Add file → Create new file**, named `LICENSE`; GitHub suggests common licenses.
