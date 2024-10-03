# display-link-fix
Fix DisplayLink on Ubuntu 22.04 and 24.04 when the second monitor is not detected


Open terminal and run

sudo displaylink-installer uninstall
sudo apt remove displaylink-driver
sudo apt remove evdi
sudo apt install displaylink-driver
