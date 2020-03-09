# under_water_object_detection

1.图片放置在 UWR/object_detection/voc/VOCdevkit/VOC2018/JPEGImages下\
2.xml文件放在 UWR/object_detection/voc/VOCdevkit/VOC2018/Annotations下\
3.把 train.txt 放在 UWR/object_detection/voc/VOCdevkit/VOC2018/ImageSets/Main下\
4.下载 https://pan.baidu.com/s/1hkHgtPqi7JmcYsOugUlNBw  密码:rhlp 放在UWR/object_detection/voc下\
5.修改UWR/object_detection/voc/ssd_resnet50_v1_fpn.config中的路径，改成自己本地的路径，共5处。另外可以通过修改参数调试模型\
6.在 UWR 下执行 python train.py 即可开始训练\
7.训练结束后，使用 object_detection/export_inference_graph.py 导出模型，需要修改或指定其中的路径\
8.参考 object_detection／object_detection.ipynb中的代码，适当修改满足比赛提交格式

