Progress builds of a Paper Mario inspired turn-based small numbers RPG, built in Unity.

Currently in progress on barebones combat system. Only jump command 'works' (sometimes enter won't work, but a mouseclick will work and subsequent enter will too).

V.9 Added example of soon-to-be implemented tweened jump command animation in beginning of level's background (implemented using Demigiant's "DOTween" engine asset).

V.8 Added inventory submenu with icon, edited panel placement.

V.7 Increased size of command submenu panel

v.6 Added command submenu. Only bootbutton->jump command actually works.

v.5 Battles now have an end and enemy turn states! When the player wins a battle they get teleported back to the overworld. No lose state yet. Endlessly running into enemies when attacking is now fixed (maybe).

V.4 Added enemy selector to combat. If enemy count is greater than two and any enemy after the 2nd is selected the player will get caught endlessly running into the first enemy. :sweat_smile:

V.3 Added enemies spawning (random count between 2 and 4) and populating battlestage (can only attack first enemy atm, can't select enemy either)

V.2 Added Realtime CSG Generated level


/////////////////////////////////////////////////////////////////////////

Controls:


Overworld:

    -WASD: Movement
    -SPACEBAR: Jump


Battle:

    -A/D: rotate through command menus
    -ENTER/MouseClick/SPACEBAR: confirm command menu (Jump command only one that works atm)
    -W/S: Cycle through commands in seleced command menu
    -F: confirm command in command menu (Only regular jump works)
    -BACKSPACE: return to command menus menu
    -SPACEBAR: Confirm enemy selection for command

        note: ENTER KEY in battle won't work if you click anywhere else. In those cases clicking on the command will still work, and so will subsequent enter commands

        also hitting spacebar while confirm the command AND execute the command at same time.


/////////////////////////////////////////////////////////////////////////

Demo Link:

https://spicygarlicalbacoreroll.github.io/PaperRPGDemo/


    