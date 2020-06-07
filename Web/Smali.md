## Smali
### Web

- In Current Time The CTF Challenge Is Not Up Anymore So, I Will Just Talk About The Solve For This Chall, When You Open The Webpage You Got A Secure Shell That You Could Write Commands There To The System, If You Try ```ls``` You Will Get That There Is Two PHP Files ```index.php , flag.php``` In Same Dir, You Could Try Cat The ```flag.php``` **< That Is The First Think Normal Person Will Do. >** , But You Will Get Some Bad Song With Bad Message There, So I Can Not Use Damn cat What Should I DO? , Kinda Easy But Take Sometime To Get, You Maybe Know About Strings? It Could Print All Readable Strings In Any File, And We Are Sure Of That PHP Files Is 100% Readable, SO I Have Try ```strings flag.php``` And Get Another Bad Message Here Says That There Is Limit For Chars In The Command SO ```WTF```, After Some Type Of Trying To DO Some Dumy Stuff I Remember ```*``` That Allows Me To Select All Files Without Need To Request Every File IN Every Time, I Try To Run ```strings *``` , And Got Both Files ```index.php , flag.php``` Content IN The Page With Same Bad Song XD.

## Images Steps

- **List Dirs (ls)**
![](https://github.com/DEMON1A/CyberHackCTF-WriteUps/blob/master/Web/images/Ls-Command.png)

- **Cat flag.php**
![](https://github.com/DEMON1A/CyberHackCTF-WriteUps/blob/master/Web/images/Cat-Flag.png)

- **Strings The Flag.**
![](https://github.com/DEMON1A/CyberHackCTF-WriteUps/blob/master/Web/images/Strings-Flag.png)

- **Get Real Flag Strings All.**
![](https://github.com/DEMON1A/CyberHackCTF-WriteUps/blob/master/Web/images/Strings-All-Solved.png)

## Tips

- There Is Multi Commands For Every Thing There In Linux.

## Our Team

```
NAME = Roots
RANK = 16th
POINTS = 4230
```
