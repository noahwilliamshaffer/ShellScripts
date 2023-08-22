# sftpScript
This repository contains a short bash script and a batch file for sftp automation.

This script was written for my personal use on macOS to locally save files from my school's remote machine.
In order to run, a few things must be done.
First, all comments must be removed from the batch file as comments are not supported.
Second, you will need to set up a ssh key using ssh-keygen if your account on the remote machine is password protected. 
I accomplished this with the commands 'ssh-keygen' and 'ssh-copy-id -i ~/.ssh/id_rsa.pub user@host'
For more details regarding setting up ssh keys visit https://www.ssh.com/academy/ssh/keygen.
Next, go find your bash file in finder, select 'Get info' for the file, and unlock the file.
Lastly, in your terminal, convert the bash script to an executable using the command 'chmod 700 sftpBash'.

And you're all set. Run the executable by opening the file in macOS or by using the command './sftpBash', now enjoy automated file transfers.
