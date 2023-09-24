The following procedure was used to upload the files.

SFTP was used to log into the remote server.

Navigate to the remote directory to be used to store the files.

cd /home/ALX/command_line_for_the_win

Confirm that the local directory is the right one with the files

lls

Put the first file to the remote directory:

 put 0-first_9_tasks.jpg

Verify that the file has been moved

ls

Put the second file to the remote directory:

put 1-next_9_tasks.JPG

Put the third file to the remote directory:

 put 2-next_9_tasks.jpg

Verify that all the files have been copied successfully:

lls
