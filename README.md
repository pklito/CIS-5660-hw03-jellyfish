This is my submission for the Houdini homework for procedural graphics CIS-5660 at UPenn.

## Features
The jellyfish features a head, veins, tentacles, organs and hairs.  
- The head is keyframed to move up and down and squash and stretch.
- The tentacles utilize Vellum cloth, and are cached into a file.
- The hairs use Vellum hair simulations
- The veins are done with a shortest path solver. The shortest path solver is run for the first frame and then deformed onto the moving mesh in order to prevent the veins from recalculating every frame.
- I did the organs with cloned semicircles and a mountain SOP.
