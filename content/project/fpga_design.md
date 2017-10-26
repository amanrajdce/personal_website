
+++
# Date this page was created.
date = "2016-03-27"

# Project title.
title = "FPGA accelerated Abandoned Object Detection"

# Project summary to display on homepage.
summary = "A standalone system based on Xilinx FPGA for abandoned object detection"


# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "fpga-1.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["demo", "computer-vision"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false


+++

Designed a standalone system that uses a novel static background modeling algorithm and identifies any object lying abandoned for a given period of time. Implemented on Xilinx FPGA ZYNQ-ZC702 board. VxWorks used as RTOS to manage the real time processes.

{{< figure src="/img/fpga-2.png" title="Horizontally placed camera on table top in minimally crowded place" >}}
