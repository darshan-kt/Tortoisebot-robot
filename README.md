# Tortoisebot-robot

This is the well structured 2 wheel robot for testing purpose in simulation. This has differential drive plugin which subscribes /cmd_vel topic for moving the robot and publishes the /odom topic as a feedback
This also has hukoyo laser plugin which publishes the scan data for detrmine the obstracles pose. 
This /scan topic and feedback /odom topics are enough to perform mapping and localization tasks using gmapping and amcl nodes respectivelly.
