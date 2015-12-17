Lets Node - Course Prerequisites
================================

Please complete the following steps before taking the course:

1. Make sure you have basic understanding of the Javascript language: **objects**, **prototype**, **functions**, **context** etc.

2. Download and install the current version of NodeJS on your machine:
    * Windows & Mac OS X users can download and use the installer from [here](http://nodejs.org/download/ "Download NodeJS")
    * Linux users can download and use the binaries from [here](http://nodejs.org/download/ "Download NodeJS") OR:
        * Ubuntu users can run the following commands:
         
             ```
             apt-get install python-software-properties
             apt-add-repository ppa:chris-lea/node.js
             apt-get update
             apt-get install nodejs
             ```
        * CentOS/RHEL users can run the following commands:         
         
             ```
             yum -y update
             yum install -y npm --enablerepo=epel
             ```
             OR
             ```
             yum -y update
             rpm -Uvh http://download.fedoraproject.org/pub/epel/6/i386/epel-release-6-8.noarch.rpm
             yum install -y npm
             ```

3. Open Terminal/Command Prompt and type:
     
     ```
     node -v
     ```
   Output should be equal to 'v0.10.28'
   
     ```
     npm -v
     ```
   Output should be equal to '1.4.9'
   
   Sets your user account as the owner of the /usr/local directory, so that you can just issue normal commands in there.
   This will allow using npm -g with no sudo.
   Type:
   
      ```
      sudo chown -R $USER /usr/local
      ```
   
4. Make sure you have a **Git** client installed on your machine and that you can easily clone git repositories, if not, do as follows:
    * Windows users can download and use the installer from [here](http://msysgit.github.com/ "Download Git")
    * Mac OS X users can download and use the installer from [here](http://sourceforge.net/projects/git-osx-installer/ "Download Git")
    * Ubuntu users can run the following command:
         
         ```
         apt-get install git
         ```
    * CentOS/RHEL users can run the following command:
         
         ```
         yum install git-core
         ```
         
5. Make sure you run the WebServer and the TCPServer examples, Do it as follows:
    * Open Terminal/Command Prompt and Run the following commands
         
         ```
         git clone https://github.com/itkoren/Lets-Node-prerequisites.git prereq
         cd prereq
         node webserver.js
         ```  
    * The output should be - "Server running at http://127.0.0.1:1337/"
    * Open your favourite browser, and navigate to http://127.0.0.1:1337/
    * The output should be - "Hello World"
    * Press Ctrl+C twice and run the following command: 
         
         ```
         node tcpserver.js
         ```
    * No output should be seen
    * Open another Terminal/Command Prompt and type:
        
        ```
        telnet localhost 1337
        ```
    * The output should include: "Echo server"
        
6. Make sure you have **IntelliJ IDEA** IDE or **WebStorm** IDE, installed on your machine, together with the NodeJS Plugin - Although you are free to use the IDE of your choice, I'll be using one of those IDE's during the course, and I am not going to deal with debugging problems on other IDE's during the course

7. **Windows users**: make sure you have **PuTTY** installed on your machine, if not, download and use the installer from [here](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html "Download PuTTY")



#####*If you've completed all the above - You are ready to Node!!!*
