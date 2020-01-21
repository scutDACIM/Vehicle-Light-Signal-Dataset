# Vehicle Light Signal (VLS) Dataset Information


Our Vehicle Light Signal (VLS) dataset contains 4 common behaviours of vehicles: driving forward, braking, turning left, turning right. Each behaviour signal contains 2 classes: day and night, since the lighting signals are not the same when during the day and night. The specific label categories are as follows:

1.day_forward

2.day_brake

3.day_left

4.day_right

5.night_forward

6.night_brake

7.night_left

8.night_right

It should be noted that, the turning data that can be collected in the real scene is very scarce, so we randomly crop the collected turning data to augment by 10 times to avoid extreme data imbalance.

Totally, this dataset includes 9 categories (including background), 7720 images, and 10571 instances. The data distribution statistics can be viewed at following histogram:
![Statistics](https://github.com/scutDACIM/Vehicle-Light-Signal-VLS-Dataset/blob/master/Statistics.png)

You can download our data set from [here](https://github.com/scutDACIM/Vehicle-Light-Signal-Dataset) (we will release later), 

including original images and labels. The original images are various vehicle light signals in the real scene taken from the driving recorder. The labels are in VOC format and each label file contains the vehicle light signal categories and locations.

For any questions related to this dataset, or If you would like to trial the More Efficient Labelling Tool (LabelImage) , please contact msxinhe@mail.scut.edu.cn
