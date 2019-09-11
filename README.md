# apt-local
by Rob Mockler <BR><BR>
 I have decided to share this as I created it many years ago and I have shared it with collegues.
 
 apt-local is an offline apt-get solution.
 
 Ideal for Live Distros where "apt-get update" is not executed, which is the case when a live distro is booted first.
 
 Usage:<BR>
 apt-local install <application>  - search mounted drives and install <application> if found.<BR>
 apt-local search <application>   - search mounted drives and list all <application> candidates.<BR>
 apt-local indexall               - search mounted drives and index all candidates (ideal for removeable media).<BR>
 apt-local mountall               - mount all blkid available drives.<BR>
 
 Usage Examples:<BR>
 apt-local install git  - search mounted drives and install git if found.<BR>
 apt-local search git   - search mounted drives and list all git candidates.<BR>
 apt-local indexall     - search mounted drives and index all candidates (ideal for removeable media).<BR>
 apt-local mountall     - mount all blkid available drives.<BR>
