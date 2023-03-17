## Arena Camera Driver for ROS1

# This Fork
Changes were held minimal, but include:
- allow Line I/O configuration
- enable Chunk Data, to capture both timestamps and exposure times
- add separate message for time info
- enable PTP, where camera must be a slave device
- optimize streaming options to prevent packet loss
- allow disabling of auto white balance
- allow sensor cropping
- allow limits for auto gain
- bug fix: set target brightness correctly

# Getting Started
setup and usage https://support.thinklucid.com/using-ros-for-linux/


for ROS2 driver contact LUCID support for more information 
https://support.thinklucid.com/contact-support/
