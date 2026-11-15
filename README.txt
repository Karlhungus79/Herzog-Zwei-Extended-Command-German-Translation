==============================================================================
  HERZOG ZWEI  -  EXTENDED COMMAND
  Enhancement patch for the Sega Mega Drive - English and German version
  Erweiterungs-Patch für das Sega Mega Drive - englische und deutsche Fassung
==============================================================================

Version / Stand: 1.0 (15.11.2026)
Project / Projekt: Karlhungus / RGB Retro Gaming
                   https://www.youtube.com/@rgbretrogaming
                   rgbretrogaming@protonmail.com

CONTENTS
------------------------------------------------------------------------------
  1. What is EXTENDED COMMAND?
  2. Requirements and installation
  3. All new features at a glance
  4. Translation
  5. HELP / HILFE: the in-game manual
  6. OPTIONS / OPTIONEN: start menu and pause menu
  7. Radar on screen
  8. Better pathfinding for your units
  9. New title screen and music selection
 10. Extra maps and large maps
 11. The extra maps in detail
 12. Notes, limitations, known issues
 13. Tested on
 14. Credits and legal


==============================================================================
1. WHAT IS EXTENDED COMMAND?
==============================================================================

Herzog Zwei (Technosoft, 1989) is one of the first real-time strategy games
ever made: you steer a transforming jet, buy units, give them orders and
capture bases until the enemy main base falls.

EXTENDED COMMAND adds improvements that make the game more comfortable, more
flexible and much more varied. It comes as two patches:

  * English version: original English game texts, all new menus and
    features in English.
  * German version (Deutsch): the complete game translated into German.

Features:

  * German version: fully German menus, messages, unit and order names,
    result screen, story and ending
  * a manual inside the game (HELP / HILFE)
  * an options menu with 19 settings, set separately for player 1 and 2
  * a pause menu that is the options menu (START during the game)
  * a permanent radar on screen (full-screen mode)
  * much better pathfinding for your units
  * 12 additional maps (some of them large maps), selectable by page
  * a single-player campaign over all 20 maps, each in TYPE A-D, with a
    24-letter password
  * music selection after choosing a map
  * a new title screen

Every new feature is optional or defaults to the original behaviour. The 8
original maps stay playable and unchanged.


==============================================================================
2. REQUIREMENTS AND INSTALLATION
==============================================================================

You need:

  * The original game "Herzog Zwei (USA, Europe)" as a ROM image
    (524288 bytes = 512 KB). The ROM is NOT part of this download.
  * An IPS patcher, e.g. Lunar IPS, Floating IPS (Flips) or an online patcher.
  * An emulator or a flash cartridge (see below).

Installation:

  1. Copy your original ROM and rename the copy, e.g. to
     "Herzog Zwei - Extended Command.md".
  2. Apply ONE of the two patches to the COPY:
       "Herzog Zwei - Extended Command (English).ips"   English version
       "Herzog Zwei - Extended Command (Deutsch).ips"   German version
  3. Done. The patched ROM is 2 MB (2097152 bytes). The patch corrects the
     header checksum.

Checksums
  Original ROM (input):      CRC32 A605B65B
                             MD5   e812002daafb264fc2ab1dff9bd06ac2
  Patched, English version:  CRC32 1F11C2F8
  Patched, German version:   CRC32 B2E46B04

IMPORTANT - ROM size:
Because of the many additions (pathfinding data, extra maps, options menu)
the ROM grows from 512 KB to 2 MB. This is addressable without bank
switching (mapper). On real hardware you therefore need a flash cartridge
such as the Everdrive, or a cartridge with a larger memory chip (at least
16 Mbit). An original-size 4 Mbit cartridge is not enough.

Emulators: developed and tested with Genesis Plus GX and Ares. Other accurate
emulators should work as well.

The patch is made for exactly one ROM version (USA/Europe). Other versions
(e.g. Japan) are not supported.


