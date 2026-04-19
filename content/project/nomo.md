
+++
# Project title.
title = "NOise MOnitor (NOMO) for aquariums"

# Date this page was created.
date = "2025-12-01"

# Project summary to display on homepage.
summary = "Development of a low cost, open source system for monitoring noise levels in aquaria"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["bioacoustics"]

# Categories: can be used for filtering projects, especially to distinguish them from blog posts
categories = ["research"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "nomo.jpeg"

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

## Quick summary

Ocean noise can negatively impact marine life in a variety of ways, including causing injury, increasing stress, and interfering with communication, navigation, or foraging. As a result, the acoustic environment should be considered in the care of a marine animal in captivity. This is challenging due to the high costs of monitoring systems and the complexity of acoustic data analyses. We have developed the NOise MOnitor (NOMO), a low-cost, open-source, smart acoustic recorder that can monitor noise levels in an aquarium environment, conduct on-board processing to derive simple noise metrics, and automatically share the results online at regular intervals.

The system is very similar to our drifting recorders. It is based on an inexpensive electronics package (Raspberry Pi with analog-to-digital converter expansion board) enclosed within a waterproof case, combined with one or two hydrophones. The use of a Raspberry Pi, which is a fully functional Linux computer, allows for wireless communication and onboard data processing. Our team has successfully used a similar electronics package housed within a drifting buoy to collect noise measurements at sea. The total cost per NOMO is about $1000 USD, and all software and hardware will be published online such that can be available for use and further development by other aquariums and research groups.
