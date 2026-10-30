# Tower Offense — Crystal Meadow + Saltworks

Play the browser demo at https://imfoot.github.io/Tower_Offense_Demo/.

Three maps and six troop classes. Command the attackers and arrange their
release order. Use full screen for the
best view. Desktop mouse and keyboard are the primary target.

The meadow maps include all six classes in the translucent troop loadout overlay. Choose one to
three classes before starting an assault: Crystal Bulwark, Flux Fox, Prism Ranger,
Void Ray, Runebinder or Lifewarden. The selection
stays locked across its three waves; use **Loadout** to review it, or restart
the map to choose again. The recruitment area shows only your selected classes.
Troops outside the selected loadout cannot recruit or evolve.
Sunmeadow Trail and Mossgate Reach have three waves and 20 exit hearts.
These two maps allow three groups per wave, with at most two groups of one troop type.
Use **Maps** to choose a mission. On Mossgate, select each group and choose A or B
at both road forks before releasing the wave. The planning helper text now fits
above the Release button. Send-with links can target any displayed group. Embedded
fonts supply arrows, hearts and other UI symbols without relying on device fonts.

Build 8 updates **Saltworks 09** from PR #7, with one shared V1 UI across all maps and new
terrain, troops and buildings. Select it through **Maps**. Saltworks keeps its
own authored rules: 160 arrivals in five waves, two entrances and a shared coast,
six group slots growing to eight, at most three groups per class, and all six
classes in its loadout. New defenses occupy seven plots over the five waves.
Choose each group's road with the numbered badges on the map or the matching
buttons below it. Saltworks uses **1A / 1B**; Mossgate uses **1A / 1B** and
**2A / 2B**. The road determines the exit automatically, with no route dropdowns.
Switching maps keeps the same command controls while updating the map, troop
art, labels, objective strip and recruitment sizes. Existing meadow limits remain.
Saltworks progress is saved separately. **Maps** returns to any mission.

Space: launch/pause · N: next batch · F: speed · R: ranges · M: Saltworks mute.

This repository contains only the exported playable demo and its browser
runtime. Game development source is maintained separately. All game art is
included as part of the demo; this repository does not grant a separate license
to reuse or redistribute those assets.
The included Noto fonts are licensed separately under the SIL Open Font License;
see font-licenses.txt for their copyright notices and license terms.

GitHub Pages serves the main branch root. The .nojekyll marker keeps the
prebuilt export intact; no custom headers or game server are required.
