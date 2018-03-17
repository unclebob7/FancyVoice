# FancyVoice
VoiceAssistant(Chinese Name:趣声) is an Android Application using voice-recognize technology from iFLY(website:http://www.xfyun.cn/). It has three mainly kinds of modules, Speech-Control Browser, Speech-Control Notebook and Game Centre based on voice-recognize. With BottomNavigationView on the bottom of layout companied by Viewpager, following **Material Design** rules, you must find yourself immerse in exploring this application for great pleasure as well as for its colorful, creative design.
<div align=center><img width="200" height="180" src="http://opm54c01s.bkt.clouddn.com/18-3-16/3554926.jpg"/></div>
## Environment
* Language
Chinese
* Platform
Andorid 
minSdkVersion 15 / compileSdkVersion 25 / targetSdkVersion 25
buildToolsVersion "27.0.3"
* Version
FancyVoice V1.0 (underdeveloped)
* Gradle details
You could refer to the following configure to gradle
```
//app/build.gradle
apply plugin: 'com.android.application'
apply plugin: 'com.jakewharton.hugo'
dependencies {
    compile project(':library')
    implementation files('libs/gson-2.8.0.jar')
    implementation files('libs/Msc.jar')
}

//library/build.gradle
apply plugin: 'com.android.library'
```
## Function
#### Speech-Control Browser
<div align=center><img width="150" height="300" src="http://opm54c01s.bkt.clouddn.com/18-3-16/61169555.jpg"/></div>

#### Speech-Control Notebook
<div align=center><img width="150" height="300" src="http://opm54c01s.bkt.clouddn.com/18-3-16/96617817.jpg"/></div>

#### Game Centre
You need to speak “华为华为” to initialize the iFLY speech-recognize engine before giving any answer to microphone of cellphone. Following the instruction given by a description, you'll have limitless opportunities to use your acute brain, deduction and logic thinking to crack the right answer in each stage.
<div align=center>
  <img width="150" height="300" src="http://opm54c01s.bkt.clouddn.com/18-3-16/13284193.jpg"/>
  <img width="150" height="300" src="http://opm54c01s.bkt.clouddn.com/18-3-16/76865400.jpg"/>
</div>
