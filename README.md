# Autorotate_sway_script
Auto rotate bash script for sway.

Using the output of the monitor-sensor command (part of the iio-sensor-proxy package)  

Usage example
echo 'monitor-sensor | bash autorotate.sh &> autorotate.log' | at now

Script test and using on lenovo thinkpad helix.
Variable WAYLANDINPUT is array devices input which will be rotated after turning the screen
Device list can be viewed by command "swaymsg -t get_inputs"
