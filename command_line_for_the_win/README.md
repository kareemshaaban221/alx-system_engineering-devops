# command line with win
-------------------------
## steps
- open terminal in local machine
- navigate to the path of the directory you want to upload
- connect the remote server using the command down below:
```
sftp <usename>@<hostname>
```
- enter the password for the remote server
- navigate to `/root/alx-system_engineering-devops`
- run the command:
```
put -rp alx-system_engineering-devops/command_line_for_the_win
```
- wait for uploading
- that's it! :)