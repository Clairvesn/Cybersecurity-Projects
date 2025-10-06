Splunk DNS Ingestion & Analysis in Ubuntu VM

##Overview
This project demonstrates how I configured a Ubuntu VM in VirtualBox to share files with my host and ingest DNS logs into Splunk for analysis.

## ⚙️ Steps Performed

### 1. Environment Setup
- Installed Ubuntu on Oracle VirtualBox.
- Installed VirtualBox Guest Additions for full integration.
- Created a **shared folder** between the host (Windows) and the virtual machine (Ubuntu) for easy file transfer.

### 2. Shared Folder Configuration
- Mounted host **Downloads** folder in Ubuntu at `/media/sf_Downloads`.


**3. DNS Ingestion into Splunk**
- I went to the site that the Splunk web interface was at: http://UbuntuVM:8000
- Then created an account, uploaded the DNS sample logs(found on Rajneesh Gupta's GitHub)
- Ran searches to visualize DNS activity.
