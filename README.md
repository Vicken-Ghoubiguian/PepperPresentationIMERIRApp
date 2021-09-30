# PepperPresentationIMERIRApp
Application developed for the Pepper robot, manufactured and marketed by the company Softbank Robotics, to present the IMERIR IT and robotics school during various events (trade fairs, open houses...)...

<img src="app_logo.png" data-canonical-src="app_logo.png" width="636" height="273" align="center" />

## Contents

1. [Introduction](#introduction),
2. [Presentation of this project](#presentation_of_this_project),
3. [Application's definition](#application_s_definition),
4. [Git repos's structure](#git_repos_s_structure),
5. [Project's components](#project_s_components),
6. [How was this project developed ?](#how_was_this_project_developed)
7. [How to install it ?](#how_to_install_it)
8. [Manual](#manual)
    * [How to start the application ?](#how_to_start_the_application),
    * [How to stop the application ?](#how_to_stop_the_application).
9. [Issues and bugs](#issues_and_bugs),    
10. [Useful links](#useful_links),
11. [Conclusion](#conclusion).

<a name="introduction"></a>
## Introduction

IMERIR is an engineering school providing training in IT, connected objects, artificial intelligence, maker culture and robotics. By the way, here is its logo:

<img src="project_s_documentation/images_to_display_in_github_repos/introduction/icon.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/introduction/icon.png" width="200" height="200" align="center" />

This school has a humanoid robot known as Pepper. Initially manufactured and marketed by the French company Aldebaran robotics, the production and marketing of Pepper was taken over by the Japanese company Softbank when the latter acquired Aldebaran robotics. Here is an image of this robot so emblematic of humanoid robotics:

<img src="project_s_documentation/images_to_display_in_github_repos/introduction/pepperRobot.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/introduction/pepperRobot.png" width="400" height="700" align="center" />

IMERIR uses the Pepper robot as the school mascot during various trade shows, meetings and professional forums focused on computer technologies and robotics as well as geek culture. 
As shown in some photos below, the Pepper robot from IMERIR is emulated wherever it goes.

<a name="presentation_of_this_project"></a>
## Presentation of this project

<a name="application_s_definition"></a>
## Application's definition

This application is for the Pepper robot to permit it to present the IMERIR school to prospects, cosplayers, professionals and all other interested audiences.
This application:

* use the robot's voice command to allow the interlocutor to ask his question or state his answer,
* display graphical interfaces to allow the interlocutor to make his choice to ask his question or state his answer if there is too much noise,
* interact with the interlocutor using the voice interface while displaying well-designed graphical interfaces to illustrate the point,
* is based on a detailed scenario to explain and question with the corresponding graphical interfaces according to a well-written text,
* is based on a detailed grafcet to establish a rigorous order in the presentation of the explanations and the questions asked as well as the beginning and the end of the program.

__warning__: this application works exclusively on Pepper robots running on the version 2.5 of its OS NAOqi.

<a name="git_repos_s_structure"></a>
## Git repos's structure

<a name="how_was_this_project_developed"></a>
## How was this project developed ?

<a name="project_s_components"></a>
## Project's components

<a name="how_to_install_it"></a>
## How to install it ?

Here, we will show you how to install the PepperPresentationIMERIRApp app on the Pepper robot. 
The process is common to all the other applications to be installed on Pepper, running with version 2.5 of the NAOqi system. In addition, you can have just as ample information just here: https://github.com/Vicken-Ghoubiguian/pepperApplications#how_to_install_an_application_on_the_robot. So let's go...

1. Please turn on the Pepper robot first;

<img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/1.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/1.png" width="452" height="319" align="center" />

2. then wait for the robot to pronounce “Ognak Gnuk” and check its environment, this means that the robot is now on;

<img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/2.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/2.png" width="384" height="512" align="center" />

3. please connect the Pepper robot to the Choregraphe software now. You have to open the software in question to do this.

<img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/3.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/3.png" width="512" height="321" align="center" />

Then click on the button <img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/3_bis.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/3_bis.png" width="42" height="35" align="center" /> indicated on the screenshot below.

<img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/4.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/4.png" width="512" height="321" align="center" />

The window shown in the screenshot below then opens.

<img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/5.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/5.png" width="512" height="340" align="center" />

So please select the robot colored in green (or the one you want which is also colored in green) and then press the “Select” button as shown below.

<img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6.png" width="512" height="340" align="center" />

Let's go back to the interface shown above. In the table on the left, you must choose the robot you want to connect to Choregraphe. In the “status” column, there are several robots, each represented by a head of Nao robots. The dotted robot (opposite <img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6_bis_1.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6_bis_1.png" width="73" height="73" align="center" />) corresponds to the virtual robot, a simulation of the Pepper robot installed by default with Chorégraphe and which is just as interfaceable, controllable and programmable as a physical robot. A real physical Pepper robot is full line and:

* either it is colored green with the eyes open (opposite <img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6_bis_2.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6_bis_2.png" width="73" height="73" align="center" />): you can connect to this robot because its NAOqi OS is running,

* or it is colored red with closed eyes (opposite <img src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6_bis_3.png" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/how_to_install_an_application/6_bis_3.png" width="73" height="73" align="center" />): you cannot connect to this robot because its NAOqi OS is stopped.

4. Now is the time to install the application on the Pepper robot.

<a name="manual"></a>
## Manual

This section is the user guide for the application. This section is the user guide for the application. All the questions you ask yourself about it are discussed there. 
So don't hesitate to take a look at it depending on the question you have, or the problem you are having.

<a name="how_to_start_the_application"></a>
### How to start the application ?

<a name="how_to_stop_the_application"></a>
### How to stop the application ?

<a name="issues_and_bugs"></a>

__Warning:__ By cloning this project from git on the Choregraphe software, a minimal bug is to be noted: by launching the application from the Choregraphe software (button <img src="project_s_documentation/images_to_display_in_github_repos/warnings/warning_1/1.PNG" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/warnings/warning_1/1.PNG" width="37" height="31" align="center" />) or by installing it directly on the robot (button <img src="project_s_documentation/images_to_display_in_github_repos/warnings/warning_1/2.PNG" data-canonical-src="project_s_documentation/images_to_display_in_github_repos/warnings/warning_1/2.PNG" width="38" height="34" align="center" />) to launch it from the tablet, the robot crashes as soon as it executes a "choice" box (a block resembling that and allowing him to ask a question and answer orally). 

<a name="useful_links"></a>
## Useful links

<a name="conclusion"></a>
## Conclusion
