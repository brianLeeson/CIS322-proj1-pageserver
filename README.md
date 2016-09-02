Author: Brian Leeson, Email: brianeleeson@gmail.com
CIS 322 Project 1: pageserver


* In this assignment we got:
  * Initial experience with GIT workflow:  Fork the project, make and test changes locally, commit;  turn in repository URL
  * Experience in basic use of Linux Debian and it's command line
  * Initial experience with automated configuration for turnkey installation
  * Extend a tiny web server in Python, to check understanding of basic web architecture
  * Use automated tests to check progress (plus manual tests for good measure)
  * basic understanding of HTML and CSS.
 
To use this project:
  * git clone YourRepositoryURL InstallDirectory
  * cd InstallDirectory
  * make configure
  * make run
 
Additionally "python3 pageserver.py -p 8888" may be run from the command line instead of the cofig file to manual choose a port. Files should be accessible via a browser local to the Pi. http://localIP:port/webpage.html
