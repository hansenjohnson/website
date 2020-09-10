+++
# Project title.
title = "Right whale location uncertainty"

# Date this page was created.
date = "2019-11-28"

# Project summary to display on homepage.
summary = "Estimating right whale location following visual or acoustic detection to inform dynamic management"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["bioacoustics","behavior"]

# Categories: can be used for filtering projects, especially to distinguish them from blog posts
categories = ["research"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "rw_sim.png"

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

## Quick summary

USA and Canadian government agencies have implemented a variety of management measures in an effort to improve conservation outcomes for the endangered North Atlantic right whale. One such strategy is dynamic management, which broadly refers to risk-mitigation actions within defined areas in response to right whale observations. Such actions are designed to reduce risk from the two primary sources of right whale mortality: vessel strike and fishing-gear entanglement.

All dynamic management strategies require knowledge of whale distribution (i.e., where whales are). We currently get this information exclusively from visual surveys and opportunistic sightings reports. These are very valuable sources of information, but are subject to many limitations (expensive, weather-limited, etc.) that make them impractical to provide the consistent coverage over large areas that right whales occupy. 

Near real-time passive acoustic monitoring (PAM) systems have been operational for many years, and present a persistent, efficient, and effective survey method. Acoustic detections, however, are quite different from sightings because we can detect right whale sounds over a large range (10s of kilometers). The uncertainty in location of an acoustically-detected whale has been cited as one of the main reasons that acoustics have not been used to inform management. 

This rationale does not consider whale movement or its contribution to location uncertainty following either visual or acoustic detection. The goal of this project is to use a simulation-based approach to estimate uncertainties in right whale location following acoustic and visual detection and identify the timescale at which the uncertainties become similar owing to post-detection whale movement. 

