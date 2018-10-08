# File Transfer Lab

First run `python3 fileServer.py &` to run the server in the background.

Type `python3 fileClient.py` and it will ask you to enter a file name to transfer.

If the file does not exist in the client, it will not be able to transfer it.
If the file already exists in the server (which is in directory 'server-files'), it won't transfer it.

If it was succesful, the file will appear in directory `server-files`.
