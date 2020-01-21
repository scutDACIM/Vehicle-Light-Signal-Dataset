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

Samples of these 8 categories are shown as follow:
![Samples](https://github.com/scutDACIM/Vehicle-Light-Signal-VLS-Dataset/blob/master/Samples.png)

Totally, this dataset includes 7720 images, 9 categories (including background), and 10571 instances. The data distribution statistics can be viewed at following histogram:
![Statistics](https://github.com/scutDACIM/Vehicle-Light-Signal-VLS-Dataset/blob/master/Statistics.png)

You can download our data set from here(download link, password: tuiy), 
[download link](https://pan.baidu.com/s/1uRJVmHoaNWg72ajDQm32ow) 

including original images and labels. The original images are various vehicle light signals in the real scene taken from the driving recorder. The labels are in VOC format and each label file contains the vehicle light signal categories and locations.

If you use this dataset, please cite:

@article{ Vehicle Light Signal (VLS) Dataset,

  author    = {Shenao Zhang , Xin He , Lei Kuang, Delu Zeng, Bo Wu},

  title     = {Coarse-to-fine attention neural network for vehicle light signal detection},

  year      = {2020},
  
}

For any questions related to this dataset, or If you would like to trial the More Efficient Labelling Tool (LabelImage) , please contact msxinhe@mail.scut.edu.cn
