How to Use the Script
Save the script to a file, e.g., system_monitor.sh.

Make the script executable:
chmod +x system_monitor.sh
Run the script manually:
./system_monitor.sh
To run the script periodically, use cron to schedule it. For example, to run the script every 5 minutes, add the following line to your crontab:
crontab -e
