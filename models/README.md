Several state-of-the-art Neural Network (NN) architectures that have been published and provide performance efficiency in 1D as well as 2D problems have been implemented and integrated into the CrossAI. The architectures that are included in the library are distinguished into 2 main categories, the models that can handle 1D problems, such as time-series, and the models that accept as input 2D data, such as images, spectrograms, etc. 

The NN topologies that are related to 1D, are the following:
* XceptionTime [[1]](#1)[[2]](2)
* InceptionTime [[3]](3)
* [BiLSTM-Time] [[4]](4)[[5]](5)

Accordingly, the NN architectures that correspond to 2D problems handling are:

* [Xception] [[6]](6)
* [Inception v3] [[7]](7)
* [ResNet-50] [[8]](8)
* [VGG16] [[9]](#9)

## References

<a name="1">[1]</a> Tzamalis, Pantelis, Andreas Bardoutsos, Dimitris Markantonatos,  Christoforos Raptopoulos, Sotiris Nikoletseas, Xenophon Aggelides, and  Nikos Papadopoulos. "End-to-end Gesture Recognition Framework for the  Identification of Allergic Rhinitis Symptoms." In 2022 18th International Conference on Distributed Computing in Sensor Systems (DCOSS), pp. 25-34. IEEE, 2022.

[2]: Rahimian, Elahe, Soheil Zabihi, Seyed Farokh Atashzar, Amir Asif, and  Arash Mohammadi. "Xceptiontime: A novel deep architecture based on  depthwise separable convolutions for hand gesture classification." arXiv preprint arXiv:1911.03803 (2019).
InceptionTime:

[3]: Ismail Fawaz, Hassan, Benjamin Lucas, Germain Forestier, Charlotte  Pelletier, Daniel F. Schmidt, Jonathan Weber, Geoffrey I. Webb, Lhassane  Idoumghar, Pierre-Alain Muller, and François Petitjean. "Inceptiontime:  Finding alexnet for time series classification." Data Mining and Knowledge Discovery 34, no. 6 (2020): 1936-1962.
BiLSTM-Time:

[4]: Zhu, Peide, Hao Zhou, Shumin Cao, Panlong Yang, and Shuangshuang Xue.  "Control with gestures: A hand gesture recognition system using  off-the-shelf smartwatch." In 2018 4th International Conference on Big Data Computing and Communications (BIGCOM), pp. 72-77. IEEE, 2018.

[5]: Hou, Jiahui, Xiang-Yang Li, Peide Zhu, Zefan Wang, Yu Wang, Jianwei  Qian, and Panlong Yang. "Signspeaker: A real-time, high-precision  smartwatch-based sign language translator." In The 25th Annual International Conference on Mobile Computing and Networking, pp. 1-15. 2019.

[6] Chollet, François. "Xception: Deep learning with depthwise separable convolutions." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 1251-1258. 2017.

[7] Szegedy, Christian, Vincent Vanhoucke, Sergey Ioffe, Jon Shlens, and  Zbigniew Wojna. "Rethinking the inception architecture for computer  vision." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 2818-2826. 2016.

[8] He, Kaiming, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. "Deep residual learning for image recognition." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 770-778. 2016.

<a name="#9">[9]</a> Simonyan, Karen, and Andrew Zisserman. "Very deep convolutional networks for large-scale image recognition." arXiv preprint arXiv:1409.1556 (2014).
