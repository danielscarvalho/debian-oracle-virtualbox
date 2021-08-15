# debian-oracle-virtualbox

Setup do Oracle VirtualBox: https://www.virtualbox.org/

Setup do Debian: https://www.debian.org/

WEB development enviroment for Java EE

Vídeo no YouTube: [>>](https://www.youtube.com/watch?v=MO2RlDhJnOA&ab_channel=DanielCarvalho)

Install: 

sudo apt-get install build-essential linux-headers-\`uname -r\` dkms<br>
cd /media/cdrom<br>
sudo VBoxLinuxAdditions.run<br>
sudo apt install openjdk-11-jdk

Host: Linux Ubuntu<br>
Oracle Virtual Box<br>
Debian (VM)<br>
VirtualBox Guest Additions<br>: https://linuxize.com/post/how-to-install-virtualbox-guest-additions-on-debian-10/

    1. JDK 16+ → Oracle: https://www.oracle.com/java/technologies/javase-jdk16-downloads.html
       
    2. Apache Tomcat: https://tomcat.apache.org/download-10.cgi

    3. Apache Maven: https://maven.apache.org/download.cgi
       
    4. Eclipse: https://www.eclipse.org/downloads/
       
    5. Git: apt get git
    6. curl: apt get curl
    7. wget: apt get wget

.profile
<pre>
export JAVA_HOME=/opt/jdk-16.0.2
export CATALINA_HOME=/opt/apache-tomcat-10.0.10
export PATH=$PATH:$JAVA_HOME/bin:/opt/apache-maven-3.8.1/bin
export CLASSPATH=$JAVA_HOME/lib:$CATALINA_HOME/lib
</pre>

Reference:

- https://www.brianlinkletter.com/2012/10/installing-debian-linux-in-a-virtualbox-virtual-machine/
- https://www.virtualbox.org/manual/UserManual.html
- https://www.veeam.com/blog/why-virtual-machine-backups-different.html
- https://www.debian.org/
