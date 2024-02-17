# FFMPEG

## ffmpeg coranlive

ffmpeg -re -stream_loop -1 -i ./streamloop/stockvideo.mp4 -i "[https://server03.quran.com.kw:7011/;*.mp3](https://server03.quran.com.kw:7011/;*.mp3)" -c:v copy -c:a copy -map 0:v -map 1:a -f flv rtmp://ovsu.mycdn.me/input/6636411562889_5503137811081_rd72enshia

# ffmpeg with no output

 nohup ffmpeg -re -i [https://stream.skynewsarabia.com/hls/sna.m3u8](https://stream.skynewsarabia.com/hls/sna.m3u8) -c copy -f flv rtmp://ovsu.mycdn.me/input/6635060669321_5500894382729_hjjbgmlnuy > /dev/null 2>&1 &

## video

[Merge Audio and Video in Seconds with FFmpeg](https://youtu.be/Q7XLtjMoMK4)

## ffmpeg quran youtub

nohup ffmpeg -re -stream_loop -1 -i ./streamloop/stockvideo.mp4 -i "[https://server03.quran.com.kw:7011/;*.mp3](https://server03.quran.com.kw:7011/;*.mp3)" -c:v copy -c:a copy -map 0:v -map 1:a -f flv rtmp://ovsu.mycdn.me/input/6636411562889_5503137811081_rd72enshia > /dev/null 2>&1 &

 nohup ffmpeg -re -i [https://dai.google.com/linear/hls/event/wG75n5U8RrOKiFzaWObXbA/master.m3u8](https://admdn2.cdn.mangomolo.com/nagtv/smil:nagtv.stream.smil/playlist.m3u8) [](https://dai.google.com/linear/hls/event/wG75n5U8RrOKiFzaWObXbA/master.m3u8)-c copy -f flv rtmp://ovsu.mycdn.me/input/6652147739529_5528451418761_qgqvadkiji > /dev/null 2>&1 &