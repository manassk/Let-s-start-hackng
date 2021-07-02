# **LET&#39;S START HACKING**

We are going to hack metasploitable using kali linux. Firstly we have to see the IP of metasploitable.

The IP is 192.168.29.75

![](https://github.com/wolff02/Let-s-start-hackng/blob/main/Metasploitable.png)

So lets check the open ports of Metasploitable.

![](https://github.com/wolff02/Let-s-start-hackng/blob/main/open.png)

We have got these much of open ports but we need port 21 ftp protocol. Now we used msfconsole and used the following commands.

use exploit/unix/ftp/vsftpd\_234\_backdoor

set RHOST 192.168.29.75

exploit

![](https://github.com/wolff02/Let-s-start-hackng/blob/main/exploit.png)

After exploitation we are now connecting to the command line of metasploitable.

![](https://github.com/wolff02/Let-s-start-hackng/blob/main/msf.png)

Now we are connected to the commandline of linux. Now we can run the commands. Here I created a new directory using mkdir.

![](https://github.com/wolff02/Let-s-start-hackng/blob/main/new%20dir.png)

So this is the metasploitable commandline where the marked directory is the file created in Kali linux.
