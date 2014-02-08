1.  We've got no labels, no axes, no idea of what we're talking about here, not nothing -- without context, the chart isn't usable.

2. gs are for grouping, and that's what they're doign here -- we have an overall group to hold the whole chart together, a group for all the bars together, and then a group for each bar.  Each will be used to be able to easily target something at a different level, whether it be labels or colors or whatever.

3. I'm not seeing a difference in behavior, but I'm not sure why.  I suspect it has to do with the order in which javascript executes things; the text isn't being added until there's something to add it to, so it doesn't much care where it shows up in the flow (so long as it shows up *after* groups exists; that's kind of important).