# Pylon-Presentation

Plyer (Platform independent compatibility layer) is a library for accessing features of your hardware / platforms. 
Plyer provides access to features like Bluetooth, Camera, NFC, Notifications, Calling and others that are commonly found on multiple platforms. 
It's aim is to make it so you don't have to think about wrapping all these features on your own because it's already done, you just need to import them.

Supported platforms by plyer:

- Windows
- Android
- Linux
- iOS
- OSX.

This talk will also include some introduction of Pyjnius and Pyobjus tools which gives access to Objective-C and Java code dynamically.

Plyer example.

    from plyer import call
    call.makecall(tel='9896464007')

Pyjnius example
    
    from jnius import autoclass
    java_string = autoclass('java.lang.String')

Pyobjus example

    from pyobjus import autoclass
    NSString = autoclass('NSString')

Project url: [Plyer on Github](https://github.com/kivy/plyer)

Pyjnius url: [Pyjnius on Github](https://github.com/kivy/pyjnius)

Pyobjus url: [Pyobjus on Github](https://github.com/kivy/pyobjus)

Presentation url: [Google Docs](https://docs.google.com/presentation/d/1eJyZCcj7sgwH5scigw9v-5zAUfZTHUBt6wnSeiqNC-8/edit?usp=sharing)

# Speaker info:

I am a Google Summer of Code'16 Student under Python Software Foundation and Kivy being the sub-organisation.
Project Plyer is one of the Kivy's sister projects for which I am selected to work on as my GSoC project.
I am a python Lover and have been coding in python for past few years. I like to try different programming languages and learn new technologies.
