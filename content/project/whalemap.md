+++
# Project title.
title = "WhaleMap"

# Date this page was created.
date = "2017-02-28"

# Project summary to display on homepage.
summary = "Display results from right whale surveys in Atlantic Canada."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["data-visualization"]

# Categories: can be used for filtering projects, especially to distinguish them from blog posts
categories = ["data-visualization"]

# Optional external URL for project (replaces project detail page).
# external_link = "http://leviathan.ocean.dal.ca/WhaleMap/"

# Does the project detail page use math formatting?
math = false

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "WhaleMap.png"

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

I developed WhaleMap to communicate the latest right whale observations and survey results to scientific, regulatory and industrial sectors to inform more effective, dynamic planning of research and conservation activities. It's synchronized with data repositories from a number of different survey groups, so that shortly after their planes land, boats tie up, or autonomous vehicles call home, the survey results will update here.

It would not be possible without help and feedback from my fellow lab members and collaborators at DFO, New England Aquarium, Canadian Whale Institute, NOAA, and others. It also relies entirely on the efforts of the data contributors. Their dedication and collaborative spirit give this species the best chance at survival.

WhaleMap is written using entirely open source tools. It relies on Google Drive / Dropbox, [rclone](https://rclone.org/), R (and [Shiny](https://shiny.rstudio.com/)), and several linux commands (mostly cron for task scheduling). The links and presentation below should provide more information. More information is available at [whalemap.org](https://whalemap.org), in the WhaleMap publication, the GitHub repository, or by getting in touch with me!
