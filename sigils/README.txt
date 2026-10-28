Westeros modular webpage asset pack
===================================

REFERENCE
- reference-complete.png
  The completed concept image to use as the visual target. It already contains the panels, compass and house markers.

BASE LAYERS
- base-background-clean.png
  The page background only: dark castle atmosphere + the detailed Westeros map. No house markers, no left panel, no legend panel, no compass, no wolf logo, no navigation/UI text.
- westeros-map-clean.png
  The user-supplied map with only the built-in top-right legend/scale and compass removed so those can be positioned independently. Geography and settlement labels are otherwise left intact.
- westeros-map-original.jpg
  Unmodified source supplied by the user.

MODULAR UI IMAGE ASSETS
- left-panel-empty.png
  Empty pointed panel. Put your headings, paragraph and button over it using HTML/CSS.
- left-panel-reference.png
  Crop of the filled panel from the visual reference, for comparison only.
- legend-panel-empty.png
  Empty top-right dark panel. Add legend content with HTML/CSS.
- legend-panel-reference.png
  Crop of the filled legend from the reference.
- compass-rose.png
  Transparent compass asset.
- direwolf-logo.png
  Transparent wolf/direwolf mark for the WESTEROS header.
- divider-ornament.png
  Gold line/diamond ornament used as a decorative divider.
- search-icon.png
  Optional transparent magnifying-glass icon from the header concept.

HOUSE MARKERS
- stark.png
- lannister.png
- targaryen.png
- baratheon.png
- tully.png
- arryn.png
- tyrell.png
- martell.png

WHAT DOES NOT NEED TO BE AN IMAGE
The following are easier and better to create in CSS/HTML rather than bake into graphics:
- the black/dark header bar
- thin gold horizontal rules
- navigation text and active underline
- panel copy and button text
- house names shown on hover
- footer text

Suggested exercise structure:
1. Use base-background-clean.png as the large page background/reference layer.
2. Position left-panel-empty.png and legend-panel-empty.png with CSS.
3. Position compass-rose.png and direwolf-logo.png.
4. Place each house PNG over the correct seat on the map using position:absolute and percentage offsets.
5. Show the house name/seat only on :hover.
