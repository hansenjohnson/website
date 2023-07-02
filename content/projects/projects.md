+++
# Projects widget.
widget = "projects"
active = true
date = "2016-04-20T00:00:00"

title = "Projects"
subtitle = "These are some of the projects I'm currently involved in, or have worked on in the past. Each at least contains a basic summary, but feel free to contact me at hansen.johnson@dal.ca for more details."

# Order that this section will appear in.
weight = 10

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "Bioacoustics"
  tag = ".bioacoustics"

[[filter]]
  name = "Habitat ecology"
  tag = ".habitat-ecology"

[[filter]]
  name = "Ocean gliders"
  tag = ".gliders"

[[filter]]
  name = "Behavior"
  tag = ".behavior"

[[filter]]
  name = "Data visualization"
  tag = ".data-visualization"

+++
