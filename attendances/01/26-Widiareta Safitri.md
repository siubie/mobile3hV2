# Android Fundamental

## Definition of Android
Android is software Software stack for mobile devices. In detail, Android is the name of the operating system used on many smartphones and tablets owned owned and maintained by Google. Google bought Android in 2005 and launched it for phones and tablets in 2007, the same year Apple released the first iPhone. In android there are SDK SDK (Aoftware Development Kit) which provides tools and APIs to develop apps

## Major Component Of Android:
1. Applications
<br>
Applicaton ships with core set of apps, written in Java
Developers have access to core APIs like views used to build application, content providers, resource manager, notification manager, and activity manager  .


2. Aplication Framework
<br>
 	In Android there are several application framework such as:
	 - activity manager
	 - windows manager
	 - View System
	 - Location manager
	 - etc.

3. Libraries 
<br>
	In Android there are several liraries such as:
	- C/C++
	- Media libraries – A/V, images
	- Surface manager – 2D/3D graphic layers
	- LibWebCore – web browser engine
	- SGL – 2D graphics engine
	- 3D – hardware or software acceleration
	- FreeType – BMP and vector fonts
	- SQLite – database engine
	<br>
in libraries there are Android Runtime whis is core libraries and Dalvik Virtual Machine

4. Linux Kernel
<br>
Linux Kernel includes core set of libraries, provides most of core Java libraries, each app runs in its own process. Linux 2.6 is used for core system services


## Main Component Of Android:
1. Activities
	 - Single page user interface
   - Most apps have multiple activities
   - Callable from other apps (if you allow it)

2. Services
	- No user interface
	- Runs in background
	- Started and stopped by activities

3. Content Providers
	- Manages shared set of application data
	- Data may be shared between apps or be private
	- Performs data handling functions

4. Broadcast Receivers
	- Listens for system wide (intent) broadcasts
	- Intent filter limits which intents cared about
	- Similar to an interrupt handler
	- Redirects to appropriate activity or service

## User Interface Basics
- Recall the basic unit of an Android application is an Activity
- An Activity displays the user interface
- User Interfaces are built from View and ViewGroup object instances of the View class
- View objects are data structures that store content and layout parameters 
	- controls a specific rectangular region of the screen
	- responsible for drawing itself
	- handles events


Other resource: <a>https://www.techadvisor.com/feature/google-android/what-is-android-3680422/</a>
