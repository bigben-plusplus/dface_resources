
在人脸识别领域，为了测试和比较各种技术的性能优劣，国内外各个大学和研究机构都建立了各自的人脸识别的测试和测评数据库。下面介绍一些著名的标准人脸数据集。

## AT&T Faces
项目主页:[The Database of Faces](http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html)
<!--
Our Database of Faces, (formerly 'The ORL Database of Faces'), contains a set of face images taken between April 1992 and April 1994 at the lab. The database was used in the context of a face recognition project carried out in collaboration with the Speech, Vision and Robotics Group of the Cambridge University Engineering Department.

There are ten different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions (open / closed eyes, smiling / not smiling) and facial details (glasses / no glasses). All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position (with tolerance for some side movement). A preview image of the Database of Faces is available.

The files are in PGM format, and can conveniently be viewed on UNIX (TM) systems using the 'xv' program. The size of each image is 92x112 pixels, with 256 grey levels per pixel. The images are organised in 40 directories (one for each subject), which have names of the form sX, where X indicates the subject number (between 1 and 40). In each of these directories, there are ten different images of that subject, which have names of the form Y.pgm, where Y is the image number for that subject (between 1 and 10).
-->

AT&T Faces（原ORL）人脸数据集包含40个人，每人10张图片。这些图片都是在一个均匀黑色背景下拍摄，且拍摄者均保持直立正面姿态，但是在光照、面部表情、面部细节（是否戴眼镜）等方面存在较大变化。所有图片为PGM格式，每张图片大小为92x112，包含256个灰度等级。是早期人脸识别与认证常用的训练集和测试集。

## YaleB人脸数据库
美国耶鲁大学的实验人脸库，该数据库包含15个不同人，每人n幅不同表情或外部条件的图像，该库的特点就是光照变化显著，面部部分有遮挡。YaleB人脸库包含10个人的5760幅人脸图像，每个人的人脸图像是在9种不同的姿态、64种不同的光照下拍摄的。

## CMU Multi-PIE
CMU Multi-PIE(Pose Illumination Expression)人脸库是由美国卡耐基梅隆大学(CMU)的机器人研究所在2000年建立了CMU PIE数据库，包含68个人41368幅图像，每一个人的图像分别是在13种不同的姿态、43种不同的光照条件、4种不同的表情条件下拍摄的。

## CASIA-WebFace
项目主页:[CASIA WebFace Database](http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html)

CASIA-WebFace是由中科院自动化所搜集的网络图片人脸数据集，共包含0.5M张人脸图片，可用于人脸识别和人脸认证算法的训练集和测试集。

<!--
受大数据和深度卷积神经网络技术的推动，人脸识别的性能变得可与人类比拟。使用私有大规模训练集，一些研究组在LFW上取得了非常好的性能，97\%-99\%。虽然有很多开源的CNN的实现版本，但是大规模的热烈数据集却无法公开获取。目前人脸识别领域的现状是数据比算法更重要。为了解决这个问题，我们提出了一种半自动方法从因特网上收集人脸图片构造了一个大规模人脸数据集，包含10575个人共计494414张图片，成为CASIA-WebFace。据我们所知，这样规模的人脸数据集在文献中排名第二，仅次于Facebook的私有数据集SFC。我们鼓励那些依赖数据的算法在我们的数据集上训练，并在LFW上报告性能。
我们提出的CASIA-WebFace数据集的基本数据见表１.除了Facebook的SFC数据集，CASIA-WebFace的规模是最大的。考虑到用户隐私等因素，可能SFC将永远不会向研究社区开放。从2012年开始，微软的WDRef数据集的特征可以公开获取，但是对于更加高级的研究还不够灵活。在表中所列的数据集中，CASIA-WebFace＋LFW是最适合自然环境下大规模人脸识别研究的数据集组合。如果你觉得LFW上的正确率已经被当前最好的算法饱和了，BLUFR是一个更加具有挑战性的数据集。

