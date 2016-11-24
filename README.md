Latest Version 
--------------
##### _Nov 18st, 2016_ - v1.8.3

Getting Started
---------------
Check out our [official documentation](https://www.devtodev.com/help/117/adobe_air_universal/) to learn how to install the library on your IDE. You will also learn how to make use of all the features we currently support!

Changelog
---------
See [releases](https://github.com/devtodev-analytics/air-sdk/releases).

#### Version 1.8.1
* Push initialization before analytics was fixed
* https protocol was added

#### Version 1.8
* Added new "Progression event". First of all, the event is used for the games with short (within one game session) locations, game levels. The event allows you to gather data on passing the locations and get statistics on parameters which vary during the the location passing.
* [Android] Possible crash caused by Google Play Services absence if push-notifications are used is fixed.

#### Version 1.7
* User profile feature is added. Here you can store properties about a specific user.
 - New methods for managing preset and custom properties of user profile are added.
 - Old methods: age, gender and cheater, are removed. These properties are moved to user profile.
* Initial referrer data tracking method is added

#### Version 1.6.6
* Call events before SDK init

#### Version 1.6.5
* Call init not longer affect pushes

#### Version 1.6.4
* Added service information to distinguish SDK type.

#### Version 1.6.3
* Added ability to customize images in Android push-notification
* Improvements in custom events

#### Version 1.6.1
* Support of push-notifications for iOS and Android is added

#### Version 1.6
* Android support is added
* iOS support is added
* Mac OS support is added
* Windows support is added
* SDK preparation for usage in cross-platform projects
