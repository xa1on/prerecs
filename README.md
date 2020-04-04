# prorec

Encoding/converting pre-records into readable formats for AE/SV
Video with render time comparisons: https://www.youtube.com/watch?v=YAbM7c9nOTo
this tool converts heavily compressed video files into readable formats suited for video editing. 

## Requirements

* **[prorec.bat](https://github.com/gmzorz/prerecs/archive/master.zip)**
* [Xvid](https://www.xvid.com/download/) (download & install)
* [quicktime](https://support.apple.com/kb/DL837) (download & install)
* [ffmpeg](https://ffmpeg.zeranoe.com/builds/) (navigate to the C:\Windows\System32 folder, open the ffmpeg zip file, go to the 'bin' folder, and extract all .exe files into the system32 folder)

## Instructions
Download the requirements and install them accordingly. Place prorec.bat in any directory containing the footage to be converted and run it. Drag & drop works, but does not support multiple files. 

There are notable differences between each codec, Whether you choose to go with prores completely relies on how much time you have, but also whether you want the most optimal quality. If you decide to go with xvid, expect very fast encoding speeds and small file sizes
Following table contains information about footage encoded into the formats described (1920x1080)
Encoded

| Codec | Encoding time | Playback time (AE only) | Difference Matte (quality difference compared to original) |
|---|---|---|---|
| prores | 7 FPS | 16 FPS | |
| xvid | 81 FPS | 9 FPS | |
