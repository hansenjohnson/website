
+++
# Project title.
title = "Drifters for passive acoustic monitoring"

# Date this page was created.
date = "2025-04-01"

# Project summary to display on homepage.
summary = "Development of a low cost, open source drifting recorder for passive acoustic monitoring during vessel surveys"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["acoustics","health","engineering","behavior"]

# Categories: can be used for filtering projects, especially to distinguish them from blog posts
categories = ["research"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "drifters.jpeg"

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

## Quick summary

Collecting acoustic data during vessel-based surveys can provide valuable insights into the acoustic ecology of marine animals and the potential impacts of noise. It is also challenging as vessel-based recording systems typically restrict maneuverability and are subject to loud vessel noise, while most remote recording systems are expensive and designed to be deployed for extended periods on moorings or autonomous vehicles. The goal of this project is to develop a low-cost, open-source, drifting recorder that offers a hand-deployable, accessible, and customizable option for collecting acoustic data for short periods from virtually any survey vessel. The system is based on an inexpensive electronics package (Raspberry Pi computer with sound card, GPS, satellite tracker and rechargeable battery) enclosed within a waterproof case fixed atop a custom spar buoy that measures approximately 1.4 m in height and weighs about 10 kg in air. The total material cost per unit is approximately $1200 USD, depending on the configuration, and all software and hardware will be made freely available for use and further development by other research groups. The system records audio using GPS-time, which allows for accurate synchronization with other data streams (e.g., vessel cameras, drone video, other recorders). Our research team has been using these systems since the summer of 2025 to collect passive acoustic monitoring data during our surveys for North Atlantic right whales. We are currently developing the capacity for these systems to transmit data in real-time and assessing the accuracy of sound source localization using an array of multiple recorders. We hope that this system will provide an open-source, customizable and accessible option for fine-scale acoustic monitoring of marine species and the ocean soundscape.

All the latest code and build instructions are available on the project [github repository](https://github.com/hansenjohnson/drifter)
