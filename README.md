QuizUP
===================

Mobile app for FBLA Mobile App Design, will be displayed for judges at the Wisconsin FBLA State Leadership Conference

Introduction
-------------
QuizUP is a mobile app that quizzes you on a variety of FBLA topics. It has account mode where scores can be saved to the cloud database and guest mode for users who'd rather not create an account. In addition, QuizUP works offline so users don't need an Internet connection to test their FBLA knowledge. 

Useful Links
-------------

 - [Screenshots](https://github.com/gzimbric/fblamobileapp2018/blob/master/quizup_photos.pdf)
 - [IPA Download](https://github.com/gzimbric/fblamobileapp2018/raw/master/fblamobilequiz.ipa)

Features
-------------

 - Authentication (Over SSL)
 - Login, Register, and Reset password pages
 - Full UI
 - Artwork (Logo, appicon, etc)
 - Full Slide-To-Refresh support on posts
 - Guest mode for userless login
 - Score tracking with lastest score and high score
 - Online documentation within app
 - Fifteen questions based on five different FBLA topics in quiz format
 
Requirements
-------------
 - An iOS device/simulator running iOS 12.0 or higher
 - Xcode 10.1 or higher
 - An active Internet connection

Installation
-------------
 **In order to install this application a Mac running Xcode with CocoaPods will be needed.**
 1. Make sure CocoaPods is installed on the development computer. Install Guide can be found here: https://guides.cocoapods.org/using/getting-started.html
 2. Open the archive and click on `fblamobilequiz.xcworkspace`
 3.  Once the project is loaded, select a device from the drop-down near the top-left corner (This can be a simulator or a real device)
 4. Once a device is selected, press the icon that is very similar to a play button to run the project.
 5. If running on an actual device, make sure to accept any prompts so the app builds correctly. You also may need to go to Settings -> General -> Profile & Device Management -> Look under 'Developer Apps' -> Accept QuizUP<br>
**Note:** If running on a device, make sure it is unlocked before it is plugged in.

**In addition, QuizUP can also be installed using the precompiled IPA listed above**

Signing Fix
-------------
After downloading the .zip file you will most likely need to change the signing settings of the app.
 1. Click 'fblamobilequiz' at the top of the left sidebar with the blue project icon to the left of it.
 2. If done correctly, a new window will open. From the left sidebar of that window, look for 'fblamobilequiz' under 'Targets' and click it.
 3. Under 'General' look for 'Signing' and fix any signing issues by selecting/creating your own team. You may have to enter your Apple ID during this step.

Software Used
-------------

 - Xcode - IDE used to develop iOS applications
 - Swift - A fairly new programming language used within iOS applications
 - Firebase: A highly scabable realtime database used for QuizUP's backend

When developing QuizUP, I used Xcode by Apple as my IDE (Integrated Development Enviornment) and I also used the lastest version of Swift (Version 4.2.3 at publish date) as my programming language. I used CocoaPods to easily install Firebase to connect to my backend and my graphical UI knowledge to build the app's design.

Sources
-------------

When I first approched doing this FBLA event, I knew that Swift would be a great language to program in. However, I didn't have a great amount of knowledge with Swift and the backend I planned on using (Firebase), so I referred to some of the tutorials from the YouTube user 'TheSwiftUniverse' on gettings started with Swift and Firebase. I also used StackOverflow to look through some already-answered topics to better understand how to use Realtime Database in Swift.

Troubleshooting
-------------

 - *App isn't loading any quiz results or is throwing errors about the 'connection'*<br>
 **A:** Your device isn't connected to the Internet or your connection is weak. Try switching networks, move closer to the Internet source, or connect to the Internet.
  
Copyright
-------------
FundUP was built with XCode, CocoaPods, Firebase, and KingFisher.

 - XCode: Copyright © 2019 Apple Inc. All rights reserved.
 - CocoaPods: Copyright © 2019 CocoaPods. CocoaPods is licensed under the MIT license.
 - Firebase: Copyright © 2019 Alphabet Inc. All rights reserved.
 - Imaging: Copyright © 2019 Future Business Leaders of America-Phi Beta Lambda, Inc. (FBLA-PBL). Imaging was conformed to the FBLA-PBL Trademark & Service Mark Policy to ensure all requirements were met.
