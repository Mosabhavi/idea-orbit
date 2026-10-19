Idea Orbit

An interactive attention map. You are the sun, your ideas orbit around you, and a grid of weeks and places bends around them. The heavier an idea, the closer it sits and the more it pulls on the grid.

Single HTML file. No build step, no dependencies.

Run it

Open index.html in a browser. Google Fonts load when you are online and fall back to system fonts when you are not.

How to read it
Distance from the sun: set by weight. Weight 10 is closest, weight 1 is farthest.
Grid: the vertical lines are twelve weeks starting Oct 19, 2026. The horizontal bands are places (Campus, Home, Online, Gym). The sun and every idea pull the grid lines toward them, in proportion to weight.
Dashed line: the interview date, marked on the time axis.
Colors: gold for the two goals, teal for what feeds them, grey-violet for parked ideas.
Controls
Sliders set each idea's weight from 1 to 10. The map updates as you drag.
Click an idea on the map or in the list to see its note, weight, attention share and grid bend.
Pause orbit stops the motion.
My focus now restores the starting weights. Ideas you added keep their current weight.
Everything equal sets every idea to 5, which shows how a flat spread of attention looks.
Add an idea with a name and a category. You can add up to 24 ideas in total, and remove the ones you added.
What the numbers mean
Attention is an idea's weight divided by the total of all weights.
Grid bend is an idea's weight divided by the heaviest idea's weight.
The big percentage in the side panel is the share of attention on the goals plus the ideas that feed them.
Customize

Everything lives in the script at the bottom of index.html:

DEFAULTS: the ideas, their category (goal, feeds or parked), starting weight and note.
START: the first date on the time axis.
INTERVIEW_DAY: days from START for the dashed marker.
PLACES: the labels on the place axis.
Saved data

Weights and ideas you add are saved in your browser's local storage under the key idea-orbit-v1. They stay in that browser and are not sent anywhere. Clearing site data resets them.

Privacy

The starting ideas and notes are personal. Keep the repository private, or edit DEFAULTS before making it public.
