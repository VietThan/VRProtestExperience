# Experience Protests from Around the World
<p align="left">
	<img src="https://img.shields.io/badge/platform-Windows-blue?style=for-the-badge"
			 alt="platform">
	<img src="https://img.shields.io/badge/engine-Unity-blueviolet?style=for-the-badge"
			 alt="engine">
 	<img src="https://img.shields.io/badge/language-Csharp-yellow?style=for-the-badge"
			 alt="language">
</p>

<p align="center"><img src="Pictures/MainMenu.gif" width=500></p>

To merge files:

 .\ffmpeg -i UnknownBeirut.mp4 -i UnknownBeirutAudio.mp3 -map 0:v -map 1:a -c:v copy -c:a copy UnknownBeirutVidAud.mp4 -y
 
 To find out streams of video:
 
 .\youtube-dl.exe --user-agent "" URL https://www.youtube.com/watch?v=SQeaicX7Q0U -F
 
 To download specific streams:
 
 .\youtube-dl.exe --user-agent "" URL https://www.youtube.com/watch?v=SQeaicX7Q0U -f 138
