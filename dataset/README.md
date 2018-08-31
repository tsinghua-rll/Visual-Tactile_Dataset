There have 2550 sets data in this dataset, only 1650 sets have the video data.

For each set that have video data, there have 4 video files:
front_rgb.mp4 is the rgb video recorded by front camera;
left_rgb.mp4 is the rgb video recorded by left camera;
fornt_depth.mp4 is the depth video recorded by front camera, the depth data is 16 bit, we have saved high 8 bit into red channel, middle 8 bit into green channel and low 8 channel into blue channel;
front_depth0.mp4 is the depth video recovered by front_depth.mp4 and represented with colormap;

When we recover the depth data, we found that influenced by the video compress process, there have some errors in the *_depth0.mp4 video, there are caused by the our storge and video compress process. But the depth is also useful and we have test the realiablity of the depth data, combine with robot model, there can be used to reconstructure the experiment.
