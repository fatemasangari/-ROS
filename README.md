# -ROS

Step 1: Install VirtualBox
1. Go to www.virtualbox.org and download the newest version of VirtualBox 
2. Install VirtualBox
3. Download Ubuntu 16.04 (Xenial) as ISO file - https://releases.ubuntu.com/16.04/
4. Run VirtualBox and create a new VM (Virtual Machine)
5. Name the Guest OS - Ubuntu (version) > click Next [Image 1]
6. Allocate RAM for Guest OS
7. Create a Virtual Hard Disk 
8. Select VDI > click Next 
9. Configurating the Type of VD (Virtual Disk) 
10. Create the Virtual Machine


Step 2: Configurating the VirtualMachine
1. Go to Settings 
2. Navigate to the Storage options on the left
3. Select Controller:IDE and insert downloaded Ubuntu image (ISO) 
4. Configure the video configuration
5. Set Video Memory in screen tab on maximum
6. Configure the System settings 
7. Set Processor(s) in Processor tab to half of the existing ones

Step 3: Booting and Installing Ubuntu on VirtualBox
1.Install Ubunt
4. Selecting the installation type
5. Set the time zone and the keyboard layout and the login information (Your name, Username, Password )
9. After rebooting, It will be ready to use

Step 4: Install ROS Kinetic Kame
1. Go to http://wiki.ros.org/ROS/Installation
2. Select the ROS inetic Kame
3. Select your Platform (Ubuntu)
4. Transferred to http://wiki.ros.org/kinetic/Installation/Ubuntu
5. Open a Terminal and follow installation steps on the site


7. Step 5: Install Arduino IDE
8. Download the latest Arduino software on your Ubuntu > https://www.arduino.cc/en/Main/Software
3. The file is compressed and you have to extract it in a suitable folder, remembering that it will be executed from there.
4. Open the arduino-1.x.x folder just created by the extraction process and spot the install.sh file > right click on it and choose Run in Terminal from the contextual menu.
5. The installation process will quickly end and you should find a new icon on your desktop

Step 6: Including ROS Library
