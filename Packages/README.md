To merge files:

 .\ffmpeg -i UnknownBeirut.mp4 -i UnknownBeirutAudio.mp3 -map 0:v -map 1:a -c:v copy -c:a copy UnknownBeirutVidAud.mp4 -y
 
 To find out streams of video:
 
 .\youtube-dl.exe --user-agent "" URL https://www.youtube.com/watch?v=SQeaicX7Q0U -F
 
 To download specific streams:
 
 .\youtube-dl.exe --user-agent "" URL https://www.youtube.com/watch?v=SQeaicX7Q0U -f 138