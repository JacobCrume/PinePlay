# PinePlay
PinePlay is an open game/app store targeted at the Pinephone. However, it (and it's apps and games) can be run on any ARM-based Linux machine. The main features of Pineplay are:

* The ability to download and install app packages
* A modern and mobile-focused UI
* Wide range of compatible devices, from the Pinephone to the Raspberry Pi Zero
* Customizable installation folders
* Easy app development, with a wide range of easy-to-use tools for both games and apps.

Additionally, the followig features are planned for a future release:

* The ability for developers to charge money for their games
* Pineplay account
* Cross-device sync (using your Pineplay account)

# Development
While it would be great to have Pineplay using either GTK or Qt, I feel that these are much more desktop-oriented, and very lacking when it comes to mobile. Therefore, Pineplay does not use Qt/Kirigami or GTK, instead opting for either Flutter, or Electron. 

Because Flutter uses the Dart programming language, it requires a lot more work to learn how to develop for it. Meanwhile, Electron is much easier to program for, since it makes use of HTML, CSS, and Javascript. The biggest downside to this approach is the performance.

The decision between these two UI options will be made when the design stage is finished.

Here the stages the project has, and will go through:

* Planning
* UI Design
* Programming
* Bugfixing
* Release

Currently, PinePlay is in the design stage. It is designed using Adobe XD, due to it's ability for the UI to be previewed on an Android device to improve usability.
