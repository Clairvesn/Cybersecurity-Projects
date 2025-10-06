**Overview**
- In this lab, I will be investigating HTTP Logs in Splunk using an HTTP sample log (found on Rajnessh Gupta's GitHub).
- Detect suspicious web traffic activity, client errors, and server errors.

⚙️ Steps Performed
**Environment Setup**
 - Installed Ubuntu on Oracle VirtualBox.
 - Installed VirtualBox Guest Additions for full integration.
 - Created a shared folder between the host (Windows) and the virtual machine (Ubuntu) for easy file transfer.

2. Shared Folder Configuration
- Mounted my host Downloads folder in Ubuntu at /media/sf_Downloads.

3. HTTP Investigation in Splunk
- I went to the site that the Splunk web interface was at: http://UbuntuVM:8000.
- Then logged into my account, uploaded the HTTP sample logs(found on Rajneesh Gupta's GitHub).
- The first task of the actual lab is to find top 10 endpoints generating web traffic.
- The next task of this lab is to count the server code errors.
- Then identify the user-agents(browsers) that a malcious attacker/pen tester used to perform an attack.
- The final task was to find large file transfers. This will be shown in a table format with both the host and server ip address and sorted by response body length. 
   
