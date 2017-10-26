
+++
# Date this page was created.
date = "2015-04-27"

# Project title.
title = "Robot Navigation system using Xbox Kinect"

# Project summary to display on homepage.
summary = "A cheap navigation system for a robot using Xbox Kinect"


# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "kinect_navigation.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["computer-vision"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false


+++

Built a navigation system for a robot using OpenCV and OpenKinect libraries, that uses disparity map along with pixel intensity
calibration to compute the distance of an object/obstacle from the Xbox Kinect. Generated signals are sent to motor
driver circuit that propels the wheel to avoid possible collision with obstacle.

{{< youtube kNfKIVMBxEE >}}
