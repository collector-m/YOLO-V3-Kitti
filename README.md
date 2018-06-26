# YOLO-V3-Kitti
Train YOLO-V3-Kitti

### DataSet: Kitti 2d object left color image
* Image download link:https://s3.eu-central-1.amazonaws.com/avg-kitti/data_object_image_2.zip
* label download link:https://s3.eu-central-1.amazonaws.com/avg-kitti/data_object_label_2.zip

### Training Data util
* Total:7481
* Train:Test:Val: 8:1:1

### original class
|	class_name	|	count	|
|	:-:	|	:-:	|
|	DontCare	|	15782	|
|	Person_sitting	|	222	|
|	Pedestrian	|	0	|
|	Car	|	28742	|
|	Tram	|	511	|
|	Misc	|	973	|
|	Cyclist	|	1627	|
|	Truck	|	1094	|
|	Van	|	2914	|
#### pie chart


### Custom class
|Class name (string in label file)|	Class ID (number in database)|comment|
|:-:|:-:|:-:|
|Person|0|include [Pedestrian, Person_sitting, cyclist]|
|bicycle|1||
|car|2||
|motorcycle|3||
|bus|4||
|truck|5|include [Truck, Van, Tram]|

### Ref:
### yolo v3
If you use YOLOv3 in your work please cite our paper!
@article{yolov3,
  title={YOLOv3: An Incremental Improvement},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2018}
}
### Kitti v3
Citation
When using this dataset in your research, we will be happy if you cite us:
@INPROCEEDINGS{Geiger2012CVPR,
  author = {Andreas Geiger and Philip Lenz and Raquel Urtasun},
  title = {Are we ready for Autonomous Driving? The KITTI Vision Benchmark Suite},
  booktitle = {Conference on Computer Vision and Pattern	Recognition (CVPR)},
  year = {2012}
}
