# ssh_tunnel
easy open and close ssh tunnel

1 - git clone
2 - pip3 install psutil
3 - mv ssh_tunnel/ssh_tunnel /usr/local/bin

use and example:
$ ssh_tunnel 2222 22
tunnel from localhost to server's port 22  
for close tunnel:
ssh_tunnel 2222 k
"k" for kill and 2222 is local port


more example:
ssh_tunnel 3306 3306

this use for connect to mysql in server from localhost:3306

and close with :
ssh_tunnel 3306 k
