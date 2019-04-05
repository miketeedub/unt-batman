# unt-batman
shell script that connects one wifi adapter to enterprise network and configures the other for BATMAN-adv


I wrote this shell script to enable a raspberry pi to connect to both the school WiFi and create a mesh network with B.A.T.M.A.N-adv.

To Run:

$ ./batsetup.sh user_name your_password ip_address_you_want_for_BATMAN

This is configured to connect to the University of North Texas Wifi. To change to your enterprise network, change the essid to <my network name>

adding an IP address is optional


some of the script is taken from EveningStarNM's reddit post: https://www.reddit.com/r/darknetplan/comments/68s6jp/how_to_configure_batmanadv_on_the_raspberry_pi_3/
