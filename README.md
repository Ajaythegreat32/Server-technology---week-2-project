## Setting up apache
I installed apache on windows by unzipping the apache installation folder into my "C:/" drive. From there I had to install the Setting up apache
I installed apache on windows by unzipping the apache installation folder into my "C:/" drive. From there I had to install Apache as a service by running the "httpd.exe" file with the argument "-k install -n 'Apache2.4'". To start the service, I had to open the apache monitor and and start the service from there. I was then able to view all the files on localhost.

#### Issues
I ran accross a few minor issues across the development of this website. One was that apache wouldn't recognise the "index.htm" file as the site index. To get around this I had to change "DirectoryIndex index.html" to "DirectoryIndex index.htm" in the httpd.conf file
