Most mobile apps need a backend: MBaaS. 
Parse easiest to get up and running

Holy Trinity of Mobile Apps:

Data
UI
"Mobile Features" (Bluetooth, GPS, accellerometer, etc)


Data - SQLite; LocalStorage (Angular LocalStorage library)
MBaaS

UI - Ionic, Angular
Mobile Features - Cordova 






Ionic -> UI Framework on top of Cordova?

Cordova: Opensource implementation of PhoneGap (Phone Gap is Owned by Adobe)

If you want to make iOS, Need Mac
If you want to make Android, need Java SDK.
If you want to make a Windows Phone App, Xamarin is $800.
Where Cross platform means iOS and Android

Not Cordova's rules; Apple requires a Mac to develop iOS apps. Blame Apple.

Android requires Java SDK. Blame Google.

What is Ionic? It's a UI framework built on HTML5, CSS, and JavaScript.

If you're a web programmer, you can write mobile apps.

Ionic                         Angular                  Cordova
  |                             |                         |
Icons,Pre-made                MVC framework            Phone APIs, GPS, Accelerometer, camera, Bluetooth, etc.   
navigation, button,
Lists, Cards, etc.



AngularJS:

MVC framework for JavaScript; 

Services                      Controllers        Views 						Directives
  | 								|				|							|
Talk to outside world			Talk to Views    Talk to 					Manipulate DOM in custom ways (think custom HTML tags on steroids)
												Controllers                 If you're familar with ASP.NET Webforms; these are like Declarative User Controls
												(2 way data-binding)        Do we have any JavaScript developers in the room? Close your ears (User Controls 							 and Directives could be close cousins. Very Close. )



Getting started with Ionic

If you're familar with Cordova, Ionic simply replaces Cordova at the Command line.

If you're on a mac, use Homebrew.

brew install ionic


If you want to install the Java SDK (newer than comes with Mac; feel free -- you may run into compatibility issues later on with other software (like Arduino, which requires Java 6))


Angular is a large part of Ionic; I've only got 70 minutes so I have to stick to a small subset. 


###Install

 - Install Homebrew
 - Install Ionic (Installs Cordova)
 - Install Apple Command Line Tools (Really, just install XCode; you'll feel better about yourself)
 
 


