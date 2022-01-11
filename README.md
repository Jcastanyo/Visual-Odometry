# Visual-Odometry
In this repository, you can find the code (jupyter notebook) that I wrote to do the visual odometry using python and opencv. The code is not mine, I followed the youtube series of Nate Cibik, I leave the link here in case anyone wants to take a look: https://www.youtube.com/channel/UC7aA9FbEDCJFwBHLNqY1K2w/videos.
I really recommend to see it if you're interested in this topic and you want to put into practice some theorical concepts you may have about visual odometry. In my case, I studied disparity and stereo vision but I've never tried to write the code. 
In these videos, Nate explains all the theorical concepts you have to know about camera calibration and stereo vision. And, then, he writes all the code using OpenCV funtions to solve the visual odometry problem. Although the results are not good enough to run this experiment in real time, I've learned many things along the videos. 
Take a look at the code and run the whole experiment. If you don't understand something, don't hesitate to open an issue. Nonetheless, I recommend you to go to Nate's github because there you can find all the code well explained and the theorical parts.
https://github.com/FoamoftheSea/KITTI_visual_odometry

I leave here some photos of the results I got in case to want to see it faster.

# Disparity map
![disparitymap](https://user-images.githubusercontent.com/84505434/149008896-b86de07c-0a7c-4ebe-917c-2cdd1333d02a.png)
# Depth map
![depthmap](https://user-images.githubusercontent.com/84505434/149008912-c146f89e-6130-4478-b67c-340b3a09c5c9.png)
# Feature matching
![featurematching](https://user-images.githubusercontent.com/84505434/149008939-2825fbc2-bb03-40f8-bd7c-b65917f237d6.png)
# Comparison between ground truth trajectory and calculated trajectory (green)
![Figure_1](https://user-images.githubusercontent.com/84505434/149009125-e8741cd4-ba99-4501-b4d2-a661fc8ba5aa.png)
