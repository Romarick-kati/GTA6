GTA-6 - how to put it online and play it on your phone

You need ANY free static host (the game is just files). Easiest first:

1) NETLIFY DROP (2 minutes, no account needed to try)
   - On a computer open https://app.netlify.com/drop
   - Drag this whole folder (benskin-night-app) onto the page.
   - You get a link like https://something.netlify.app  -> open it on your phone.

2) CLOUDFLARE PAGES (free, fast in Africa)
   - dash.cloudflare.com > Workers & Pages > Create > Pages > Upload assets
   - Upload the folder, click Deploy. Link: https://yourname.pages.dev

3) GITHUB PAGES (free)
   - Create a repository, upload these 5 files, then Settings > Pages > Deploy from branch (main, / root).
   - Link: https://yourusername.github.io/yourrepo/

ON THE PHONE (use the https link)
   - Android Chrome: menu (3 dots) > Add to Home screen / Install app.
   - iPhone Safari: Share button > Add to Home Screen.
   - It opens full screen like an app, saves your cash and missions, and after the first load it also works offline (the 3D engine is cached).

Do NOT just double-click index.html on a phone: install/offline needs the https link.

TOUCH CONTROLS (phone)
   - After you press START you get an on-screen joystick (bottom-left) and buttons (bottom-right): FIRE, JUMP, E/ENTER, RUN, GUN, RELOAD, HORN, VIEW.
   - Drag the empty right side of the screen to look around. VIEW switches third-person / top view.
   - If you ever do not see the controls: open the link with ?pad=1 at the end (example: https://yourname.netlify.app/?pad=1) or press T on a keyboard.
   - Turn the phone sideways (landscape).
ENTERING BUILDINGS
   - Walk up to a glowing door sign (green = shop, blue = apartment, red = bar) and press E / ENTER. Leave by the green EXIT door.

CONTROLS CHANGE WITH WHAT YOU ARE DOING
   - On foot: FIRE, JUMP, E/ENTER, RUN, GUN, RELOAD, VIEW.
   - In a car or boat: BRAKE/REVERSE, HORN, EXIT, FIRE, VIEW.
   - In a plane: CLIMB, LAND, EXIT, VIEW. Push the joystick to speed up, hold CLIMB at speed to take off, hold LAND to come down on open ground.
   - The MENU button (top-right, under the minimap) opens CHEAT CODES, HELP, RADIO, SOUND, SHADOWS and VIEW.
ENTERING BUILDINGS
   - Every block has open doors on all four sides, with a glowing coloured light above each: green = shop, blue = apartment, red = bar. They also show as dots on the minimap.
REAL CHARACTER
   - See models/README.txt (put your own hero.glb in the models folder).

UPSTAIRS, LAKE, BOMBS (v11)
   - Every building has two floors. Walk up the wooden stairs inside. Upstairs you find stockrooms, bedrooms, VIP rooms, safes and a bed to sleep in.
   - A big lake in the south-east of the city (cheat code: lake) with boats. Roads cross it as bridges.
   - BOMB button / X key: throw a bomb (2 second fuse, big blast). Buy bombs in shops, find them in stockrooms. Police throw bombs at wanted level 4+.
   - Inside a car, boat or plane, bullets damage the vehicle, not you. Only explosions hurt you fast.

DAY AND NIGHT, GRAPHICS (v12)
   - Full day/night cycle (10 minutes per day). The clock is on the minimap. Cheats: day, night, dawn.
   - MENU > GRAPHICS cycles HIGH / MEDIUM / LOW. The game also lowers quality by itself if your phone is slow.
   - Your money, rank, ammo, bombs and the time of day are saved automatically.

BIGGER BUILDINGS, LIFT, PEOPLE (v13)
   - Rooms are about 2.25x bigger per floor and every building has 3 floors (ground, upper, top).
   - Take the wooden stairs to the 1st floor, or step on the glowing LIFT pad and stand still for a second (or press E): the lift goes up to each floor and back down.
   - People now vary in height and build, and wear jackets, hoodies, dresses, beards and glasses. They walk with a hip sway and look around when standing.

BIG STAIRS, CLEAR EXIT (v14)
   - Two big staircases side by side in every building (90 wide, 260 long, yellow handrails, "STAIRS UP / STAIRS DOWN" signs): ground to 1st floor, and 1st floor to the top floor.
   - While you are on the steps the camera swings to the side and the floor above is cut away, so you can see the stairs you are climbing.
   - The EXIT is a wide glowing doorway with a green frame, a big EXIT sign and a green light beam; walking into any part of it takes you out.

v15
   - App name is GTA-6 (to rename it later: search for "GTA-6" in index.html and manifest.webmanifest and change it).
   - The start screen is just the title and START.
   - The character now has a body size: it can no longer sink into walls or trees.
   - Rooms are 4x the original floor area. Doors outside are bigger and show SHOP / HOME / BAR.
   - Inside any building the LEAVE button (key L) takes you out from any floor. E at the foot or top of the stairs also takes you up or down.
