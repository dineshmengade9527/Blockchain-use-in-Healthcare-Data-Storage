# Blockchain-use-in-Healthcare-Data-Storage
IPFS File system is used to implement this Blockchain
#Basic installation steps
1. Download ipfs-go
2. Download JDK8 and install
3. Install Xampp and configure localhost
4. extract it to the file system and add it to environment variables
5. Then run the following commands to check successfull setup of the IPFS on System
    - Open cmd > IPFS init
           cmd> IPFS daemon
           cmd> IPFS block <put file path>  // this is to add file from cmd to IPFS
           cmd> IPFS block get hash <generated in above steps to check the content of uploaded file>
6. Download Eclipse-java8-sr2 from https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/kepler/SR2/eclipse-jee-kepler-SR2-win32-x86_64.zip here or you can go to official web page of Eclipse to download the eclipse
7. Download Tomcat 7 and extract at any place in the system
8. Download this project and extract it anywhere in the system.
9. Open the Eclipse and add workspace as path of the project
10. Go to project properties and in Runtime add it to server
11 then run index.jsp file to start 

