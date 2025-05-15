https://github.com/jon424/jon424.github.io

grifter html index.html



changed codec of source video like this:
   ffmpeg -i "path\to\original\BLIP_3.MP4" -c:v libx264 -c:a aac -crf 23 -preset medium video\BLIP_3_simple.MP4