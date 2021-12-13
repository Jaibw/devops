# devops
<pre>
Install JAVA
----------------------
$ sudo apt update
$ java -version 
$ sudo apt install default-jdk
$ java -version 

Install Jenkins 
-----------------------
$ wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
$ sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
$ sudo apt update
$ sudo apt install jenkins
$ sudo systemctl start jenkins
$ sudo systemctl status jenkins
</pre>
