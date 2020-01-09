# ROS_Workshop_ITECH2020
## Introduction
Dear participants,
I am defining some basic requirments that I need you to fullfil before the workshop as well as some basic questions I need you to answer. Like that I will be hopefully able to prepare the right content for you.
ROS is very powerful and very flexible although it is of course not a golden bullet. It gives you a basic communication framework and it has a lot of packages that will make your life easy.
Some of the packages we will cover during the workshop (I am open to suggestions). Please try to prepare a problem or project (your thesis, seminar project etc.) for which you would like to use ROS for. 
Some examples: 
- I would like my robot swarm to be able to communicate their position to each other. 
- I want to collect a sensor data from numerous different sensors and interprent the data.
- I want to be able to communicate with a KUKA arm and visualize its position in a Unity app.

The workshop will be divided into three parts:
1. I will summarize the basic ROS functionalit in a short presentatins and we will go over your problems and questions that arised during your preparation.
2. We will write some simple ROS nodes together and go over a communication with some common hardware and software platforms (Grasshopper, Arduino, Unity etc.)
3. We will go over your projects and try to develop a solution for your problems (or at least I will try to point you in a right direction)

## Questionaire
You can work in groups during the workshop but I need you to answer the following questions on your own (be honest please): 

*How well do you know python?*
1. I know that python is a kind of snake
2. I tried to do some scripting in Rhino but it is not my thing
3. I am comfortable using Python for handling geometry in Rhino/Grasshopper
4. I am writing basic scripts using external libraries even outside Rhino/Grasshopper environment
5. I know how Python works, I know the ups and downs of python interpreter and I know when to use egg, spam and ham.

*Can you work with Unix-like OS (OS X, GNU/Linux, etc.)?* 
1. Unix who?? OS what?
2. I know GNU/Linux or OS X but I've never really worked with it.
3. I am used to work with Unix-like OS but I rarelly interface with the system through the terminal.
4. I am using Unix-like OS regularly as my dev environment. 
5. I know that GNU's not unix and I know how to exit Vim. In fact I am using Windows only because I have to.

*Are you a good programer?*
1. Nope sorry. My experties lies somewhere else.
2. I am ok with writing simple programs and scripts I guess. 
3. I know quite well at least one programing language and I know how to write a proper object oriented program.
4. I know several programing languages and I know how when to use which. Most of the common design patterns are known to me.
5. I am well respected on stack overflow. Nuff said.

*What platforms I want to use with ROS? (you can specify up to three of them)* 
1. Grasshopper
2. Arduino
3. Raspberry Pi
4. Unity
5. KUKA
6. Other (specify)

Please send the projects proposals and answers to me as soon as possible.

## Prerequisites
The preferred setup is the one I will be using during the workshop on my computer. If you want to use some other setup (Raspberry Pi, differen GNU/Linux flavor etc.) you are welcome to do so but don't expect my support if things don't work as they should.

*Install ROS*
1. Install the newest version of Oracle's VirtualBox for your host including the extension pack: https://www.virtualbox.org/manual/ch02.html
2. Install the latest Ubuntu LTS version (Bionic Beaver): https://ubuntu.com/download/desktop
   - If you are lost here is a good step by step installation guide (allocate at least 16gb on your hard drive): https://itsfoss.com/install-linux-in-virtualbox/
3. Install the latest Desktop-Full ROS LTS version (Melodic Morenia). Don't be scared if you don't understand the process completely, just copy paste the commands in the terminal: http://wiki.ros.org/melodic/Installation/Ubuntu
4. Create ROS workspace: http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment#Create_a_ROS_Workspace
5. Install catkin_tools: https://catkin-tools.readthedocs.io/en/latest/installing.html

*Install Visual Studio Code:*
1. Install VSCode for Ubuntu from a .deb package (substitute the <file>.deb with the actual name of the deb package that you downloaded): https://code.visualstudio.com/docs/setup/linux
2. Open VSCode and install the following extensions (how to install extensions: https://code.visualstudio.com/docs/editor/extension-gallery):
   - Python: https://marketplace.visualstudio.com/items?itemName=ms-python.python
   - ROS: https://marketplace.visualstudio.com/items?itemName=ms-iot.vscode-ros
   - GitHub: https://marketplace.visualstudio.com/items?itemName=KnisterPeter.vscode-github
   - CMake:
   - If you want the exact same look as mine then download the following color and icon theme:
     - https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark
     - https://marketplace.visualstudio.com/items?itemName=qinjia.seti-icons

*Additional linux packages and setup:*
vim, screen, python-pip, ros-melodic-rosserial-arduino
sudo pip install virtualenv
mkdir ~/.virtualenvs




## Reading list
*Mandatory:*
1. M. Quigley et al., “ROS: an open-source Robot Operating System,” ICRA Work. open source Softw., vol. 3, no. 3.2, p. 5, 2009.
2. J. M. O’Kane, A gentle introduction to ROS, no. 2.1.3. 2016.	

*Optional:* 
1. E. Gamma, R. Helm, R. Johnson, and J. Vlissides, Design Patterns: Elements of Reusable Object-Oriented Software. Addison-Wesley, 1994.
   - On a second thought this book is a bit too complex and require some knowledge of programing. 

*Online:*
1. ROS Tutorial page: http://wiki.ros.org/ROS/Tutorials

*Uderstand the following terms:*
- client-server model
- peer-to-peer model
- publisher-subscriber messaging pattern
- request-reply messaging pattern

