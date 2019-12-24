# Android-Apps
This file contains source codes to my android apps.

## Instructions on how to run each app
1. To install android studio you need to first download and install JDK (Java Development Kit)<br>
2. Next download and install android studio
   
### 1. Installing The Java Development Kit: Windows Guide
#### i. Check If You Have Java on Your Computer
##### Open the Terminal
Before you start, you will need to open a program on your computer called the Terminal. To do this, go to the Task Bar at the bottom of your computer screen, click Start, and navigate to Run...<br>
![Screen Shot 2019-12-23 at 10 51 23 AM](https://user-images.githubusercontent.com/13493736/71372654-3130c280-2572-11ea-96f1-c86f86d3822d.png)<br>

Type cmd in the box that pops up. (Your box might look slightly different than ours, depending on what version of Windows your computer is running.)<br>
![Screen Shot 2019-12-23 at 10 52 21 AM](https://user-images.githubusercontent.com/13493736/71372702-5291ae80-2572-11ea-9fe5-5e098b3116c6.png)<br>
This will open the Terminal window.

##### Use the Terminal to find information
Now you are ready to check if you have the Java Developer Kit, version 7 or greater, already installed on your computer. To check if you have JDK installed (and which version), open a terminal window and type:

java -version

Then hit enter.

The example below shows Java version 8.0_05 -- the version number comes after the “1.”

(Note: As of May 2015, the most recent version was 8.0_45.)<br>
![Screen Shot 2019-12-23 at 10 53 57 AM](https://user-images.githubusercontent.com/13493736/71372798-8e2c7880-2572-11ea-9622-32644252bc6f.png)<br>

If you have Java 7 or greater, you can move on to the next node: Install Android Studio.

If the JDK is not available, or the version is lower than 7, go on to Step 2, below.

#### ii. Download the Java Development Kit
Download the Java Development Kit, aka, the JDK, from this page (http://www.oracle.com/technetwork/java/javase/downloads/index.html).

Oracle, the company that maintains Java, has a lot of options and acronyms. We're looking for the plain old JDK. This is the kit you need to start developing your apps with Java.

As of May 2015, the download icon for the JDK looked like this:<br>
![Screen Shot 2019-12-23 at 10 55 42 AM](https://user-images.githubusercontent.com/13493736/71372889-cb910600-2572-11ea-88a6-db6f247cd7d8.png)<br>

After you click the download link, you'll see a list of options for download. Go to the Java SE Development Kit menu of options. Do not go to the demos and samples (the menus look very similar, so make sure to read the heading at the top).

##### Install
You've got a lot of options here, but the two you care about are the Windows options.

If your computer is only a few years old, you're most likely going to download the 64-bit option. If your computer is a little older you can follow these instructions (https://support.microsoft.com/en-us/kb/827218) to double check.

I'm going to download the 64-bit option (highlighted below).<br>
![Screen Shot 2019-12-23 at 10 57 30 AM](https://user-images.githubusercontent.com/13493736/71373010-0b57ed80-2573-11ea-86a1-2fa24ee2b74c.png)<br>
Accept the license agreement, and download it. Once you've downloaded it, go ahead and double click it to install.

#### iii. Verify that Java is Installed
Go back to Step 1 and follow the instructions to open your Terminal and verify that you have Java version 7 or higher installed.

##### Do not move on with Android Studio install until after you have installed the JDK.
Without a working copy of Java, the rest of the process will not work. If you can't get the download to work, look for error messages, and try googling to find a solution.

Link to Java download site (http://www.oracle.com/technetwork/java/javase/downloads/index.html) <br>

### 1. Installing The Java Development Kit: Mac Guide
#### i. Check If You Have Java on Your Computer
##### Open the Terminal
Before you start, you will need to open a program on your computer called the Terminal. To do this, click the search icon (magnifying glass) on the top right of your desktop, and type in "terminal."<br>
![Screen Shot 2019-12-23 at 11 14 43 AM](https://user-images.githubusercontent.com/13493736/71373740-730f3800-2575-11ea-99c6-cf94d1166bcf.png)<br>
You can also navigate to the Terminal from your Applications > Utilities folder.

##### Use the Terminal to find information
Now you are ready to check if you have the Java Developer Kit, version 7 or greater, already installed. To check if you have JDK installed (and which version), open the Terminal and type:

java -version into the window, and hit enter.

The example below shows Java version 8.0 -- the version number comes after the “1.”<br>
![Screen Shot 2019-12-23 at 11 16 09 AM](https://user-images.githubusercontent.com/13493736/71373804-a5b93080-2575-11ea-8938-023ce8608214.png)<br>
If you have Java 7 or greater, move on to the next node: Install Android Studio.

If the JDK is not available, or the version is lower than 7, go on to Step 2, below.

#### ii. Download the Java Development Kit
Download the Java Development Kit, aka, the JDK, from this page (http://www.oracle.com/technetwork/java/javase/downloads/index.html).

Oracle, the company that maintains Java, has a lot of options and acronyms. We're looking for the plain old JDK. This is the kit you need to start developing your apps with Java.

As of May 2015, the download icon for the JDK looked like this:<br>
![Screen Shot 2019-12-23 at 11 17 42 AM](https://user-images.githubusercontent.com/13493736/71373869-e1ec9100-2575-11ea-9f97-fb0b1888714a.png)<br>
After you click the download link, you'll see a list of options for download. Go to the Java SE Development Kit menu of options.

Do not go to the demos and samples (the menus look very similar, so make sure to read the heading at the top).

##### Install
Select the JDK for your operating system (Mac OSX). In most cases, if you have a machine that is less than 4 years old, you should choose the x64 (64-bit) version (highlighted below). Search online for instructions if you have an older machine and are unsure what version to download.<br>
![Screen Shot 2019-12-23 at 11 18 57 AM](https://user-images.githubusercontent.com/13493736/71373910-09dbf480-2576-11ea-8d49-b2aa3fada08b.png)<br>
Accept the license agreement to download and locate the file, and double click it to begin the installation process.

#### iii. Verify that Java is Installed
Go back to Step 1 and follow the instructions to open your Terminal and verify that you have Java version 7 or higher installed.

##### Do not move on with Android Studio install until after you have installed the JDK.
Without a working copy of Java, the rest of the process will not work. If you can't get the download to work, look for error messages, and try googling to find a solution.

Link to Java download site (http://www.oracle.com/technetwork/java/javase/downloads/index.html)

### 2. Download and Install Android Studio
Make sure you're computer is capable of running Android Studio by checking the system requirements (https://developer.android.com/sdk/index.html?utm_source=udacity&utm_medium=course&utm_campaign=android_basics#Requirements).<br>
If on a corporate network, you may need to Set Your Proxy Settings (https://developer.android.com/studio/intro/studio-config#proxy) or check in with your IT team on help setting up Android Studio.

#### i. Installation Guide: Windows
##### Install Android Studio
Navigate here (https://developer.android.com/sdk/index.html?utm_source=udacity&utm_medium=course&utm_campaign=android_basics), to the Android developers site to install Android Studio. This page will automatically detect your operating system.<br>
![Screen Shot 2019-12-24 at 1 00 12 PM](https://user-images.githubusercontent.com/13493736/71424282-5d6d4180-264d-11ea-9a2c-24512da4fdf0.png)<br>
Accept the terms and conditions to start the download. Double-click the downloaded file and follow all the prompts. Open the downloaded file, and follow the Android Studio Setup Wizard. Accept the defaults configuration for all steps.<br>
![Screen Shot 2019-12-24 at 1 01 26 PM](https://user-images.githubusercontent.com/13493736/71424342-e2f0f180-264d-11ea-8b43-ff89d489ffcc.png)<br>
![Screen Shot 2019-12-24 at 1 05 14 PM](https://user-images.githubusercontent.com/13493736/71424363-12076300-264e-11ea-9cef-251904c1a250.png)<br>
When you reach this screen, make sure that all components are selected.<br>
##### Setup Wizard
After finishing the install, the Setup Wizard will download and install some additional components. Be patient, this might take some time depending on your internet speed.<br>

![Screen Shot 2019-12-24 at 1 06 49 PM](https://user-images.githubusercontent.com/13493736/71424397-50048700-264e-11ea-8b78-6687e49ea36c.png)<br>
##### Install Finished!
When you are finished, you will see this window:<br>
![Screen Shot 2019-12-24 at 1 10 17 PM](https://user-images.githubusercontent.com/13493736/71424443-c1443a00-264e-11ea-8771-68ff3c861490.png)<br>
#### Important Notes<br>
#### Note 1: When you download and install Android Studio the appearance of the windows that you'll deal with may be different from the ones provided above, that's OK as the version you'll download is different from the one that was being downloaded when the screenshots above were taken. So, the overall process is the same.<br>

#### Note 2: For the third screenshot that shows the components, if you get fewer components, it's OK, the most important thing is to have them all selected.<br>

#### Note 3: The setup Wizard above will launch when you try to open Android Studio for the first time to download some additional components, follow-up with the wizard until it finishes and Android Studio launches.<br>

#### ii. Installation Guide: Mac
##### Install Android Studio
Navigate here (https://developer.android.com/sdk/index.html?utm_source=udacity&utm_medium=course&utm_campaign=android_basics), to the Android developers site to install Android Studio. This page will automatically detect your operating system.<br>
![Screen Shot 2019-12-24 at 1 15 31 PM](https://user-images.githubusercontent.com/13493736/71424514-7bd43c80-264f-11ea-9198-85633f071b83.png)<br>
Accept the terms and conditions to start the download. Double-click the downloaded file and follow all the prompts. Drag the Android Studio icon into your Applications folder.

##### Setup Wizard
The setup wizard will setup Android Studio for you.<br>
![Screen Shot 2019-12-24 at 1 16 32 PM](https://user-images.githubusercontent.com/13493736/71424528-a32b0980-264f-11ea-94ce-a3eb827a2329.png)<br>
You can go ahead and choose Standard Setup and accept all the licenses.

##### Install Finished!
When you are finished, you will see this window:<br>
![Screen Shot 2019-12-24 at 1 18 06 PM](https://user-images.githubusercontent.com/13493736/71424552-db324c80-264f-11ea-8aa8-70f7e85e14f5.png)<br>
If you're installing a recent version of Android Studio (from around April/May/June 2015) on a Mac, a standard installation might fail with a bunch of errors. If that happens, try doing a "Custom Setup" instead. Just keep clicking "Next" through all of the custom options (there's nothing you actually need to change) and let it install. If using a custom install doesn't fix your issue, keep troubleshooting and look through discussion posts!


