+++
# Project title.
title = "Real-time detection range"

# Date this page was created.
date = "2017-02-28"

# Project summary to display on homepage.
summary = "Evaluating the range-dependent accuracy of a near real-time baleen whale monitoring system."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["bioacoustics","gliders"]

# Categories: can be used for filtering projects, especially to distinguish them from blog posts
categories = ["research"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "dmon_buoy.png"

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

## Quick summary

Passive acoustics (i.e., "listening") has become an important tool for monitoring marine mammals. The use of passive acoustic monitoring, or PAM, is typically motivated by the fact that hydrophones are persistent (can record for long periods, regardless of conditions) and inexpensive compared to vessel-based surveys.

One of the pervasive challenges in passive acoustic monitoring, especially for baleen whales, is that it is extremely difficult to know how far you can hear calls underwater. Baleen whales (e.g., blue, fin, right, humpback; the big ones) make very loud, very low calls that, under the right conditions, can propagate 10s to 100s of kilometers. The range over which these calls can be detected (by another whale, or hydrophone) depends largely on the type and quality of the call, the depth of the water, the physical properties of the water (temperature, salinity, etc), the type and structure of the bottom, ambient noise levels, and more.

Even though it's complicated, it's very important to understand how far we are able to detect whales if we hope to interpret our monitoring results correctly. The main goal of this project is to conduct an experiment that allows us to determine the range-dependent accuracy of the [LFDCS real-time monitoring system](http://dcs.whoi.edu) on mobile (glider) and fixed (buoy) platforms.
