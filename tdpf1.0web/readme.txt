README.TXT                                            February 12, 2002

                       TopoDrive and ParticleFlow

      Two Computer Models for Simulation and Visualization of 
  Ground-Water Flow and Transport of Fluid Particles in Two Dimensions 

                              Version 1.0

        for executaion as an applet in a Java 1.1 enabled web browser


                          TABLE OF CONTENTS

                          A. INTRODUCTION
                          B. DISTRIBUTION FILES
                          C. DOCUMENTATION
                          D. EXTRACTING FILES
                          E. INSTALLATION ON WEB SERVER
                          F. RUNNING THE SOFTWARE ON A WEB BROWSER


A. INTRODUCTION

The models TopoDrive and ParticleFlow are developed as Java "applets." As such, 
they can be placed on a web server, allowing user access via the Internet (see
Section E). Alternatively, the models can run within a Java-enabled web browser 
locally on a computer (see Section F). 


B. DISTRIBUTION FILES

The following distribution file is currently available:

tdpf1_0web.exe      -  self-extracting zip file for Windows
tdpf1_0web.tar.gz   -  compressed tar file for extraction on UNIX system


C. DOCUMENTATION

Hsieh, P.A., 2001, TopoDrive and ParticleFlow--Two Computer Models 
for Simulation and Visualization of Ground-Water Flow and Transport 
of Fluid Particles in Two Dimensions: U.S. Geological Survey 
Open-File Report 01-286, 30 p. 

A PDF version of this report is included with the software distribution.


D. EXTRACTING FILES

On Windows, double click tdpf1_0web.exe and follow directions on the screen. 

On Unix, uncompress and extract the distribution file using the command:

         gunzip -c tdpf1_0web.tar.gz | tar xvpof -

In both cases, all files will be under the directory tdpf1.0web.


E. INSTALLATION ON WEB SERVER

To install Topodrive on the web server, copy all the files in the folder 
tdpf1.0web/topodrive to an appropriate folder on the the server. 
(Note that all the files must be in the same folder.) An internet 
user accessing the server should open the file topodrv.html, using an 
address such as
http://my.server.org/folderName/topodrv.html.

To install ParticleFlow on the web server, copy all the files in the folder 
tdpf1.0web/pflow to an appropriate folder on the the server. 
(Note that all the files must be in the same folder.) An internet 
user accessing the server should open the file pflow.html, using an 
address such as
http://my.server.org/folderName/pflow.html.


F. RUNNING THE SOFTWARE ON A WEB BROWSER 

On any operating system that has a Java 1.1 enabled web browser, 
TopoDrive can be run locally from within the browser using the following 
procedure:
   a. Start the web browser
   b. Open the file topodrv.html located in the folder tdpf1.0web/topodrive. 
      This web page also provides instructions on how to use the model.
   c. Scroll down to the heading "Running the Model" and click on the
      text "Click here to run the model".

Similarly, ParticleFlow can be run locally from within the browser using 
the following procedure:
   a. Start the web browser
   b. Open the file pflow.html located in the folder tdpf1.0web/pflow. 
      This web page also provides instructions on how to use the model.
   c. Scroll down to the heading "Running the Model" and click on the
      text "Click here to run the model".


