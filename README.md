# YorkURemoteLabAutoSync
A shellscript which utilizes fswatch and rsync to automatically sync a directory to the yorku remote lab over ssh.

For the sake of security and good SSH practice, a public SSH key is required for this script to function efficently. Please ensure that you have setup your SSH key on both the host and target. 

This script uses fswatch and rsync as dependencies so ensure that they are also installed. 

To start create the folder which you want to tr
