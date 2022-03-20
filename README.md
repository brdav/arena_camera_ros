## Arena Camera Driver for ROS1

# Getting Started
setup and usage https://support.thinklucid.com/using-ros-for-linux/


for ROS2 driver contact LUCID support for more information 
https://support.thinklucid.com/contact-support/

# This Fork
The driver was adapted for usage with the Triton TRI054S specifically. Changes were held minimal, but include:
- enable PTP, where camera must be a slave device
- optimize streaming options to prevent packet loss
- allow disabling of auto white balance
- allow sensor cropping
- allow limits for auto gain
- bug fix: set target brightness correctly
