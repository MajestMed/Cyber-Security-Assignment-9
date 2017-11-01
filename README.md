# Cyber-Security-Assignment-9 
In this assignment, A MHN admin VM was created as well as a MHN Honeypot VM using Google Cloud Platform. After various instalations, I was able to attack the honeypot using nmap.

Step 1: Create Google Cloud account
Step 2: Create MHN Admin VM
Step 3: Install MHN Admin Application
Step 4: Create a MHN Honeypot VM
Step 5: Install the Honeypot Application
Step 6: Attack the Honeypot
Step 7: Export data

# Honeypot(s) deployed
 A Dionaea over HTTP Honeypot was deployed and attacked.
 https://imgur.com/a/8eJ1E
 
# Issues encountered
 - Unable to download session.json
 experienced errors in both local machine (GCP attempt) and in the MHN admin VM.
 https://imgur.com/a/42PGx

# Summary of Data collected:
After starting the command nmap -sV -P0 35.193.152.53 the MHN login showed over 1000 attacks from nmap from tools such as pcap, epmapper, smbd, mysqld.

# Unresolved questions raised by data collected
I wish I could take a peak at the json file so I can find more information on data collected. But from the attacks I see, I would like to know what these attacks achieved and what information they were able to find.
