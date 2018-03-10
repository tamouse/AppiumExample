Just a little testing of Appium following their example

Check out https://appium.io/docs/en/about-appium/getting-started/?lang=en

Using demo app https://github.com/appium/sample-code/blob/master/sample-code/apps/ApiDemos/bin/ApiDemos-debug.apk

Install with

    npm install

Make sure you set JAVA_HOME to your jdk installation. Mine is:

    /Library/Java/JavaVirtualMachines/jdk1.8.0_144.jdk/Contents/Home

Start up an android emulator.

To run Appium:

    appium

In another terminal window, run

    node test.js
