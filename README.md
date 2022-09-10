# my-eve-ng-automation
#
# I built this python script to avoid having to manually start lab nodes in the EVE-NG GUI
# You need to add your own credentials and servr IP/name. I have left default admin/eve in this script and a dummy server IP address and lab name I used for testing
# The script starts by logging into EVE-NG and getting a cookie used by subsequent requests
# IT then reads all of the nodes in your lab nd issues a START command
# A response is printed to verify every node comes up
# The script finishes by asking if you'd like to shutdown all of the nodes so you have the option to leave it running while you carry out the lab or can rerun the script at the end of the lab
#
#
#
#