==============================================================================
3. ALL NEW FEATURES AT A GLANCE
==============================================================================

  Translation (German version)
    - Start menu, sub-menus, messages, all 18 music titles
    - Buy menu with lower case, umlauts and punctuation
    - German names for all 8 units and all 7 orders
    - Red buy-menu counter reads "ANZ" instead of "UNIT"
    - Result screen, both story endings and the headings of the ending

  English version
    - Original English game texts; readable unit and order names in the
      buy menu (CAR, TANK, ... STAY, PATROL, ...)
    - All new menus in English: HELP, OPTIONS, "Select the music",
      "Select the difficulty", "Page 1 of 3"

  Comfort
    - HELP / HILFE: 5-page manual inside the game, with the buy-menu icons
    - OPTIONS / OPTIONEN: 19 settings, separate for player 1 and player 2
    - Options also reachable during the game with START (pause menu)
    - Radar on screen (overview map or close range)
    - Transformer speed x2 (with a camera fix against graphics glitches)
    - Rapid fire (hold B)
    - New unit pathfinding ("Pathfinding new / old")
    - Music selection after choosing a map: any of the 8 map songs
      (preselected: the map's own song; Up/Down plays it as a preview)
    - Hint texts for TYPE A-D and the music selection

  Content
    - 12 extra maps on pages 2 and 3 of the map selection (20 maps in total)
    - Single-player campaign over all 20 maps (TYPE A-D each); the ending
      only comes when everything is won; 24-letter password
    - Large maps: 64x96 (portrait) and 128x48 (landscape)
    - New map pieces: wooden and steel bridges, lava, ice, city, and more
    - Five maps with completely new, hand-drawn graphics
    - New title screen with the EXTENDED COMMAND logo
    - EXTENDED COMMAND entry in the ending credits


==============================================================================
4. TRANSLATION
==============================================================================

English version
  All texts of the original game stay as they are (menus, music titles,
  result screen, story, ending). The new features use English texts. In
  the buy menu the units and orders have readable names (CAR, TANK, SAM,
  GUNBOAT, TRUCK, CANNON, INFANTRY, BIKE; STAY, PATROL, ATTACK, DEFEND,
  OCCUPY, HOME ATK, SUPPLY). The map names are the original German map
  names of the game; the extra maps follow that style.

The rest of this section describes the German version.

Menus and messages
  The whole start menu is German: START, WEITER, SPIELER, MUSIK, SOUND,
  BILDSCHIRM (split screen / full screen), Mensch / Computer, PASSWORT,
  TYP A to D, plus the messages PASSWORT FALSCH and RICHTIG.
  The menu font now has the letters ä ö ü Ä Ö Ü ß and a comma. The blue
  start-menu box is one column wider so that the German words fit.
  All 18 music titles are translated.

Units (buy menu)
  AMR   Panzerwagen   (armoured car)
  TAX   Kampfpanzer   (battle tank)
  SAM   Flugabwehr    (anti-aircraft)
  ST    Kanonenboot   (gunboat)
  SUP   Versorger     (supply truck)
  GRM   B/L-Geschütz  (ground/air gun)
  INF   Fußsoldat     (infantry)
  FWA   Motorrad      (motorbike)

Orders
  Halten, Patrouille, Besetzen, Abwehr, Vorrücken, Basis Angriff, Versorgung
  (hold, patrol, occupy, defend, advance, attack base, supply)

Buy menu
  The in-game font was extended with lower case, umlauts and punctuation.
  Only 13 characters per name fit in the buy menu, which is why three names
  are shortened (Versorger, B/L-Geschütz, Halten). The manual (HILFE) shows
  the full names. The red counter at the bottom now reads "ANZ" (Anzahl)
  instead of "UNIT".

Map names
  The map selection prints names with the menu font, so umlauts work there
  (for example SÜDSEE). Names are upper case only.

Ending: result screen, story and credits
  The result screen is German: SIEGER, SPIELER 1/2, ZEIT, MENSCH or COM,
  BASEN, EINHEIT, LEBEN (lives = transformers used), PASSWORT. Both endings
  (LUDWIG wins or loses) are fully translated, as are the headings of the
  credits (the names stay). The story font got ä ö ü Ä Ö Ü ß, colon,
  question mark and hyphen.


==============================================================================
5. HELP / HILFE: THE IN-GAME MANUAL
==============================================================================

The start menu has a new entry HELP (German version: HILFE). It opens a
manual with 5 pages:

  Page 1    How to read the buy menu
  Page 2-3  The units (with their icons from the buy menu)
  Page 4-5  The orders (with their icons from the buy menu)

Controls: Left/Right turns the page (wrapping from the last page to the first
one), B goes back to the start menu. The cursor and all settings are kept.


==============================================================================
6. OPTIONS / OPTIONEN: START MENU AND PAUSE MENU
==============================================================================

Where?
  * In the start menu: entry OPTIONS / OPTIONEN (below HELP / HILFE).
  * During the game: START opens the options menu instead of the original
    pause. Game time stands still and the sound is paused. Both controllers
    can operate the menu. It works in full-screen and split-screen mode.

Controls
  Up/Down        select a row
  Left/Right     select a column (player 1 red / player 2 blue)
  A or C         switch to the next value
  B or START     go back

Every setting applies separately to player 1 and player 2, no matter whether
a human or the computer plays that side. You can give yourself advantages or
weaken or strengthen the computer opponent. The default everywhere is the
original behaviour (except "Pathfinding", see below). The
settings are kept when you return to the start menu and when you restart a
game. They are not stored in the password and are reset when the console is
switched off.

The table uses the row names and values exactly as they appear in the game
(English version). The German version shows the German names, given here in
brackets.

General
  Income        1x / 2x / 4x            money income over time
                                        (German: Einkommen)
  Build time    1x / 2x / instant       time until bought units are ready
                                        (German: Bauzeit; sofort)
  Base B        normal / double / unlimited
                                        energy of the main base
                                        (German: Basis B; doppelt, unendlich;
                                        double = half damage)

Transformer (your jet)
  Armor D       normal / double / unlimited       armour
  Ammo G        normal / double / unlimited       ammunition
  Fuel E        normal / double / unlimited       fuel
                ("double" means half damage or half consumption; the gauge
                bars stay correct. "unlimited" = infinite)
                (German: Panzerung D, Munition G, Treibstoff E)
  Repair D      normal / double / instant         repair
  Reload G      normal / double / instant         reload
  Refuel E      normal / double / instant         refuel
                ("double" = twice as fast, "instant" = full immediately)
                (German: Reparatur D, Nachladen G, Auftanken E;
                doppelt so schnell, sofort)
  Rapid fire    off / on
                hold B for about 10 shots per second
                (German: Dauerfeuer; aus / an)
  Speed         normal / double
                double top speed in all modes (robot, flight, carrying a
                unit). Shot speed and camera are adjusted so that the map
                is still drawn cleanly during fast flight.
                (German: Tempo)

Units
  Armor D       normal / double / unlimited       armour
  Fuel E        normal / double / unlimited       fuel
  Ammo G        normal / double / unlimited       ammunition
  Missiles M    normal / double / unlimited       missiles
  Speed         normal / double
  Cost          on / off (off = units cost nothing)
                (German: Panzerung D, Treibstoff E, Munition G, Raketen M,
                Tempo, Kosten; an / aus)

Further rows
  Radar wide view   off / on    (German: Radar im Vollbild, see section 7)
  Pathfinding       new / old   (German: Routenwahl; neu / alt, see section 8)

Note: the computer removes its own surplus infantry by itself. That is not
combat damage and "unlimited" does not prevent it.


==============================================================================
7. RADAR ON SCREEN
==============================================================================

In the original game the radar is only visible in the buy menu. With the
option "Radar wide view" ("Radar im Vollbild", OPTIONS, per player) it
appears permanently in the bottom left corner of the game screen, even
while the buy menu is closed.

  * Two modes, just like in the buy menu: overview map (with bases and both
    transformers) or close range (with units). You switch in the buy menu:
    put the cursor on RADAR and press Left/Right.
  * It hides when the buy menu or the pause menu opens and comes back
    afterwards.
  * Full-screen mode only. In split-screen mode there is no free space for
    it; the option row is named "Radar wide view" for that reason.
  * Available on all extra and large maps.
  * Default: off.

The radar was built so that no graphics errors appear over bases and the
"occupied" markers of small side bases do not lie on top of it.


==============================================================================
8. BETTER PATHFINDING FOR YOUR UNITS
==============================================================================

The problem in the original
  Units drive straight towards their target. When they hit an obstacle they
  stop, turn randomly and try again. They get stuck in every bay and behind
  every rock ridge, and this is even more noticeable on the new maps with
  bays, bridges and chokepoints.

The solution: pathfinding "new" ("neu")
  For every map and every target (all bases and both main bases) a
  precomputed path field is stored in the ROM. Units follow the shortest way
  around obstacles, slopes and lava. In detail:

  * The real footprint is used (vehicles 3x3 tiles, infantry and motorbike
    2x2).
  * Units slide along obstacles instead of stopping.
  * In sharp turns they turn on the spot (not on slopes or ice).
  * Behind other units they wait for a moment before they steer around.
  * A chosen target is kept as long as it can be taken and no other target is
    clearly closer.
  * Applies to the orders ATTACK, OCCUPY and HOME ATK (German: Besetzen,
    Vorrücken, Basis Angriff).

Measurement (2x32 test units per map, 16 maps, 11 Nov. 2026)
  Arrived on time at the target: original 74 %  ->  new 96 %.
  Examples: LOCH 38 % -> 95 %, FLUSS 59 % -> 98 %, EISWERK 67 % -> 98 %,
  GLUT 62 % -> 92 %.

Switch
  OPTIONS, row "Pathfinding" ("Routenwahl"), per player: "new" (default) or
  "old" (original behaviour). This also applies to the units of the
  computer.

Unchanged
  Gunboats, the orders STAY, PATROL, DEFEND and SUPPLY, behaviour
  in combat (enemy in sight) and the transformer.

Limits
  Many units still jam in narrow passages. On OASE the trees slow units down.
  On ABGRUND and KLAMM units that end up on a steep slope slide down and can
  get stuck below. On island maps a target that cannot be reached over land
  stays unreachable.


==============================================================================
9. NEW TITLE SCREEN AND MUSIC SELECTION
==============================================================================

Title screen
  Between the Herzog Zwei logo and "(C) Techno Soft" there is now the
  EXTENDED COMMAND lettering in chrome blue. It fades in together with the
  copyright line.

Music selection
  After the map selection (and after TYPE A-D in a game against the
  computer) a window "Select the music" opens. It lists the 8 map songs as
  "1. Title (MAP)". The song of the chosen map is preselected; Up/Down
  selects a song and plays it at once as a preview. A or C starts the game
  with that song, B goes back to the map selection. The choice applies to
  this one game only. With two players both controllers can operate it.
  The TYPE A-D selection now shows the hint "Select the difficulty".


==============================================================================
10. EXTRA MAPS AND LARGE MAPS
==============================================================================

Selection
  In the map selection you page through the maps with Left/Right, 8 maps per
  page. Page 1 contains the 8 original maps, pages 2 and 3 contain the extra
  maps (8 on page 2, 4 on page 3). The footer reads e.g. "Page 1 of 3"
  ("Seite 1 von 3" in the German version).
  Behind the names there is ABCD as on page 1 (for extra maps this is only a
  label; they are not marked as completed). Preview, radar, bases and start
  formation come from the selected map. Page 3 still has four free rows.

Tile set and rules
  Every extra map uses the graphics, colours, music, buy menu and rules of
  one of the 8 original slots. Consequences:
  * Gunboats exist only on maps that use the STRAND, EISFREI or OASE tile set.
  * On maps with the ABGRUND tile set all bases are neutral.
  Some maps mix two landscapes and have their own colour palette and the
  music of another map.

Large maps
  Extra maps may be larger than the usual 64x64 fields:
    64x96    portrait
    128x48   landscape
  That is 1.5 times the area. The console's work RAM allows no more. Radar
  and map preview show the whole map scaled down. On large maps the computer
  needs longer until its first conquests.

Single player: campaign over all 20 maps
  In a game against the computer the extra maps are part of the campaign,
  just like the 8 original maps. Every map has to be won in all four
  difficulty types (TYPE A, B, C and D) - 80 wins in total. The ending only
  comes after the last of them.
  * Map selection: won types light up grey behind the map name (ABCD), as
    on page 1. A map won in all four types is grey and can no longer be
    selected; pages without a selectable map are skipped.
  * TYPE A-D: already won types are grey and cannot be selected.
  * Password: after every win the result screen shows a password with 24
    letters (A to P), written in six groups of four. It stores the progress
    of all 20 maps in all four types.
  * Continue: start menu, CONT (German version: WEITER). The last password
    is already filled in while the console stays on (also after a reset),
    so A or C on END is enough. Up/Down
    moves to the next/previous letter of the password, Left/Right selects a
    letter from the row below, A or C enters it (or checks the password on
    END), B goes back.
  * The 24 letters contain a checksum: a typing error is reported as
    PASSWORD ERROR instead of loading a wrong progress.
  * Passwords from the original game (11 letters) are no longer valid.

Own map pieces
  For the extra maps additional map pieces were built that do not exist in
  the original maps: wooden and steel bridges (over water and over land),
  copies of lava, city and snow pieces from other maps, own shores and
  beaches, and fully hand-drawn pixel graphics.

Five maps (PLATINE, ORBIT, FLIPPER, WILDNIS and SÜDSEE) do not use any
terrain from the game at all but fully own graphics, see below.


==============================================================================
11. THE EXTRA MAPS IN DETAIL
==============================================================================

Page 2
------
MAUER (64x64, tile set LOCH)
  A diagonal wall splits the map; two gates are the only ways through. It
  started as a test map and is a good introduction to the extra maps. The
  wall is visible on the radar. 8 bases.

FLUSS (64x64, OASE)
  A wide river separates the main bases. From each base a side arm leads
  right up to the base so that gunboats can reach it. A wooden bridge leads
  from the north bank across an island with a neutral base to the south
  bank. Boats cannot pass under the bridge; for boats it acts like a dam.

BASTION (64x64, WALDUNG, no water)
  A diamond-shaped fortress made of four forest bastions in the centre, four
  gates between them that meet in a crossroads at the neutral central base.
  In front of two corners lies a rock barrier with a narrow gate and behind
  it a basin with a neutral base. Three routes lead between the main bases:
  through the fortress or through the lanes next to it. The map is point
  symmetric, so both sides have equal chances.

EISWERK (64x96 portrait, EISFREI + STADT)
  On the left a piece of real city with platforms, pipes and halls; a
  snowstorm blows across the pavement into the ice land on the right, where
  frozen ponds lie (ice can be walked on). A river runs from north to south
  through the middle; in a basin with a round ice floe lies a neutral base
  that cannot be reached from the ground. Two steel bridges in the north and
  south are the only ground routes across the river. Player 1 (red) starts
  bottom left in the city, the opponent (blue) top right in the snow.
  9 bases, point symmetric.

PLATINE (64x64, completely new graphics; rules and music of STADT)
  The battle on the main board of a Mega Drive. This map uses no terrain
  from the game: circuit board, traces, solder pads, chips, capacitors,
  shielding cans and the silkscreen print are newly drawn. Chips and
  capacitors are obstacles; traces, resistors and printed text are not. In
  the middle lies the courtyard between the CPU (MC68000, north) and the
  cartridge slot (south) with a neutral base; you can only enter from west
  and east. Two more neutral bases lie in the free corners (north-west,
  south-east), one each at the west and east edge. Player 1 (red) starts
  bottom left, the opponent (blue) top right; the map is point symmetric.
  Two LEDs blink near the main bases. No gunboats. 9 bases.

SANDUHR (64x96 portrait, OASE)
  A lake in the shape of an hourglass with a dam in an S-curve, two shore
  paths and two islands (the islands are free land without bases).
  9 bases, point symmetric.

KLAMM (128x48 landscape, ABGRUND)
  Two winding rivers with two fords each divide the map into home west,
  contested centre and home east. All 10 bases are neutral, as on ABGRUND,
  and point symmetric.

GLUT (64x96 portrait, OASE + VULKAN)
  The mixed map. In the north (opponent, blue) real VULKAN terrain with
  bubbling lava lakes, small lava veins in red rock, a lava stream with
  three fords and three volcano craters. Lava can be driven on but damages
  ground troops (an armoured car is destroyed in under a second). In the
  south (player 1, red) lies an oasis with many trees, lakes and a small
  beach, with a slow transition from rock to soil in between. Own colour
  palette; the music of VULKAN plays. 9 bases, point symmetric.

Page 3
------
ORBIT (64x64, completely new graphics; rules and music of LOCH)
  The battle on the space station DS9. Like PLATINE, this map uses no terrain
  from the game: decks, walkways, solar panels, radiators, domes, antennas,
  tanks and containers are newly drawn, surrounded by space with stars, an
  ice giant with a ring and a satellite. Space blocks ground troops: they can
  only get from deck to deck over the walkways. Eight decks form a ring; in
  the middle sits the octagonal core with a neutral base, reachable via four
  spokes. Player 1 (red) starts bottom left, the opponent (blue) top right.
  9 bases, point symmetric. Domes, antennas and the position lights of the
  walkways pulse.

FLIPPER (64x64, completely new graphics; rules and music of ABGRUND)
  The battle on a pinball table. The table has two ends (head to head):
  wooden playfield, frame, flippers, slingshots, bumper towers, target
  banks, ramps, a plunger lane with spring and ball are all newly drawn.
  Each main base stands in the outlane of its end; player 1 (red) at the
  bottom, the opponent (blue) at the top. A centre post stands between the
  flipper tips: for ground troops the middle is closed, the way to the main
  base leads around the outside, past the flippers through the outlanes.
  7 bases, all neutral, both halves exactly identical. The main bases are
  closer together than on other maps, so games are faster. Bumpers, lamps,
  ramp arrows and flipper rubbers blink.

WILDNIS (64x64, completely new graphics; rules and music of WALDUNG)
  The battle in a river valley. Everything is nature this time: a river
  leaves the gorge of a rock massif in the north-west, splits around an
  island with a stone circle in the middle of the map and ends in a lake with
  water lilies in the south-east. Dense deciduous and conifer forest, rock
  ribs, boulders, flower meadows and dirt tracks. Water, rock, forest and
  boulders block ground troops. The river can only be crossed in three
  places: the ford in the north-west, the two wooden bridges of the island
  (the central base stands there) and the ford in the south-east. Player 1
  (red) starts bottom left, the opponent (blue) top right. 9 bases, point
  symmetric; at each ford a neutral base stands on both banks. Waves and
  spray sparkle, the campfire flickers.

SÜDSEE (64x64, completely new graphics; rules and music of STRAND)
  The battle in the South Pacific. A ring atoll with bright sand beach,
  palms, jungle and straw huts lies in the turquoise sea. In the lagoon lies
  an island with the central base and a circle of tikis; two long wooden
  jetties lead across from the ring. The ring is open in the north and south,
  where a small island each can be reached over wooden bridges. In the
  north-west corner stands a volcano with a lava lake and lava stream, in the
  south-east corner a jungle island with a shipwreck and SOS on the beach.
  Water, palms, jungle, huts and rock block ground troops; gunboats sail on
  sea and lagoon. Player 1 (red) starts on the left, the opponent (blue) on
  the right. 7 bases, point symmetric. Water and lava sparkle.

Graphics style of WILDNIS and SÜDSEE
  Both nature maps were redrawn on 14 Nov. 2026 in a second, more detailed
  style: patterned instead of flat areas, irregular shores and edges, closed
  tree canopies, large palms with fronds and shadows, rock walls with a lit
  edge, basalt slabs, plank jetties with railings, straw huts and carved
  tikis. The layout, blocked fields, bases and starting units are unchanged.


==============================================================================
12. NOTES, LIMITATIONS, KNOWN ISSUES
==============================================================================

  * The patched ROM is 2 MB. On original hardware you need a flash cartridge
    (e.g. Everdrive). More maps would let it grow up to 4 MB, the limit
    without a mapper.
  * German version: SOUND and END stay English (the boxes are too small for
    German words); the names in the ending credits stay unchanged. The
    result screen (big font) has no umlauts.
  * Umlauts are missing in the yellow titles. In the map selection umlauts
    work, but only as capital letters.
  * The options are not stored in the password.
  * "Radar wide view" works in full-screen mode only, not in split screen.
  * In the close-range radar a short stutter can rarely occur with very many
    units.
  * Passwords of the original game (11 letters) are not valid any more;
    the campaign uses 24-letter passwords.
  * After B in the TYPE selection the right edge of the TYPE box stays
    visible next to the map list until the next screen (as before).
  * The extra maps have only few resources for graphics tiles. That limits
    how much variety a map can offer.
  * The computer AI conquers late on very large maps. On island maps the
    pathfinding changes little.
  * Gunboats and units affected by gunboat orders keep using the original
    steering logic.
  * On GLUT and SÜDSEE some units still arrive late at certain targets
    (measured: 27 and 28 of 32 test units on time).


==============================================================================
13. TESTED ON
==============================================================================

  * Genesis Plus GX (automated tests and scripted playthroughs): menus,
    manual, options, pause menu, radar, tile and colour checks on all extra
    maps, pathfinding, and computer opponents on all maps.
  * Ares: all features of the German version have been played through by
    the author.
  * English version: built from the same code as the German version, only
    the texts differ; checked in Genesis Plus GX (all menus, manual,
    options, pause menu, map selection, music selection, buy menu, ending
    credits, computer opponent).
  * Campaign and 24-letter password (both versions, Genesis Plus GX): 80
    passwords checked against a reference calculation (40 valid, 40 with
    typing errors or random letters), wins on original and extra maps,
    continuing via CONT/WEITER, ending after the very last win.
  * NOT tested yet: real hardware / Everdrive; the campaign in Ares.

Please send bug reports and feedback to the author (channel see top).


==============================================================================
14. CREDITS AND LEGAL
==============================================================================

  Herzog Zwei (c) 1989 Techno Soft / Sega. This patch contains no game ROM,
  only changes to it. You need a legally acquired original. The patch is a
  fan project, non-commercial and not affiliated with the rights holders.

  Extended Command, translation, testing:
                                Karlhungus (RGB Retro Gaming)
  Programming:                  created with the help of Claude (Anthropic)
  Test emulators:               Genesis Plus GX, Ares
  Buy-menu names (English):     as in the "Accessible" patch for Herzog Zwei

  The ending of the game also names Karlhungus: "EXTENDED COMMAND" in the
  English version, "EXTENDED COMMAND UND ÜBERSETZUNG" in the German version
  (right before COPYRIGHT).

  Enjoy commanding!




INHALT
------------------------------------------------------------------------------
  1. Was ist EXTENDED COMMAND?
  2. Voraussetzungen und Installation
  3. Alle Neuerungen im Überblick
  4. Übersetzung
  5. HILFE: Die Anleitung im Spiel
  6. OPTIONEN: Start- und Pausenmenü
  7. Radar im Bild
  8. Bessere Wegfindung der Einheiten
  9. Neues Titelbild und Musikwahl
 10. Zusatzkarten und Großkarten
 11. Die Zusatzkarten im Einzelnen
 12. Hinweise, Einschränkungen, Bekanntes
 13. Getestet auf
 14. Credits und Rechtliches


==============================================================================
1. WAS IST EXTENDED COMMAND?
==============================================================================

Herzog Zwei (Technosoft, 1989) war eines der ersten Echtzeit-Strategiespiele
überhaupt: Du steuerst einen Transformer-Jet, kaufst Einheiten, gibst ihnen
Befehle und eroberst Stützpunkte, bis die gegnerische Hauptbasis fällt.

EXTENDED COMMAND bringt Verbesserungen, die das Spiel bequemer, fairer
einstellbar und abwechslungsreicher machen. Es gibt zwei Patches:

  * Deutsche Fassung: das komplette Spiel auf Deutsch.
  * Englische Fassung (English): die englischen Originaltexte, alle neuen
    Menüs und Funktionen auf Englisch.

Neuerungen:

  * deutsche Fassung: komplett deutsche Menüs, Meldungen, Einheiten- und
    Befehlsnamen, Ergebnisbildschirm, Story und Abspann
  * eine Anleitung direkt im Spiel (HILFE)
  * ein Optionsmenü mit 19 Einstellungen, getrennt für Spieler 1 und 2
  * ein Pausenmenü, das zugleich das Optionsmenü ist (START im Spiel)
  * ein dauerhaftes Radar im Bild (Vollbild)
  * eine deutlich bessere Wegfindung der Einheiten
  * 12 Zusatzkarten (teils als Großkarten), per Seitenwechsel wählbar
  * eine Einzelspieler-Kampagne über alle 20 Karten, je in TYP A-D, mit
    einem Passwort aus 24 Buchstaben
  * Musikwahl nach der Kartenwahl
  * ein neues Titelbild

Alle Neuerungen sind abschaltbar bzw. stehen standardmäßig auf dem
Originalverhalten. Die 8 Originalkarten bleiben unverändert spielbar.


==============================================================================
2. VORAUSSETZUNGEN UND INSTALLATION
==============================================================================

Du brauchst:

  * Das Originalspiel "Herzog Zwei (USA, Europe)" als ROM-Abbild
    (524288 Byte = 512 KB). Das ROM ist NICHT Teil dieses Downloads.
  * Ein IPS-Patchprogramm, z. B. Lunar IPS, Floating IPS (Flips) oder ein
    Online-Patcher.
  * Einen Emulator oder ein Flashmodul (siehe unten).

Installation:

  1. Kopiere dein Original-ROM und benenne die Kopie, z. B. in
     "Herzog Zwei - Extended Command.md".
  2. Wende EINEN der beiden Patches auf die KOPIE an:
       "Herzog Zwei - Extended Command (Deutsch).ips"   deutsche Fassung
       "Herzog Zwei - Extended Command (English).ips"   englische Fassung
  3. Fertig. Das gepatchte ROM ist 2 MB (2097152 Byte) groß. Die Prüfsumme im
     Header wird vom Patch korrekt angepasst.

Prüfsummen
  Original-ROM (Eingabe):    CRC32 A605B65B
                             MD5   e812002daafb264fc2ab1dff9bd06ac2
  Gepatcht, deutsch:         CRC32 B2E46B04
  Gepatcht, englisch:        CRC32 1F11C2F8

WICHTIG - ROM-Größe:
Durch die vielen Neuerungen (Wegfindung, Zusatzkarten, Optionsmenü) wächst
das ROM auf 2 MB (Original: 512 KB). Das ist ohne Bank-Umschaltung (Mapper)
adressierbar. Auf Original-Hardware läuft der Patch daher mit einem
Flashmodul wie dem Everdrive oder einem Modul mit größerem Speicherchip
(mindestens 16 Mbit). Das originale 4-Mbit-Modul reicht nicht.

Emulatoren: Entwickelt und getestet mit Genesis Plus GX und Ares. Andere
genaue Emulatoren sollten ebenfalls funktionieren.

Der Patch ist für genau eine ROM-Version gedacht (USA/Europa). Andere
Versionen (z. B. Japan) werden nicht unterstützt.


==============================================================================
3. ALLE NEUERUNGEN IM ÜBERBLICK
==============================================================================

  Übersetzung (deutsche Fassung)
    - Startmenü, Untermenüs, Meldungen, alle 18 Musiktitel
    - Kaufmenü mit Klein- und Großbuchstaben, Umlauten, Satzzeichen
    - Deutsche Namen für alle 8 Einheiten und 7 Befehle
    - Rote Anzeige im Kaufmenü heißt "ANZ" statt "UNIT"
    - Ergebnisbildschirm, beide Story-Enden und die Überschriften im Abspann

  Englische Fassung
    - Englische Originaltexte; lesbare Einheiten- und Befehlsnamen im
      Kaufmenü (CAR, TANK, ... STAY, PATROL, ...)
    - Alle neuen Menüs auf Englisch: HELP, OPTIONS, "Select the music",
      "Select the difficulty", "Page 1 of 3"

  Komfort
    - HILFE / HELP: 5 Seiten Anleitung im Spiel, mit den Kaufmenü-Icons
    - OPTIONEN / OPTIONS: 19 Einstellungen, getrennt für Spieler 1 und 2
    - Optionen auch im Spiel per START (Pausenmenü)
    - Radar im Bild (Gesamtkarte oder Nahbereich)
    - Transformer-Tempo doppelt (mit Kamera-Fix gegen Grafikfehler)
    - Dauerfeuer (B gedrückt halten)
    - Routenwahl neu: Einheiten finden ihren Weg um Hindernisse
    - Musikwahl nach der Kartenwahl: eines der 8 Kartenlieder wählen
      (vorausgewählt ist das Lied der Karte; hoch/runter spielt es zur Probe)
    - Hinweise "Wähle den Schwierigkeitsgrad" (TYP A-D) und "Wähle die Musik"

  Inhalt
    - 12 Zusatzkarten auf Seite 2 und 3 der Kartenwahl (insgesamt 20 Karten)
    - Einzelspieler-Kampagne über alle 20 Karten (je TYP A-D); das Ende
      kommt erst, wenn alles gewonnen ist; Passwort mit 24 Buchstaben
    - Großkarten bis 64x96 bzw. 128x48 Felder
    - Eigene Brücken, Lava, Eis, Stadt und mehr
    - Fünf Karten mit komplett neu gezeichneter Grafik
    - Neues Titelbild mit EXTENDED-COMMAND-Schriftzug
    - Eintrag EXTENDED COMMAND im Abspann


==============================================================================
4. ÜBERSETZUNG
==============================================================================

Englische Fassung
  Alle Texte des Originalspiels bleiben unverändert (Menüs, Musiktitel,
  Ergebnisbildschirm, Story, Abspann). Die neuen Funktionen haben englische
  Texte. Im Kaufmenü haben Einheiten und Befehle lesbare Namen (CAR, TANK,
  SAM, GUNBOAT, TRUCK, CANNON, INFANTRY, BIKE; STAY, PATROL, ATTACK, DEFEND,
  OCCUPY, HOME ATK, SUPPLY). Die Kartennamen sind die deutschen
  Originalnamen des Spiels, die Zusatzkarten folgen diesem Stil.

Der Rest dieses Abschnitts beschreibt die deutsche Fassung.

Menüs und Meldungen
  Das gesamte Startmenü ist deutsch: START, WEITER, SPIELER, MUSIK, SOUND,
  BILDSCHIRM (Geteiltes Bild / Vollbild), Mensch / Computer, PASSWORT,
  TYP A bis D, dazu die Meldungen PASSWORT FALSCH und RICHTIG.
  Im Menü-Font wurden ä ö ü Ä Ö Ü ß und das Komma ergänzt. Der blaue
  Menükasten ist eine Spalte breiter geworden, damit die deutschen Wörter
  hineinpassen. Alle 18 Musiktitel sind übersetzt.

Einheiten (Kaufmenü)
  AMR   Panzerwagen
  TAX   Kampfpanzer
  SAM   Flugabwehr
  ST    Kanonenboot
  SUP   Versorger
  GRM   B/L-Geschütz
  INF   Fußsoldat
  FWA   Motorrad

Befehle
  Halten, Patrouille, Besetzen, Abwehr, Vorrücken, Basis Angriff, Versorgung

Kaufmenü
  Der Spiel-Font wurde um Kleinbuchstaben, Umlaute und Satzzeichen erweitert.
  Im Kaufmenü werden nur 13 Zeichen pro Name angezeigt; deshalb sind drei
  Namen gekürzt (Versorger, B/L-Geschütz, Halten). Die Anleitung (HILFE)
  zeigt die vollen Namen. Die rote Anzeige unten im Kaufmenü heißt jetzt
  "ANZ" (Anzahl) statt "UNIT".

Kartennamen
  Die Kartenauswahl druckt die Namen mit dem Menü-Font, deshalb gehen dort
  Umlaute (z. B. SÜDSEE). Die Namen bestehen nur aus Großbuchstaben.

Spielende: Ergebnisbildschirm, Story und Abspann
  Der Ergebnisbildschirm ist deutsch: SIEGER, SPIELER 1/2, ZEIT, MENSCH oder
  COM, BASEN, EINHEIT, LEBEN (verbrauchte Transformer), PASSWORT. Beide Enden
  (LUDWIG gewinnt oder verliert) sind komplett übersetzt, ebenso die
  Überschriften des Abspanns (die Namen bleiben). Der Story-Font hat dafür
  ä ö ü Ä Ö Ü ß, Doppelpunkt, Fragezeichen und Bindestrich bekommen.


==============================================================================
5. HILFE: DIE ANLEITUNG IM SPIEL
==============================================================================

Im Startmenü gibt es einen neuen Punkt HILFE (englische Fassung: HELP). Er
öffnet eine Anleitung mit 5 Seiten:

  Seite 1   Das Kaufmenü lesen
  Seite 2-3 Die Einheiten (mit ihren Icons aus dem Kaufmenü)
  Seite 4-5 Die Befehle (mit ihren Icons aus dem Kaufmenü)

Bedienung: Links/Rechts blättert (mit Umlauf von der letzten zur ersten
Seite), B geht zurück ins Startmenü. Der Cursor und alle Einstellungen
bleiben dabei erhalten.


==============================================================================
6. OPTIONEN: START- UND PAUSENMENÜ
==============================================================================

Wo?
  * Im Startmenü: Punkt OPTIONEN (unter HILFE; englisch OPTIONS unter HELP).
  * Im laufenden Spiel: START öffnet statt der Original-Pause das
    Optionsmenü. Die Spielzeit steht still, der Ton wird angehalten.
    Beide Controller können das Menü bedienen. Es funktioniert im Vollbild
    und im geteilten Bild.

Bedienung
  Hoch/Runter   Zeile wählen
  Links/Rechts  Spalte wählen (Spieler 1 rot / Spieler 2 blau)
  A oder C      Wert weiterschalten
  B oder START  zurück

Jede Einstellung gilt getrennt für Spieler 1 und Spieler 2 - egal ob Mensch
oder Computer. So kannst du dir Vorteile geben oder einen Computergegner
schwächen oder stärken. Standard ist überall das Originalverhalten (außer
bei "Routenwahl", siehe unten). Die Einstellungen bleiben beim Zurückkehren
ins Startmenü und bei einem Spielneustart erhalten, werden aber nicht im
Passwort gespeichert und beim Ausschalten der Konsole zurückgesetzt.

Die Tabelle nennt die deutschen Namen. Die englische Fassung zeigt:
  Income, Build time, Base B, Armor D, Ammo G, Fuel E, Repair D, Reload G,
  Refuel E, Rapid fire, Speed, Missiles M, Cost, Radar wide view,
  Pathfinding; Werte 1x/2x/4x, instant, normal/double/unlimited, off/on,
  new/old.

Allgemein
  Einkommen      1x / 2x / 4x       Geldzuwachs pro Zeit
  Bauzeit        1x / 2x / sofort   Dauer, bis gekaufte Einheiten bereitstehen
  Basis B        normal / doppelt / unendlich
                 Energie der Hauptbasis (doppelt = halber Schaden)

Transformer (dein Jet)
  Panzerung D    normal / doppelt / unendlich
  Munition G     normal / doppelt / unendlich
  Treibstoff E   normal / doppelt / unendlich
                 ("doppelt" heißt: halber Schaden bzw. halber Verbrauch,
                 die Anzeigebalken bleiben dabei korrekt)
  Reparatur D    normal / doppelt so schnell / sofort
  Nachladen G    normal / doppelt so schnell / sofort
  Auftanken E    normal / doppelt so schnell / sofort
                 (sofort = sofort voll)
  Dauerfeuer     aus / an
                 B gedrückt halten, ca. 10 Schuss pro Sekunde
  Tempo          normal / doppelt
                 doppelte Höchstgeschwindigkeit in allen Modi (Roboter,
                 Flug, mit Einheit). Schuss und Kamera sind dazu passend
                 abgestimmt, damit die Karte beim schnellen Flug sauber
                 nachgezeichnet wird.

Einheiten
  Panzerung D    normal / doppelt / unendlich
  Treibstoff E   normal / doppelt / unendlich
  Munition G     normal / doppelt / unendlich
  Raketen M      normal / doppelt / unendlich
  Tempo          normal / doppelt
  Kosten         an / aus (aus = Einheiten kosten nichts)

Weitere Zeilen
  Radar im Vollbild   aus / an   (siehe nächster Abschnitt)
  Routenwahl          neu / alt  (siehe Abschnitt 8)

Hinweis: Die KI baut überzählige eigene Fußsoldaten selbst ab. Das ist kein
Kampfschaden und wird auch von "unendlich" nicht verhindert.


==============================================================================
7. RADAR IM BILD
==============================================================================

Im Original ist das Radar nur im Kaufmenü sichtbar. Mit der Option
"Radar im Vollbild" (OPTIONEN, je Spieler schaltbar) erscheint es dauerhaft
unten links im Spielbild - auch bei geschlossenem Kaufmenü.

  * Zwei Modi, genau wie im Kaufmenü: Gesamtkarte (mit Stützpunkten und
    beiden Transformern) oder Nahbereich (mit Einheiten). Umgeschaltet wird
    im Kaufmenü, indem der Cursor auf RADAR steht und Links/Rechts gedrückt
    wird.
  * Beim Öffnen des Kaufmenüs oder der Pause blendet sich das Radar aus,
    danach ist es wieder da.
  * Nur im Vollbild. Im geteilten Bild gibt es keinen freien Platz dafür;
    deshalb heißt die Optionszeile "Radar im Vollbild".
  * Auch auf allen Zusatz- und Großkarten verfügbar.
  * Standard: aus.

Das Radar wurde so eingebaut, dass keine Bildfehler über Basen entstehen und
Besetzt-Anzeigen kleiner Nebenbasen nicht darüber liegen.


==============================================================================
8. BESSERE WEGFINDUNG DER EINHEITEN
==============================================================================

Das Problem im Original
  Einheiten fahren in Luftlinie auf ihr Ziel zu. Stoßen sie an ein Hindernis,
  halten sie an, drehen sich zufällig und versuchen es erneut. In jeder Bucht
  und hinter jedem Felsriegel bleiben sie hängen - auf den neuen Karten mit
  Buchten, Brücken und Engstellen fällt das stärker auf.

Die Lösung: Routenwahl "neu"
  Für jede Karte und jedes Ziel (alle Stützpunkte und beide Hauptbasen) liegt
  im ROM ein vorberechnetes Wegfeld. Einheiten folgen damit dem kürzesten
  Weg um Hindernisse, Hänge und Lava herum. Dabei gilt:

  * Es wird mit der echten Standfläche gerechnet (Fahrzeuge 3x3 Kacheln,
    Fußsoldat und Motorrad 2x2).
  * Einheiten gleiten an Hindernissen entlang, statt anzuhalten.
  * Bei scharfen Kurven drehen sie auf der Stelle (nicht auf Hang oder Eis).
  * Hinter anderen Einheiten warten sie kurz, bevor sie ausweichen.
  * Ein gewähltes Ziel wird festgehalten, solange es einnehmbar ist und kein
    anderes deutlich näher liegt.
  * Wirkt bei den Befehlen Besetzen, Vorrücken und Basis Angriff.

Messung (je Karte 2x32 Testeinheiten, 16 Karten, Stand 11.11.2026)
  Pünktlich am Ziel angekommen: Original 74 %  ->  neu 96 %.
  Beispiele: LOCH 38 % -> 95 %, FLUSS 59 % -> 98 %, EISWERK 67 % -> 98 %,
  GLUT 62 % -> 92 %.

Schalter
  OPTIONEN, Zeile "Routenwahl", je Spieler: "neu" (Standard) oder "alt"
  (Originalverhalten). Gilt auch für die Einheiten des Computers.

Unverändert
  Kanonenboote, die Befehle Halten, Patrouille, Abwehr und Versorgung, das
  Verhalten im Kampf (Gegner im Blick) und der Transformer.

Grenzen
  In engen Durchgängen stauen sich viele Einheiten weiterhin. Auf OASE
  bremsen Bäume. Auf ABGRUND und KLAMM rutschen Einheiten, die auf einen
  Steilhang geraten, ab und können unten festsitzen. Auf Inselkarten bleibt
  ein über Land unerreichbares Ziel unerreichbar.


==============================================================================
9. NEUES TITELBILD UND MUSIKWAHL
==============================================================================

Titelbild
  Zwischen dem Herzog-Zwei-Logo und "(C) Techno Soft" steht jetzt der
  Schriftzug EXTENDED COMMAND in Chrom-Blau. Er blendet gemeinsam mit der
  Copyright-Zeile ein.

Musikwahl
  Nach der Kartenwahl (und nach TYP A-D im Spiel gegen den Computer) öffnet
  sich das Fenster "Wähle die Musik". Es zeigt die 8 Kartenlieder als
  "1. Titel (KARTE)". Vorausgewählt ist das Lied der gewählten Karte;
  Hoch/Runter wählt ein Lied und spielt es sofort zur Probe. A oder C
  startet das Spiel mit diesem Lied, B geht zurück zur Kartenwahl. Die Wahl
  gilt nur für diese eine Partie. Zu zweit können beide Controller wählen.
  Die Auswahl TYP A-D zeigt jetzt den Hinweis "Wähle den Schwierigkeitsgrad".


==============================================================================
10. ZUSATZKARTEN UND GROSSKARTEN
==============================================================================

Auswahl
  In der Kartenauswahl blätterst du mit Links/Rechts durch Seiten zu je
  8 Karten. Seite 1 enthält die 8 Originalkarten, Seite 2 und 3 die
  Zusatzkarten (8 auf Seite 2, 4 auf Seite 3). Unter der Liste steht z. B.
  "Seite 1 von 3" (englisch "Page 1 of 3"). Hinter den Namen steht wie auf
  Seite 1 ABCD (bei Zusatzkarten nur als Beschriftung, sie werden nicht als
  geschafft markiert). Vorschau, Radar, Basen und Startaufstellung kommen
  von der jeweils gewählten Karte. Seite 3 hat noch vier freie Zeilen.

Kachelsatz und Regeln
  Jede Zusatzkarte nutzt Grafik, Farben, Musik, Kaufmenü und Spielregeln
  eines der 8 Originalplätze. Daraus folgt:
  * Kanonenboote gibt es nur auf Karten mit STRAND-, EISFREI- oder
    OASE-Kachelsatz.
  * Auf Karten mit ABGRUND-Kachelsatz gibt es nur neutrale Stützpunkte.
  Einzelne Zusatzkarten mischen zwei Landschaften und haben eine eigene
  Farbpalette sowie die Musik einer anderen Karte.

Großkarten
  Zusatzkarten dürfen größer als die üblichen 64x64 Felder sein:
    64x96   hochkant
    128x48  quer
  Das ist 1,5-mal so viel Fläche. Mehr lässt der Arbeitsspeicher der Konsole
  nicht zu. Radar und Kartenvorschau zeigen die ganze Karte verkleinert.
  Auf großen Karten braucht der Computer länger bis zu den ersten
  Eroberungen.

Einzelspieler: Kampagne über alle 20 Karten
  Im Spiel gegen den Computer gehören die Zusatzkarten genauso zur Kampagne
  wie die 8 Originalkarten. Jede Karte muss in allen vier Schwierigkeits-
  graden (TYP A, B, C und D) gewonnen werden - insgesamt 80 Siege. Erst
  nach dem letzten davon kommt das Spielende.
  * Kartenwahl: gewonnene Typen werden hinter dem Kartennamen grau (ABCD),
    wie auf Seite 1. Eine Karte, die in allen vier Typen gewonnen ist, wird
    grau und ist nicht mehr wählbar; Seiten ohne wählbare Karte werden
    übersprungen.
  * TYP A-D: schon gewonnene Typen sind grau und nicht wählbar.
  * Passwort: Nach jedem Sieg zeigt der Ergebnisbildschirm ein Passwort aus
    24 Buchstaben (A bis P) in sechs Vierergruppen. Es speichert den Stand
    aller 20 Karten in allen vier Typen.
  * Weiterspielen: Startmenü, WEITER. Das letzte Passwort ist schon
    eingetragen, solange die Konsole an bleibt (auch nach einem Reset),
    dann genügt A oder C auf END. Hoch/runter
    springt zum nächsten/vorigen Buchstaben des Passworts, links/rechts
    wählt einen Buchstaben aus der Reihe darunter, A oder C trägt ihn ein
    (bzw. prüft das Passwort auf END), B geht zurück.
  * Die 24 Buchstaben enthalten eine Prüfsumme: Ein Tippfehler wird als
    PASSWORT FALSCH gemeldet, statt einen falschen Stand zu laden.
  * Passwörter des Originalspiels (11 Buchstaben) gelten nicht mehr.

Eigene Bausteine
  Für die Zusatzkarten wurden zusätzliche Kartenteile gebaut, die es in den
  Originalkarten nicht gibt: Holz- und Stahlbrücken (über Wasser und über
  Land), Kopien von Lava-, Stadt- und Schneeteilen aus anderen Karten,
  eigene Ufer und Strände sowie komplett selbst gezeichnete Pixelgrafik.

Fünf Karten (PLATINE, ORBIT, FLIPPER, WILDNIS und SÜDSEE) benutzen kein
Gelände aus dem Spiel, sondern vollständig eigene Grafik, siehe unten.


==============================================================================
11. DIE ZUSATZKARTEN IM EINZELNEN
==============================================================================

Seite 2
-------
MAUER (64x64, Kachelsatz LOCH)
  Eine Diagonalmauer teilt die Karte, zwei Durchgänge sind die einzigen
  Wege. Ursprünglich als Testkarte entstanden - ein guter Einstieg in die
  Zusatzkarten. Die Mauer ist im Radar sichtbar. 8 Stützpunkte.

FLUSS (64x64, OASE)
  Ein breiter Fluss trennt die Hauptbasen. Von beiden Basen führt je ein
  Seitenarm direkt bis vor die Basis, sodass Kanonenboote die Basis
  erreichen. Eine Holzbrücke führt vom Nordufer über eine Insel mit
  neutralem Stützpunkt zum Südufer. Boote können nicht unter der Brücke
  durchfahren - sie wirkt für Boote wie ein Damm.

BASTION (64x64, WALDUNG, ohne Wasser)
  Eine Rautenfestung aus vier Waldbastionen in der Mitte, dazwischen vier
  Tore, die sich im Kreuzweg zum neutralen Stützpunkt in der Mitte treffen.
  Vor zwei Ecken liegt je ein Felsriegel mit schmalem Tor und dahinter ein
  Kessel mit neutralem Stützpunkt. Drei Wege führen zwischen den Basen:
  durch die Festung oder durch die Gassen daneben. Die Karte ist
  punktsymmetrisch - beide Seiten haben die gleichen Chancen.

EISWERK (64x96 hochkant, EISFREI + STADT)
  Links ein Stück echte STADT mit Plattformen, Rohrleitungen und Hallen, ein
  Schneesturm weht über das Pflaster in das Eisland auf der rechten Seite.
  Dort liegen zugefrorene Teiche (Eis ist begehbar). In der Mitte fließt ein
  Fluss von Nord nach Süd, in einem Becken mit runder Eisscholle liegt ein
  neutraler Stützpunkt, der vom Boden aus nicht erreichbar ist. Zwei
  Stahlbrücken im Norden und Süden sind die einzigen Bodenwege über den
  Fluss. Spieler 1 (rot) startet links unten in der Stadt, der Gegner (blau)
  rechts oben im Schnee. 9 Stützpunkte, punktsymmetrisch verteilt.

PLATINE (64x64, komplett eigene Grafik, Regeln und Musik von STADT)
  Die Schlacht auf der Hauptplatine eines Mega Drive. Diese Karte benutzt
  kein Gelände aus dem Spiel: Leiterplatte, Leiterbahnen, Lötaugen, Chips,
  Elkos, Abschirmbleche und der Bestückungsdruck sind neu gezeichnet. Chips
  und Elkos sind Hindernisse, Leiterbahnen, Widerstände und Schrift nicht.
  In der Mitte liegt der Hof zwischen der CPU (MC68000, Norden) und dem
  Modulschacht (Süden) mit einem neutralen Stützpunkt; hinein geht es nur
  von Westen und Osten. Zwei weitere neutrale Stützpunkte liegen in den
  freien Ecken (Nordwest, Südost), je einer am West- und Ostrand. Spieler 1
  (rot) startet unten links, der Gegner (blau) oben rechts, die Karte ist
  punktsymmetrisch. Bei den Hauptbasen blinken zwei Leuchtdioden. Keine
  Kanonenboote. 9 Stützpunkte.

SANDUHR (64x96 hochkant, OASE)
  Ein See in Sanduhrform mit einem Damm in S-Kurve, zwei Uferpfaden und zwei
  Inseln (die Inseln sind freie Landfläche ohne Stützpunkte).
  9 Stützpunkte, punktsymmetrisch verteilt.

KLAMM (128x48 quer, ABGRUND)
  Zwei gewundene Flüsse mit je zwei Furten teilen die Karte in Heimat West,
  umkämpfte Mitte und Heimat Ost. Alle 10 Stützpunkte sind neutral, wie auf
  ABGRUND, und punktsymmetrisch verteilt.

GLUT (64x96 hochkant, OASE + VULKAN)
  Die Mischkarte. Im Norden (Gegner, blau) echtes VULKAN-Gelände mit
  brodelnden Lavaseen, kleinen Lava-Adern im roten Gestein, einem Lavastrom
  mit drei Furten und drei Vulkankratern. Lava ist befahrbar, schadet
  Bodentruppen aber (ein Panzerwagen ist in unter einer Sekunde zerstört).
  Im Süden (Spieler 1, rot) liegt eine Oase mit vielen Bäumen, Seen und einem
  kleinen Strand, dazwischen ein langsamer Übergang von Gestein zu Erde.
  Eigene Farbpalette, es läuft die Musik von VULKAN. 9 Stützpunkte,
  punktsymmetrisch verteilt.

Seite 3
-------
ORBIT (64x64, komplett eigene Grafik, Regeln und Musik von LOCH)
  Die Schlacht auf der Raumstation DS9. Wie PLATINE benutzt diese Karte
  kein Gelände aus dem Spiel: Decks, Stege, Sonnensegel, Radiatoren,
  Kuppeln, Antennen, Tanks und Container sind neu gezeichnet, drumherum
  liegt der Weltraum mit Sternen, einem Eisriesen mit Ring und einem
  Satelliten. Der Weltraum sperrt Bodentruppen: Sie kommen nur über die
  Stege von Deck zu Deck. Acht Decks liegen im Ring, in der Mitte der
  achteckige Kern mit einem neutralen Stützpunkt, erreichbar über vier
  Speichen. Spieler 1 (rot) startet unten links, der Gegner (blau) oben
  rechts. 9 Stützpunkte, punktsymmetrisch verteilt. Kuppeln, Antennen und
  die Positionslichter der Stege pulsieren.

FLIPPER (64x64, komplett eigene Grafik, Regeln und Musik von ABGRUND)
  Die Schlacht auf dem Flippertisch. Wie PLATINE und ORBIT benutzt diese
  Karte kein Gelände aus dem Spiel: ein Tisch mit zwei Enden (Kopf an
  Kopf), Holzspielfeld, Rahmen, Flipperfinger, Schleudern, Schlagtürme,
  Zielbänke, Rampen, Abschussbahn mit Feder und Kugel sind neu gezeichnet.
  Jede Hauptbasis steht im Auslauf ihres Endes, Spieler 1 (rot) unten,
  der Gegner (blau) oben. Zwischen den Fingerspitzen steht ein
  Mittelpfosten: Für Bodentruppen ist die Mitte zu, der Weg zur
  Hauptbasis führt außen um die Finger herum durch die Auslaufbahnen.
  7 Stützpunkte, alle neutral, beide Hälften exakt gleich. Die
  Hauptbasen liegen näher beieinander als auf den anderen Karten, die
  Partien sind schneller. Schlagtürme, Lampen, Rampenpfeile und
  Flippergummis blinken.

WILDNIS (64x64, komplett eigene Grafik, Regeln und Musik von WALDUNG)
  Die Schlacht im Flusstal. Diesmal ist alles Natur: Ein Fluss kommt aus
  der Schlucht eines Felsmassivs im Nordwesten, teilt sich in der
  Kartenmitte um eine Insel mit Steinkreis und mündet im Südosten in einen
  See mit Seerosen. Dazu dichter Laub- und Nadelwald, Felsrippen,
  Findlinge, Blumenwiesen und Trampelpfade. Wasser, Fels, Wald und
  Findlinge sperren Bodentruppen. Über den Fluss geht es nur an drei
  Stellen: über die Furt im Nordwesten, über die beiden Holzbrücken der
  Insel (dort steht der mittlere Stützpunkt) und über die Furt im
  Südosten. Spieler 1 (rot) startet unten links, der Gegner (blau) oben
  rechts. 9 Stützpunkte, punktsymmetrisch verteilt, an jeder Furt steht
  auf beiden Ufern ein neutraler. Wellen und Gischt glitzern, das
  Lagerfeuer flackert.

SÜDSEE (64x64, komplett eigene Grafik, Regeln und Musik von STRAND)
  Die Schlacht im Südpazifik. Ein Ringatoll mit hellem Sandstrand, Palmen,
  Dschungel und Strohhütten liegt im türkisen Meer. In der Lagune liegt
  eine Insel mit dem mittleren Stützpunkt und einem Kreis aus Tikis; zwei
  lange Holzstege führen vom Ring hinüber. Im Norden und Süden ist der Ring
  offen, dort liegt je eine kleine Insel, die über Holzbrücken zu erreichen
  ist. In der Nordwest-Ecke steht ein Vulkan mit Lavasee und Lavastrom, in
  der Südost-Ecke eine Dschungelinsel mit Schiffswrack und SOS am Strand.
  Wasser, Palmen, Dschungel, Hütten und Fels sperren Bodentruppen,
  Kanonenboote fahren auf Meer und Lagune. Spieler 1 (rot) startet links,
  der Gegner (blau) rechts. 7 Stützpunkte, punktsymmetrisch verteilt.
  Wasser und Lava glitzern.

Grafikstil von WILDNIS und SÜDSEE
  Beide Naturkarten wurden am 14.11.2026 in einem zweiten, detaillierteren
  Stil neu gezeichnet: gerasterte Muster statt einfarbiger Flächen,
  unregelmäßige Ufer und Ränder, geschlossene Kronendecken, große Palmen
  mit Wedeln und Schatten, Felswände mit Lichtkante, Basaltplatten,
  Bohlenstege mit Geländer, Strohhütten und geschnitzte Tikis. Grundriss,
  Sperrfelder, Basen und Starteinheiten sind unverändert.


==============================================================================
12. HINWEISE, EINSCHRÄNKUNGEN, BEKANNTES
==============================================================================

  * Das gepatchte ROM ist 2 MB groß. Auf Original-Hardware wird ein
    Flashmodul (z. B. Everdrive) benötigt. Mit weiteren Karten kann es bis
    4 MB wachsen, das ist die Grenze ohne Mapper.
  * Noch englisch: SOUND und END (die Boxen sind zu klein für deutsche
    Wörter).
    Die Namen der 8 Originalkarten sind die deutschen Originalnamen.
  * Im Ergebnisbildschirm (große Schrift) gibt es keine Umlaute. Die Namen
    im Abspann bleiben unverändert.
  * Umlaute fehlen in den gelben Titeln. In der Kartenauswahl gehen Umlaute,
    aber nur als Großbuchstaben.
  * Die Optionen werden nicht im Passwort gespeichert.
  * "Radar im Vollbild" funktioniert nur im Vollbild, nicht im geteilten Bild.
  * Im Nahbereich-Radar kann es bei sehr vielen Einheiten selten zu einem
    kurzen Ruckler kommen.
  * Passwörter des Originalspiels (11 Buchstaben) gelten nicht mehr; die
    Kampagne benutzt Passwörter aus 24 Buchstaben.
  * Nach B in der TYP-Auswahl bleibt der rechte Rand des TYP-Kastens neben
    der Kartenliste stehen, bis der nächste Bildschirm kommt (wie bisher).
  * Die Zusatzkarten haben nur wenige Ressourcen für Grafik-Kacheln. Das
    bestimmt, wie viel Abwechslung eine Karte bieten kann.
  * Die Computer-KI erobert auf sehr großen Karten spät. Bei den
    Inselkarten verändert die Wegfindung wenig.
  * Kanonenboote und Einheiten, die ein Kanonenboot-Befehl betrifft, werden
    weiter nach Originallogik gesteuert.
  * Auf GLUT und SÜDSEE kommen einzelne Einheiten bei manchen Zielen noch
    verspätet an (gemessen: 27 bzw. 28 von 32 Testeinheiten pünktlich).


==============================================================================
13. GETESTET AUF
==============================================================================

  * Genesis Plus GX (automatisierte Tests und Skript-Partien): Menüs,
    Anleitung, Optionen, Pausenmenü, Radar, Kachel- und Farbprüfung aller
    Zusatzkarten, Wegfindung und Computergegner auf allen Karten.
  * Ares: alle Funktionen der deutschen Fassung wurden vom Autor
    durchgespielt.
  * Englische Fassung: aus demselben Code gebaut wie die deutsche, nur die
    Texte sind anders; geprüft in Genesis Plus GX (alle Menüs, Anleitung,
    Optionen, Pausenmenü, Kartenwahl, Musikwahl, Kaufmenü, Abspann,
    Computergegner).
  * Kampagne und 24-stelliges Passwort (beide Fassungen, Genesis Plus GX):
    80 Passwörter gegen eine Vergleichsrechnung geprüft (40 gültige, 40 mit
    Tippfehler oder zufälligen Buchstaben), Siege auf Original- und
    Zusatzkarten, Weiterspielen über WEITER, Spielende nach dem letzten Sieg.
  * Noch NICHT getestet: echte Hardware / Everdrive; die Kampagne in Ares.

Fehler und Rückmeldungen bitte an den Autor (Kanal siehe oben).


==============================================================================
14. CREDITS UND RECHTLICHES
==============================================================================

  Herzog Zwei (c) 1989 Techno Soft / Sega. Dieser Patch enthält kein
  Spiel-ROM, nur Änderungen daran. Du brauchst ein legal erworbenes
  Original. Der Patch ist ein Fan-Projekt, nicht kommerziell und nicht mit
  den Rechteinhabern verbunden.

  Extended Command, Übersetzung, Tests:
                                  Karlhungus (RGB Retro Gaming)
  Programmierung:                 entstanden mit Hilfe von Claude (Anthropic)
  Test-Emulatoren:                Genesis Plus GX, Ares
  Kaufmenü-Namen (englisch):      wie im "Accessible"-Patch für Herzog Zwei

  Auch der Abspann des Spiels nennt Karlhungus: "EXTENDED COMMAND UND
  ÜBERSETZUNG" in der deutschen Fassung, "EXTENDED COMMAND" in der
  englischen (direkt vor COPYRIGHT).

  Viel Spaß beim Kommandieren!
==============================================================================
