# FINAL-YEAR-PROJECT
PASS AND HASH ETCS

#Start/Check Wazuh Services
#sudo systemctl start wazuh-manager
sudo systemctl start wazuh-indexer
sudo systemctl start wazuh-dashboard

#Then verify:
sudo systemctl status wazuh-manager
sudo systemctl status wazuh-indexer
sudo systemctl status wazuh-dashboard

#TO Check Kali IP
#ip a

#On Windows, Start Wazuh Agent Service
Win + R
services.msc
Wazuh Agent -> START/RESTART
