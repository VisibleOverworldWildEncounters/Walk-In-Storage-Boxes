# Walk-In-Storage-Boxes
Walk In Storage Boxes

This script is for Pokémon Essentials v20 and v20.1 (for short PEv20).
VERSION-NUMBER: v0.0.1


Every storage box has an representation as a map, where you can walk in as the player and
see your caught pokemon move as overworld pokemon and interact with them.


## FEATURES
- You can create maps where your caught pokemon live and run around
- Pokemon play their cry when touched

## INSTALLATION
- Add Graphics: Either get the resources from Gen 8 Project https://reliccastle.com/resources/670/ and install the "Graphics/Characters" folder in your game file system. Or you place your own sprites for your pokemon/fakemon with the right names in your "\Graphics\Characters\Follower" folder and your shiny sprites in your "\Graphics\Characters\Follower shiny" folder. 
The right name of sprites is:
   - usual form     - SPECIES.png   where SPECIES is the species name in capslock (e.g. PIDGEY.png)
  - alternate form - SPECIES_n.png where n is the number of the form (e.g. PIKACHU_3.png)
  - female form    - SPECIES_female.png or SPECIES_n_female (e.g. PIDGEY_female.png or PIKACHU_3_female.png)
- Create Maps: build and design a map for each storage box and keep the corresponding map ids in mind . Also make sure that these maps are accessible for the player and connected to the ordinary maps, somehow.
- Add Script
- Change Settings: Open the settings.rb file in the folder and write down the map ids in the parameter STORAGE_MAPS and change the parameters in the settings section therein as you like. Details descriptions about the parameters can be found there as well. 
- Enjoy!

## HELP AND MORE
If you need help, found a bug or search for more modifications then go to pokecommunity.com
