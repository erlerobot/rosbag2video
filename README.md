# rosbag2video

With this script you can create a video over a rosbag.

## How to record a rosbag?

`rosbag record /camera/image/compressed`

## How to decompress?

**Note** move the rosbag at same folder which contains `rosbag2video.py`, then execute the following:

`python rosbag2video.py -r 50 -o <nameofvideo>.mp4 <rosbagname>.bag`

**Example:**

`python rosbag2video.py -r 50 -o test.mp4 2016-03-07-17-17-02.bag `

