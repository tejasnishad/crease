# Crease

Crease is a control panel for Origami, in the vein of Tweakpane and Dialkit.

## Components:

1) Crease Panel:
Comprises the panel and an overlay. Swipe from the right edge to trigger, or disable the action and hook up custom triggers with pulse inputs. You can drop crease components (or even your own) directly inside the panel layer.

2) Checkbox:
Outputs a boolean value.

3) Slider:
Specify a range with min/max. To convert into a stepped slider, specify a non-zero step count. You can set a default value; to reset the slider to defaults, simply double-tap. This component outputs a value within the specified range.

4) Enum:
Provide a JSON array of labels. Output is the index of the currently selected item. Similarly to the slider, you can set a default value and double-tap (in this case only the label can be double-tapped) to reset the value to defaults.

5) Button:
A button. Outputs a pulse when tapped.