Pushing by big data and deep convolutional neural network (CNN), the performance of face recognition is becoming comparable to human. Using private large scale training datasets, several groups achieve very high performance on LFW, i.e., 97% to 99%. While there are many open source implementations of CNN, none of large scale face dataset is publicly available. The current situation in the field of face recognition is that data is more important than algorithm. To solve this problem, we propose a semi-automatical way to collect face images from Internet and build a large scale dataset containing 10,575 subjects and 494,414 images, called CASIA-WebFace. To the best of our knowledge, the size of this dataset rank second in the literature, only smaller than the private dataset of Facebook (SCF). We encourage those data-consuming methods training on this dataset and reporting performance on LFW.

The statistics of the proposed CASIA-WebFace dataset is shown in Table 1. Except for Facebook's SFC dataset, the scale of CASIA-WebFace has the largest scale. For users' privacy issue, maybe SFC will never be open to research community. The features of Microsoft's WDRef dataset was publicly available from 2012 but it is inflexible for advanced researches. Among the datasets listed in the table, CASIA-WebFace+LFW is the most suitable combination for large scale face recognition in the wild. If you feel the accuracy of LFW has been saturated by the current state-of-the-art method. BLUFR is a more challenging protocol to report your results.
-->

## Celeb Faces
项目主页:[Large-scale CelebFaces Attributes (CelebA) Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

Celeb Faces数据集是一个大规模人脸属性数据集, 包含10,177个名人的共计202,599张脸部图片。每张图片包含5个面部特征点标记以及40个二值属性标记，图片具有较大的姿态和背景变化,是一个海量，多样以及具有丰富标记信息的人脸数据集，可用于人脸属性识别，人脸检测以及特征点定位等机器视觉任务的训练集和测试集。例如，著名的DeepID系列算法就是利用该数据集的图片以及特征点标记提取人脸patch训练其深度学习模型。

<!--
CelebFaces Attributes Dataset (CelebA) is a large-scale face attributes dataset with more than 200K celebrity images, each with 40 attribute annotations. The images in this dataset cover large pose variations and background clutter. CelebA has large diversities, large quantities, and rich annotations, including

10,177 number of identities,
202,599 number of face images, and
5 landmark locations, 40 binary attributes annotations per image.

The dataset can be employed as the training and test sets for the following computer vision tasks: face attribute recognition, face detection, and landmark (or facial part) localization.
-->

## PubFig
项目主页:[PubFig: Public Figures Face Database](http://www.cs.columbia.edu/CAVE/databases/pubfig/)

## PubFig83
项目主页:[PubFig83: A resource for studying face recognition in personal photo collections](http://vision.seas.harvard.edu/pubfig83/)

## PubFig83+LFW
项目主页:[PubFig83 + LFW Dataset](http://www.briancbecker.com/blog/research/pubfig83-lfw-dataset/)

## WDRef
WDRef只提供feature公开下载，即LE和LBP特征，不提供原始图片下载。

## LFW
LFW数据集(Labeled Faces in the Wild)是目前学术界最常用的人脸认证性能测试数据集合。该库共包含5749个人在自然条件下的13,233幅图像，目的是提高自然条件下人脸识别的精度。其中1680人有2幅及以上的图像，4069人只有一幅图像。图像均为250*250大小的JPEG格式，其中绝大多数为彩色图片，也有少数为灰度图。大多数图像都是由Viola-Jones的检测器得到人脸区域之后，被裁剪为固定大小图片，有少量图片人为地从false positive中得到。View1用于训练和验证，主要用于模型选择；而View2用于测试，作为结果评定的标准。

## 其他
[SFC Facebook Social Face Classification]()

项目主页:[Face Recognition for Web-Scale Datasets](http://enriquegortiz.com/wordpress/enriquegortiz/research/face-recognition/webscale-face-recognition/)
提供Facebook和LFW+Pubifg数据集原始图片以及特征下载，很大，若干个G.
