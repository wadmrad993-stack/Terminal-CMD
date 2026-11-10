# Terminal-CMD
ffmpeg -loop 1 -i image.jpg -i audio.mp3 -c:v lib264 -tune stillimage -c:a aac -b:a 128k -ar 44100 -ac 2 -pix_fmt yuv420p -r 15 -shortest -fps_mode cfr output.mp4
