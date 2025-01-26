# Safe Mode 

(Insert Table of Contents Here)

Safe mode allows your Windows 10 system to boot into a state in which drivers which are activated is limited and program functionality is at a minimum. This can be used if the computer won’t start under normal circumstances as a troubleshooting step. It can also be used as a means to remove viruses from your system. 

If you are a veteran from Windows 7 or below and are wondering why you can’t press F8 at the windows startup screen to activate safe mode, proceed to the section labeled “Enable Safe Mode Key” in order to reenable this feature if this was your preferred method. It will reenable that functionality. 

## Safe Mode Restart Simple Method

If you can boot into your computer properly to the point of the log in screen, you can access safe mode by doing the following steps. 

1: Right click on the windows icon. 

2: Hold down shift on your keyboard as you click on “Restart”. 

3: You should now be presented with the “Advanced Startup” screen. Click on the “Troubleshoot” option. 

4: Click on Startup Settings. 

5: Click on “Restart” as it pops up. 

6: Once the machine has restarted, a series of options will populate the screen for you to choose from. You have three options to choose from here and you will type the number of which you intend to use. 4 for Safe Mode, 5 for Safe Mode with Networking or 6 for Safe Mode With Command Prompt. What each does will be listed below these steps. 

7: After typing your selected Safe Mode type, your machine will restart and you will be booted into the Safe Mode of your choice. 

### Safe Mode (Regular) 

The standard Safe Mode that has the most limited functionality but all normal desktop visuals.  


### Safe Mode With Networking 

This version of Safe Mode allows you to still access your network and network connected devices, such as cloud drives or other technologies. 

### Safe Mode With Command Prompt 

The most bare version of Safe Mode which doesn’t even load the visuals and instead simply gives you a command prompt to run commands. Most commonly used if graphics drivers are failing at the highest levels or the user wishes to minimize system usage. 

## Safe Mode Through Settings App

1: Select the search bar or the windows button at the bottom left of the screen.

2: Type “Settings”. 

3: Click on “Settings”. 

4: A new menu should open up called “Settings”. Click on “Update and Recovery”. 

5: The update screen should open. Select “Recovery”. 

6: The recovery section should open. Navigate to “Advanced Startup” and click on “Restart”. 

7: Once the machine has restarted, a series of options will populate the screen for you to choose from. You have three options to choose from here and you will type the number of which you intend to use. 4 for Safe Mode, 5 for Safe Mode with Networking or 6 for Safe Mode With Command Prompt. What each does will be listed below these steps. 

8: After typing your selected Safe Mode type, your machine will restart and you will be booted into the Safe Mode of your choice.


## Safe Mode Through System Configuration Tool

1: Navigate down to the search bar or the windows button. 

2: Type into the bar: “msconfig”. Click on the program that pops up. A new menu will open. 

3: Click on the “boot” tab within the new menu. 

4: Under boot options, select with your mouse “Safe Boot”. Select Minimal for normal Safe Mode or Network to launch Safe Mode With Networking. 

5: Click on apply. 

6: Click on “ok”. 

7: When the new window pops up, select restart with your cursor and click it. 

8: Your machine shall now restart into Safe Mode. 

9: When done, open “msconfig” again at the search bar, go to the boot tab and uncheck “Safe Boot”. Hit apply and then close to boot normally again. 


## Safe Mode Automatic Method

### Please note that the ability to enter this mode will likely be determined by the speed of your hard drive. If it is an HDD (Hard Disk Drive), then this method should be simple. If it is an SSD, it may be hard to get the timings right and it may be simpler to use other methods. 

1: Ensure your computer is off. 

2: When the Windows 10 Logo appears, hold down the power button until the system turns off. Do this 2 more times (3 total times). 

3: Turn on your PC for the 4th time and it should now begin automatic repair. Wait for Windows to diagnose your PC. 

4: A new menu will open called “Startup Repair”. Select “Advanced Options”. 

5: You should now be presented with the “Advanced Startup” screen. Click on the “Troubleshoot” option. 

6: Click on Startup Settings. 

7: Click on “Restart” as it pops up. 

8: Once the machine has restarted, a series of options will populate the screen for you to choose from. You have three options to choose from here and you will type the number of which you intend to use. 4 for Safe Mode, 5 for Safe Mode with Networking or 6 for Safe Mode With Command Prompt. What each does will be listed below these steps. 

9: After typing your selected Safe Mode type, your machine will restart and you will be booted into the Safe Mode of your choice.

## Safe Mode At Startup

### Accessing Safe Mode at startup means accessing Safe Mode at system startup as opposed to logging in and using the easier Windows 10 methods. Unfortunately, Windows 10 does not have a built-in functionality to allow you to enter the state under normal circumstances and this must be done beforehand to allow it’s use. 

## Step 1: Enable Safe Mode Key

1: Open Command Prompt by navigating down to the search bar or the windows button. 

2: Type “CMD” into the search bar 

3: Hover your mouse over to the program name and then right click it with your mouse. Hit “Run As Administrator”. 

4: You will be greeted with a black box that should say the following: “C:/Windows/system32”. (This may also say System 64 if you are using a 64 bit version of Windows 10.)  

5: Copy this command into the line: “bcdedit /set {default} bootmenupolicy legacy”. Type enter. 

6: The following picture should be displayed. You have successfully enabled Safe Mode’s button press command. If this fails, ensure that you ran the program as outlined in #2 and #3. 

## Step 2: Boot Up

First begin by turning on your computer. As this process begins, press the F8 key repeatedly to access the following screen. 

Select the version of Safe Mode that suits your needs in the moment and the system will restart once again. You have successfully booted into Safe Mode. If the menu below does not pop up and instead it boots up normally, the button was likely not clicked fast enough.

### Note: No AI was used in the creation of this project. However, due to the nature of the fact this guide requiring turning off your own machine and accessing menu's without "Print Screen" functionality, third party images were used in some instances. They are listed below. 

# Image Sources (For Those Not My Own) 

https://ms.codes/blogs/windows/what-is-safe-mode-in-windows-10 

https://www.drivereasy.com/knowledge/how-to-enter-safe-mode-in-windows-10/

https://www.tenforums.com/attachments/tutorials/259099d1576354505-boot-advanced-startup-options-windows-10-a-3-startup_options.jpg

https://ms.codes/cdn/shop/articles/b6f591d9-227c-8ef1-80bc-5139e82b62ac.png?v=1709223211

https://i.ytimg.com/vi/TwIOazT1BxU/maxresdefault.jpg

https://images.drivereasy.com/wp-content/uploads/2016/03/advanced-options-2-1.jpg
