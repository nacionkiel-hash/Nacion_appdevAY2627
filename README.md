Nacion, Andrew Ezekiel O.

Lab_Act1

When rotating the screen, the Activity displays another set of onCreate(), onStart(), and onResume() methods on my Android emulator because the Activity is recreated. When I press the Home button and return to the application, it goes through the onPause(), onStop(), onRestart(), onStart(), and onResume() lifecycle methods as it moves to the background and becomes active again.

Logcat helped me identify the processes being executed because it displays the lifecycle methods in order. This allowed me to observe and verify which methods were triggered during screen rotation and when returning to the application.

I had a hard time setting up the SDK and encountered a problem where my application would not run. After investigating the issue, I discovered that my project was not properly synchronized with the required SDK, which is necessary for building and running applications in Android Studio.