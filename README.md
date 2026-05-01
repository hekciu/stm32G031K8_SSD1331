## Image preparation:
- ffmpeg -vcodec png -i file.png -vcodec rawvideo -f rawvideo -s 96x64 -pix_fmt rgb565 file.raw
- ./bin2header.exe -o file.h file.raw