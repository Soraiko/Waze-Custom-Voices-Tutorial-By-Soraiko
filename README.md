# Waze Custom Voices Tutorial By Soraiko

### This repository is a tutorial with my explanations on how to import voices to Waze: the "hard way" to do it. 
Hopefully my explanations will help make that pain easier to bear.  
  
The "easy way" around is the official alternative that consists in recording your voice on Waze by using their audio capturing tool.  
The problem is, their audio capturing tool is horribly compressing your audio, so trying to run it on an emulator by sending high quality audio into the microphone stream doesn't help either.  
  
### That said, let's start with the explanations.  
I'll be using **Bluestacks**, but you can do it the way you want.  
In my case, you will need specific versions of Bluestacks, because latest versions either are a pain to root, either run versions of Android that are not compatible with Waze.  
The voice packs that you will generate are compatible with the last versions of Waze.

I'm an empathic person unlike most Github user so I uploaded all binaries that I have used in the folder "Dependencies-Binaries". (Yes I'm also rude and arrogant but I don't give a crap I'm saying the truth and this is MY tutorial.)  
<ul>
<li><a target="_blank" href="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/raw/main/Dependencies-Binaries/bluestacks-app-player-5-10-210.exe"><img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/bsicon.jpg" width="18">&nbsp;bluestacks-app-player-5-10-210.exe</a></li>
<li><a target="_blank" href="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/raw/main/Dependencies-Binaries/BSTweaker69020.zip"><img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/archive.jpg" width="18">&nbsp;BSTweaker69020.zip</a></li>
<li><a target="_blank" href="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/raw/main/Dependencies-Binaries/SuperSU-v2.82-SR5"><img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/bsicon.jpg" width="18">&nbsp;SuperSU-v2.82-SR5.apk</a></li>
<li><a target="_blank" href="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/raw/main/Dependencies-Binaries/waze-4-52-3-4.apk"><img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/bsicon.jpg" width="18">&nbsp;waze-4-52-3-4.apk</a></li>
</ul>
 
  
### BSTweaker, an utility to patch Bluestacks so it can be rooted.  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image1.jpg" width="512">
The two chain link icons on the left panel of BSTweaker must both be green. I let you understand the app to make it so. 
I personally just ran the app AFTER Bluestacks was fully loaded and ready in the main menu with application icons.  <br>  
<br>  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image2.jpg" width="512">
Click the "Root" tab of BSTweaker and the top "Patch" button located before "Install SuperSu"<br>  
  
### SuperSU, to enable root from the machine/emulated side.  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image3.jpg" width="512">
SuperSU will ask to update few modules, click "Normal" method.<br>  
Then tick"Activate Super-user" and "Allow access" in "Default access choice".<br>  
(Not sure how these buttons are named in the english.)  
  
### Install Waze APK.  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image4.jpg" width="512">
  
