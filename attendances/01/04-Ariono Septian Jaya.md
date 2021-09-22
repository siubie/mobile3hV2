>> What Is Android ?
1.Andoid is a mobile robot usually with a human form. How to use android in a sentence.
2.Software stack for mobile devices
3.SDK provides tools and APIs to develop apps

>>  Major Component
1.Application :
    > core set of apps,that writen in java.
       > Developers have access to core APIs
            - Views used to build application
            - Content providers – access data from other apps
            - Resource manager – access to local strings, graphics
            - Notification manager – display custom alerts
            - Activity manager – manages app lifecycle


2.Application Framework
3.Libraries : 
    > Mention :
       - C/C++
       - Media libraries – A/V, images
       - Surface manager – 2D/3D graphic layers
       - LibWebCore – web browser engine
       - SGL – 2D graphics engine
       - 3D – hardware or software acceleration
       - FreeType – BMP and vector fonts
       - SQLite – database engine

4.Android Runtime :
    > Includes core set of libraries
        > Provides most of core Java libraries
        > Each app runs in its own process

    > Linux 2.6 is used for core system services
        > Abstraction layer between HW & SW stacks

5.Linux Kernel

6.Main Components Of Android :
        > Activities
        > Services
        > Content Providers
        > Broadcast Receivers
    
7.Activity :
        > Single page user interface
        > Most apps have multiple activities
        > Callable from other apps (if you allow it)

8.Services :
        > No user interface
        > Runs in background
        > Started and stopped by activities
 
9.Content Provider :
        > Manages shared set of application data
        > Data may be shared between apps or be private
        > Performs data handling functions

10.Broadcast Receiver :
        > Listens for system wide (intent) broadcasts
        > Intent filter limits which intents cared about
        > Similar to an interrupt handler
            > Redirects to appropriate activity or service

11.Intens
        > Allows an activity, service or broadcast receiver to link to another
            > Within or between apps
            > Allows apps to use components of others
        

