Commands
video-retime: Video Retiming (Speed Up/Down)
video-retime data/2018-11-02_14-44-14.mp4 --retime 2
video-retime data/2018-11-02_14-44-14.mp4 --retime 2 --inplace
video-togif: Create a GIF
video-togif data/2018-11-02_14-44-14.mp4 --fps 2 --duration 5
video-togif data/2018-11-02_14-44-14.mp4 --fps 2 --duration 5 --resize 0.5
video-trim: Video Triming
video-trim data/2018-11-02_14-44-14.mp4 --start 3 --duration 5
video-tile: Video Tiling
video-tile data/2018-11-02_14-44-14.mp4 data/2018-11-02_14-44-14.mp4 --shape 1x2 -o tile.mp4
video-toimg: Convert a Video to Images
video-toimg data/2018-11-02_14-44-14.mp4 --per 10 --start 3 --duration 10
video-tovideo: Convert to Video
video-tovideo data/2018-11-02_14-44-14.mp4
video-resize: Video Resizing
video-resize data/2018-11-02_14-44-14.mp4 --scale 0.5
video-fromimg: Create a Video from Images
video-toimg data/2018-11-02_14-44-14.mp4
video-fromimg --input-files "data/2018-11-02_14-44-14/*.jpg" --fps 30 out.mp4
video-crop: Crop a region of a Video
video-crop data/2018-11-02_14-44-14.mp4