## Now run Waze. 
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image5.jpg" width="512">
Click the sound icon at right bottom of main map view.<br>  
<br>  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image6.jpg" width="512">
Then click "Waze Voice"<br>  
<br>  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image7.jpg" width="512">
"Record a new voice"<br>  
<br>  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image8.jpg" width="512">
Here we are. This is the official panel that tells you everything to know about the files to record.  
<br>  
Just as a reference, (you don't need this folder for your conversion) you will find a list of filenames and details about them in the folder<br>  
<b>Voice-Files/[language].txt</b> in my repository.
<br>
As well as file I generated to put Waze's audio encoder on trial. (Random sample audio through the microphone to show the maximum compressing result)  
<br>  
  
```
Codecs:
AAC LC, 12kb/s, 8000 Hz, mono

StartDrive1.mp3         (10kb / 6 sec. max)
StartDrive2.mp3         (10kb / 6 sec. max)
StartDrive3.mp3         (10kb / 6 sec. max)
StartDrive4.mp3         (10kb / 6 sec. max)
StartDrive5.mp3         (10kb / 6 sec. max)
StartDrive6.mp3         (10kb / 6 sec. max)
StartDrive7.mp3         (10kb / 6 sec. max)
StartDrive8.mp3         (10kb / 6 sec. max)
StartDrive9.mp3         (10kb / 6 sec. max)
200.mp3                 ( 5kb / 3 sec. max)
200meters.mp3           ( 5kb / 3 sec. max)
400.mp3                 ( 5kb / 3 sec. max)
400meters.mp3           ( 5kb / 3 sec. max)
800.mp3                 ( 5kb / 3 sec. max)
800meters.mp3           ( 5kb / 3 sec. max)
1500.mp3                ( 5kb / 3 sec. max)
1000meters.mp3          ( 5kb / 3 sec. max)
1500meters.mp3          ( 5kb / 3 sec. max)
KeepLeft.mp3            ( 5kb / 3 sec. max)
KeepRight.mp3           ( 5kb / 3 sec. max)
TurnLeft.mp3            ( 5kb / 3 sec. max)
TurnRight.mp3           ( 5kb / 3 sec. max)
ExitLeft.mp3            ( 5kb / 3 sec. max)
ExitRight.mp3           ( 5kb / 3 sec. max)
Straight.mp3            ( 5kb / 3 sec. max)
uturn.mp3               ( 5kb / 3 sec. max)
Roundabout.mp3          ( 5kb / 3 sec. max)
First.mp3               ( 6kb / 3 sec. max)
Second.mp3              ( 5kb / 3 sec. max)
Third.mp3               ( 5kb / 3 sec. max)
Fourth.mp3              ( 5kb / 3 sec. max)
Fifth.mp3               ( 5kb / 3 sec. max)
Sixth.mp3               ( 5kb / 3 sec. max)
Seventh.mp3             ( 5kb / 3 sec. max)
Police.mp3              (10kb / 6 sec. max)
ApproachAccident.mp3    (10kb / 6 sec. max)
ApproachHazard.mp3      (10kb / 6 sec. max)
ApproachTraffic.mp3     (10kb / 6 sec. max)
ApproachRedLightCam.mp3 (10kb / 6 sec. max)
ApproachSpeedCam.mp3    (10kb / 6 sec. max)
AndThen.mp3             ( 5kb / 3 sec. max)
TickerPoints.mp3        ( 8kb / 5 sec. max)
Arrive.mp3              (10kb / 6 sec. max)
```
  
### How Waze manages files in real time when you use their voice recording panel in the app.
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image9.jpg" width="512">
First of all, go back to BSTweaker (than must stay open in background during the whole process) click "File Manager" from the "Info" tab (first tab of BSTweaker).<br>  
<br>  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image10.jpg" width="512">

### This is the File Manager.
Files saved by Waze on android are located at this path:
```
/data/data/com.waze/waze
```
<ul>
<li>Left panel is system folder of Waze (android root accessible folder)</li>
<li>Right panel is your Windows folder. You must naviguate to a folder that will contain the files you will transfer to the emulator by drag and drop through these two panels.</li>
</ul>
  
### Each custom voice you make has a UniqueID.  
In my example, my voice "Voix de Gertrude" has the following Unique ID:  
```
641cdc20-ffe7-4ad4-88a9-5d7f6a264c97
```
This is the unique ID that will identify your custom voice (or someone else's) everywhere:
<ul>
<li>1) In the share URL</li>
<li>2) In the system app folder</li>
<li>3) In the <b>metadata.json</b> that contains each voice file details.</li>
</ul>
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image11.jpg" width="512">

### When you record voices.   
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image12.jpg" width="512">
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image13.jpg" width="512">
Here are the two folder in which Waze will transfer files. See following images for further explanations.<br>  
<br>  
<img src="https://github.com/Soraiko/Waze-Custom-Voices-Tutorial-By-Soraiko/blob/main/README_Pictures/image14.jpg" width="512">
In my example the file "StartDrive1_temp.mp3" is created when I hit the record button, and is renamed to "StartDrive1.mp3" when I hit save.<br>  
  
# This is where you perform the action that will do the whole thing. 

### Start recording silence, then press stop, and before to hit "Save", in the file explorer, replace "StartDrive1_temp.mp3" by your custom "StartDrive_temp.mp3"  
You MUST replace the temps files one by one in the temp folder. (Files you will drag and drop from Windows must end with "_temp.mp3")
<br>  
You will have to repeat that action for every file.