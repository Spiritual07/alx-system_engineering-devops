Command line for the win

Open a terminal or command prompt on your local machine.

Initiate an SFTP connection to the sandbox environment

Once connected, navigate to the directory on the sandbox environment where you want to upload your screenshots. For example:
cd /path/to/sandbox/directory

On your local machine, navigate to the directory containing the screenshots you want to upload. For example:
cd /path/to/local/screenshots

Use the put command to upload the files. Replace file1.png and file2.png with the actual filenames you want to transfer:
put file1.png
put file2.png

If you want to upload all files in the local directory, you can use a wildcard:
put *

After uploading the files, you can use the ls command to verify that the files are present in the remote directory:
ls
This command lists the files in the current remote directory.

When you are done transferring files, type exit to close the SFTP session:
exit

That's it! You've successfully used the SFTP command-line tool to transfer files from your local machine to the sandbox environment. Adjust the commands and paths based on your specific environment and file locations.

