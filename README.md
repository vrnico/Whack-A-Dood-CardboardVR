Whack-a-dood
==========
#### A Cardboard VR application developed in Unity

![alt text](https://i.imgur.com/pyXdFfu.png "screenshotgame")
![alt text](https://i.imgur.com/Cpcd7iN.gif)

## Installation (open in Unity)



Open your preferred terminal, and enter the following command to clone source to your local machine:
```sh
git clone https://github.com/vrnico/Whack-A-Dood-CardboardVR
```

Open  Whack-A-Dood-CardboardVR project in Unity


In order to Test Play with funationality: In Unity add GvrEditorEmulator.prefab into PlayerContainer. The prefab is in the file below
```
Assets > GoogleVR > prefabs
```

Test play by pressing the play button. Clicking represents the "Fire1" input for Google Cardboard


#####  *Remember to Delete GvrEditorEmulator.prefab from Project before Building!*



Build out the apk with Custom settings and assets using Unity's build settings. Gradle / Internal errors are most likely due to mismatched versions of Unity / GoogleVR Sdk/ and And
```sh
ng serve --open
```

## Android Installation .apk

Download Cardboard on your Android Phone
```sh
https://vr.google.com/cardboard/download/
```
Activate Developer Options on your phone
```sh
Settings > General > About Phone > Software Info
```
*Tap the Software Version 7 times* (sounds weird, but if it works you should see an alert that Developer Options have been unlocked) Navigate to Developer Options in Settings
```sh
Activate USB Debugging
```
Plug phone into Computer and drag whackadood.apk into the file storage of your Android device

Navigate to whackadood.apk in your phone's storage and install into your app library.


Open from the Whackadood Icon or from Google Cardboard. Make sure to give it a minute or two after the install before trying to run.


Congratulations you've succesfully deployed an Android app! Now go whack some doods!


## Created With
* C#
* Unity
* Blender
* Android SDK
* GoogleVR Unity Sdk gvr-unity-sdk-1.70.0

## Special thanks to
* Mammoth Interactive


## Contact
questions/comments/concerns
* [nico.daunt@gmail.com](mailto:nico.daunt@gmail.com)
* [PERSONAL WEBSITE](http://www.nicodaunt.com)




## License
Copyright 2018

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
