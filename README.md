# DS3_Randomizer
Dark Souls 3 Randomizer Mod Tools

Side project for DS3 randomizer runs.

Example:

info = FogRemover(full_path)
info.process() # This processes the spoiler log

info.fog_gates # This shows all fog gates (To and From) as well as warps
info.zones # This shows all zones as well as their scaling (if this option is turned on)
info.search('Archdragon') # This searches fog_gates and pulls up any gates/warps relating to the search term
info.path("Greirat's Cell", 'Grand Archives') # This gives you the fastest path between two zones. Full name needs to be specified. This may sometimes give you paths that are not acessible (one-directional warps) or require special key-items.
info.plot(cmap='gist_rainbow') # Generate a plot of the world. Set your color mapping to correspond with the enemy scaling.
