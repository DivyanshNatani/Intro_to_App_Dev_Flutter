# Flutter Installation

https://flutter.dev/docs/get-started/install

This is the official documentation of flutter Installation. Almost every video tutorial will have reference to this link and this documentation is well defined so you can go through this along with any video-tutorial.

## Dependencies

For flutter installation you will need
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) : You can follow video [Windows 10](https://www.youtube.com/watch?v=2j7fD92g-gE), [Mac](https://www.youtube.com/watch?v=LK0vMt_lEbQ) and [Ubuntu](https://www.youtube.com/watch?v=gdgravCh_Bw)

For Android Studio
- Java Development Kit(JDK): If you have JDK (8 or above) installed then you can ignore. If you dont, then you need to install JDK and set up JAVA_HOME envirnment variable. Follow this [Youtube tutorial](https://www.youtube.com/watch?v=IJ-PJbvJBGs)
  ### __NOTE__ : 
  JDK 16(latest version of JDK) doesn't work well with gradel(a android studio dependency). So, download JDK 15 or earlier. [Drive link for JDK_15.0.2 setup](https://drive.google.com/drive/folders/1v-4kjKhpyop36jtQ0yJ7CkOtYbocqsMZ?usp=sharing). or you can search for JDK <version you require>, sign up for oracle account and download the installer.
  
 
## Installation Guide
  
  Installation doesn't take much time compared to time required to download the packages. ([Android Studio Installer](https://developer.android.com/studio) is ~900MB, so download it ASAP, don't leave it for actual installation) 

  Follow the [Flutter Installation Documentation](https://flutter.dev/docs/get-started/install).
  
  Video Tutorial for installation
  - [Windows 10](https://www.youtube.com/watch?v=fDnqXmLSqtg)
  - [Mac OS](https://www.youtube.com/watch?v=fDnqXmLSqtg)
  - [Ubuntu](https://www.youtube.com/watch?v=GFh4xNVLzUM)
  
  
  Check installation by running 
  ```
  flutter doctor
  ```
  
__Note__ : Setting up VS Code for Flutter is optional, you can use Android Studio Editor as well.
  
## Sorting Errors
  Things might not go as shown in above videos and you might get various errors.
  
  
  Most of these errors are because of incorrect PATH or PATH_VARIABLES (like [ANDROID_HOME](http://www.automationtestinghub.com/setup-android-environment-variables/)) or flutter/android studio is not able to locate required SDKs. 
  
  Greatfully, these are not rare errors and help is available on Internet. Just google the exact error you are getting and you might get a stackoverflow or GitHub thread for same.   Checkout those thread.
  ##
  
  These are some of the common errors and solution link that might help. Note that, we can work as community to help each other out. If you face any error and solve it, then add the article here (Just put a PR!).  
  - [Android SDK cannot be found by flutter](https://stackoverflow.com/questions/44485848/android-sdk-cannot-be-found-by-flutter)
  - [[tag][!] Android Studio (not installed) , when run flutter doctor while Android Studio installed on machine](https://stackoverflow.com/questions/59647791/tag-android-studio-not-installed-when-run-flutter-doctor-while-android)
  - [Flutter does not find android sdk](https://stackoverflow.com/questions/49175231/flutter-does-not-find-android-sdk)
  - [flutter doctor --android-licenses gives a java error](https://stackoverflow.com/questions/61993738/flutter-doctor-android-licenses-gives-a-java-error/66363044)
  - [flutter doctor --android-licenses gives a java error ALITER](https://stackoverflow.com/questions/46402772/failed-to-install-android-sdk-java-lang-noclassdeffounderror-javax-xml-bind-a)
  
  
  
