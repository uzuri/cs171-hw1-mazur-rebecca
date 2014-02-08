1.  We've got no labels, no axes, no idea of what we're talking about here, not nothing -- without context, the chart isn't usable.

2. gs are for grouping, and that's what they're doign here -- we have an overall group to hold the whole chart together, a group for all the bars together, and then a group for each bar.  Each will be used to be able to easily target something at a different level, whether it be labels or colors or whatever.

3. Putting the text before the rects also puts it behind the rects. SVG is rendered in the order it's applied, kind of like if you were laying down construction paper squares -- later squares would appear on top of earlier ones (unless you actively did something to slide a square behind another).