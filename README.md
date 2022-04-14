# script-for-microphone-monitoring-on-Linux-Mint
These are two little scripts for simply monitoring your microphone in Linux Mint with pulseaudio instead of using the terminal everytime!

Note: This one of my first little bash scripts ever written and I don't have a lot of programming knowledge so far, so I'm open for improvements! Also I'm new to commission anything on GitHub!

1. Download the .zip file and extract it in the directory where you want to have it located.
2. Set the [PATH] in the scripts to their location
3. Set the "monitoring_output_delete.sh" file as a start-up programm in the systemsettings in Linux Mint
  -> This script deletes the "monitoring_output.txt" file when starting the computer when the user hasn't deleted it by himself or via the script      
  "monitoring.sh" and acts as a automatic reset without breaking the script
4. Rightclick on the desktop and create a simple launcher by adding the "monitoring.sh" script
5. Have fun hearing yourself!
6. To end it you have to click on the launchericon again
