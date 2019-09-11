# apt-local
Rob Mockler
 I have decided to share this as I created it many years ago and I have shared it with collegues.
 
 apt-local is an offline apt-get solution.
 
 Ideal for Live Distros where "apt-get update" is not executed, which is the case when a live distro is booted first.
 
 Usage:
 apt-local install <application>  - search mounted drives and install <application> if found.
 apt-local search <application>   - search mounted drives and list all <application> candidates.
 apt-local indexall               - search mounted drives and index all candidates (ideal for removeable media).
 apt-local mountall               - mount all blkid available drives.
 
 Usage Examples:
 apt-local install git  - search mounted drives and install git if found.
 apt-local search git   - search mounted drives and list all git candidates.
 apt-local indexall     - search mounted drives and index all candidates (ideal for removeable media).
 apt-local mountall     - mount all blkid available drives.
