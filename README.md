**Python**

`wget http://download.tensorflow.org/models/object_detection/mask_rcnn_inception_v2_coco_2018_01_28.tar.gz`
`tar zxvf mask_rcnn_inception_v2_coco_2018_01_28.tar.gz`

Download and extract the needed model files.

**Usage Examples :**

**Python**

`python3 mask_rcnn.py --image=cars.jpg`
`python3 mask_rcnn.py --video=cars.mp4`

It starts the webcam - if no argument provided.

**C++**

Compile using:

```g++ -ggdb `pkg-config --cflags --libs /Users/snayak/opencv/build/unix-install/opencv.pc` mask_rcnn.cpp -o mask_rcnn.out```

Run using:
`./mask_rcnn.out --image=cars.jpg`
`./mask_rcnn.out --video=cars.mp4`

#This program adds two numbers
num1 = 1.5
num2 = 6.3
#Add two numbers
sum = num1 + num2
#Display the sum
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))


