# Gaining root and installing a custom rom on the M3 Note - M681H

Steps to gain root and in the future hopefully install a custom rom.

# Disclaimer
I am not responsible for any damage caused by this guide, this is just a project of mine and doesn't mean you need to follow along with me, if the phone bricks it's not my fault, especially if you have a different model M3 Note to me.

I am free from liability for any risk or consequence from following this guide.

By continuing through this guide, and doing the aforementioned steps you agree to these terms.

Make sure that you read over the Disclaimer for Open System Permissions, linked here.

# Model and Verison
At the start of the project, My M681H M3 Note is running Android 5.1, Flyme 6.3.0.0G.

# Why?
## Why would I want to install root and overwrite the stock rom?
Well of course it's always fun doing this process anyway, but there are some reasons for this phone, some users have reported their Meizu phones running Flyme as having Chinese spyware, in the form of preinstalled apps. This in some cases is very much true. 
Some Meizu devices even report (in the form of a notification) their own system apps (In my case my M6 Note settings were reported as dangerous software).
These phones seem to be no longer supported, as updates are no longer pushed to the devices. Leaving these capable phones stuck on Mesozoic versions of Android.

# Let's get started!

With all of that out of the way, let's get started!! Our goal is to gain root access, in the future, we will unlock the bootloader, and install TWRP.

All APKs used in this guide, as well as VirusTotal scans, are located in the [APK folder](https://github.com/OfficialJavaScript/Root-and-Rom/tree/main/M3%20Note/APK)

Here's a link to the video version: [CLICK](https://drive.google.com/file/d/17MBOBE_WYpkQ_3-AU08JfYW2rk1Pw_Xb/view?usp=sharing) (I recommend you check this out as well as the instructions below) 

1. Backup all of your files, as a precaution.
2. Login (or Signup) to your Flyme Account --- I think this step is necessary, but I can't remember, the process is similar to the M6 Note so I'm trying to remember off the top of my head 😅
3. Install the MeizuAccount.apk attached in this repository, the preinstalled version for some reason doesn't let you obtain root through the method we use here.
4. Install the QuickShortcutMaker.apk attached in the repository.
5. Enter Easy Mode, this is accessible by opening Settings, then scrolling down to the device section, selecting 'Easy Mode', then pressing 'ENABLE'.
6. Open QuickShortcutMaker, and migrate to the 'Activities' tab.
7. Find the 'Flyme' app there, below it, will say 'com.meizu.account' click on this (to open the dropdown menu)
8. Scroll down until you find the com.meizu.root.OpenSystemRightActivity option, click on this.
9. I like to press the 'Try' button, this will show a message "Sorry. You cannot launch this activity from this app because it requires some additional permissions to launch." Don't worry this is a good sign, it actually means that you have followed all of the previous steps correctly.
10. Press 'Create', it will then exit the application and add a 'Flyme' icon/app to your home screen.
11. Click this application, it will then show the 'Disclaimer for Open System Permissions'. You can read that [here](https://github.com/OfficialJavaScript/Root-and-Rom/blob/main/M3%20Note/Disclaimer%20for%20Open%20System%20Permissions.md). 
12. Please make sure that you read through the disclaimer.
13. If you agree to these terms press Accept, then ok, your phone will be restarted, I don't believe it wipes the phone.
14. If you do not agree to these terms, close the application immediately, and stop following this guide.
15. Continuing from step 13, once your phone has started you should be successfully rooted, install the attached RootChecker.apk
16. Once the application is installed and agree to its disclaimer, then go through the Get Started guide.
17. Click Verify Root, and allow the root permissions request, it may give you a warning about Third-Party access to root, I allowed it, if you disallow it, the application won't gain access to root.
18. Now we are going to create a Root Permission Shortcut, to do this open the QuickShortcutMaker application and Go to the Activities tab.
19. Click the 'Input keyword to filter' option, and type "root", a settings option should appear, click that to open the drop-down menu.
20. Click the 'Root Permission' "com.meizu.settings.MzSettingsActivity$RootPermissionSettingsActivity" option and create the shortcut.
21. Now you should have a shortcut named "Settings" - you can change the name of this when creating it, after clicking on the "com.meizu.settings.MzSettingsActivity...." option at the top there should be a "settings" 'tap to change label' option.
22. Opening this shortcut you should be able to make Applications 'Ask', 'Allow' or straight up stop the root permissions with 'Disallow'
23. You should now be successfully rooted, I hope this helped!

If you have any problems or questions, don't be afraid to open an issue, I will reply to you as soon as I can, I may not be able to answer every question.