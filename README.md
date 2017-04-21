# Android-LifeCycle
Understanding the Android lifecycle. This tutorial describes how the Android application and activity life cycle works.

**Android Activity Lifecycle**
Android Activity Lifecycle is controlled by 7 methods of android.app.Activity class. The android Activity is the subclass of ContextThemeWrapper class.

An activity is the single screen in android. It is like window or frame of Java.

By the help of activity, you can place all your UI components or widgets in a single screen.

The 7 lifecycle method of Activity describes how activity will behave at different states.

**Android Activity Lifecycle methods**
Let's see the 7 lifecycle methods of android activity.

Method | Description
------------ | -------------
onCreate	| called when activity is first created.
onStart	| called when activity is becoming visible to the user.
onResume	| called when activity will start interacting with the user.
onPause	| called when activity is not visible to the user.
onStop	| called when activity is no longer visible to the user.
onRestart	| called after your activity is stopped, prior to start.
onDestroy	| called before the activity is destroyed.

<br><br>
<a href="url"><img src="https://github.com/sambhaji213/Android-LifeCycle/blob/master/screenshot/Android-Activity-Lifecycle.png"></a>
<br><br>
<a href="url"><img src="https://github.com/sambhaji213/Android-LifeCycle/blob/master/screenshot/home.png" align="left" height="480" width="250"></a>
