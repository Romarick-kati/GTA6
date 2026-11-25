HOW TO GET A REAL-LOOKING CHARACTER (optional)

Put a rigged human model named  hero.glb  in this folder (models/hero.glb), then redeploy.
The game loads it automatically and your hero becomes that model, with idle / walk / run animations.

Where to get one (free):
 1. Quaternius  (quaternius.com)  - free CC0 characters and animation packs, already in .glb / glTF format.
 2. Mixamo  (mixamo.com, free Adobe account) - pick a character, then add the animations Idle, Walking, Running.
    Download as FBX (with skin), open in Blender (free), File > Export > glTF 2.0 (.glb), keep animations ticked.
 3. Ready Player Me (readyplayer.me) - make an avatar, download the .glb, then animate it on Mixamo (step 2).

Rules: the model should face forward (+Z, the normal for glTF), and each animation name should contain
"idle", "walk" or "run" (upper/lower case does not matter). Size is automatic (about 31 game units tall).
If the file is missing the game simply keeps the built-in character.
