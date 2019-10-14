# FancyVoice
FancyVoice(Chinese Name:趣声) is an Android application aiming to fully utilize the power of ASR by incorporating it into lots of controlling details. For example, for the convenience of the physical impaired, I developed "Handfree Browser" that use voice trigger for controlling events which traditonally requires direct physical operations; "Lisinterest": combining ASR with Acapella-CNN, I managed to increase the signal-noise-ratio and better the performance of lyrics recognition; "Skypeech": in-time captioning for Skype, offering accessible and satisfying Skype experience for the hearing-disabled. Following **Material Design** rules, you must find yourself immersed in exploring this application for great pleasure as well as for its colorful, creative design.

<div align=center>
    <img width="250" height="180" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/logo.png"/>
</div>

## 1 Environment
* Platform: Android API:25(minAPI:21)
* Version: FancyVoice V1.0 (underdeveloped)
### 1.1 Gradle details
You could refer to the following configure to gradle

```
/*app/build.gradle*/
apply plugin: 'com.android.application'

dependencies {
    implementation files('libs/gson-2.8.0.jar')
    implementation files('libs/Msc.jar')
    implementation 'com.rengwuxian.materialedittext:library:2.1.4'
}
```


## 2 Function
### 2.1 Handfree Browser
A never-seen-before browser that specifically designed for the physical disabled to more conveniently use their browser. By incorporating **voice trigger** in every single controlling details which previously requires direct physical operations, this is sure to be convenient and never-seen-before!
<div align=center>
    <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/browser1.jpg"/>
    <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/browser2.jpg"/>
</div>

### 2.2 Lisinterest
combining ASR with Acapella-CNN, I managed to increase the signal-noise-ratio and better the performance of lyrics recognition which offers instantaneous lyrics generation for the users. It's still an ongoing research trial.
<div align=center>
    <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/music_player1.jpg"/>
    <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/music_player2.jpg"/>
</div>

### 2.3 Speech-Control Notebook
Just click the button and then assert without any restraint. All your voice would be converted into texts.
<div align=center>
    <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/notebook1.jpg"/>
    <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/notebook2.jpg"/>
</div>

### 2.4 Bob's secret
Using ***voice trigger** to initialize the Iflytek speech-recognize engine before giving any answer to microphone of cellphone. Following the instruction given by a description, you'll have limitless opportunities to use your acute brain, deduction and logic thinking to crack the right answer in each stage.
<div align=center>
  <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/game.jpg"/>
</div>

### 2.5 Other Modules
Other Modules include ***Me*** and ***About Softeware***
*Me* is a page for containing other voice-recognition tools;
*About Software* is a Copyright Statement and contains developers' information.
<div align=center>
  <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/me.jpg"/>
  <img width="150" height="300" src="https://github-1252789527.cos.ap-shanghai.myqcloud.com/FancyVoice/about_software.jpg"/>
</div>

### Contributors
- Zhiming Li (China University of Geosciences)
- Rongfeng Yang (HKUST)
