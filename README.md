# htbdownloadroot
This is for htb seasonal lab "download"  root exploit.

For user you sholud run user.py script and wait for sometimes it will reveal passwd for ssh connection.

Then use this command in your terminal:
gcc exploit.c -o exploit -static
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/7692b3cd-6460-4ade-8c9b-c817482612e6)

##### NOTE: Do this all in '/tmp' dir in wesley terminal. #####
 
After that upload 'exploit' file in '/tmp' dir on Wesley terminal and run the cmd using this ' ./exploit '
After that You got the passwd for psql.

And run this cmd after.                   
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/064e14d7-a671-4061-8167-465e12b72fb9)

Then the last step is:-                          
![image](https://github.com/1cYinfinity/htbdownloadroot/assets/55952519/5c471b6b-b8e1-43a3-b685-c40a2f58c260)


Done you got the #root
