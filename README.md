# MISC

## Introduction

The maceral components are closely related to the physical and chemical properties of coal, precise identification of the maceral components has a multitude of uses across various industry sectors, including hydrogenation, combustion, carbonization, and gasification [1-3].In order to improve the objectivity and efficiency of analysis, an automatic framework to identify the maceral components is presented in this study.
The proposed maceral analysis method, MISC, based on image segmentation and classification makes it possible to identify the maceral composition automatically and intelligently. Considering the complex and heterogeneous nature of coal, a two-level coarse-to-fine clustering method based on K-means is employed to divide microscopic images into a sequence of regions with similar attributes (i.e., binder, vitrinite, liptinite, and inertinite). Furthermore, comprehensive features along with random forest are utilized to automatically classify binder and seven types of maceral components, including vitrinite, fusinite, semifusinite, cutinite, sporinite, inertodetrinite and micrinite. 
Evaluations on 39 microscopic images show that the proposed method achieves state-of-the-art accuracy of 90.44%. The software can be used to support the decisions of petrologists in classifying maceral components.

**Note**: this package requires installing Matlab **R2016b** or latter.

## Usage

1. The software of MISC was implemented in Matlab and could be run on
Windows systems without installing. MISC distributions for Windows can be found at 
https://github.com/GuyooGu/MISC-Master. we recommend that users can download the latest release. 

2. After downloading, please double-click on the file 'MISC.exe' to run the executable file：MISC.exe

3. Select an image（such as test_image_1.bmp） for analysis.

4. Select the segmentation method and the classification methods. 
The segmentation results are presented as 4 subfigures, corresponding to the binders and 3 maceral groups. The classification result for each object detected by image segmentation is shown with different colors for visualization. 


## Updation

Our software will be updated routinely based on users’suggestions and advice. Thus, your feedback is greatly important for our future upgrading. Please do not hesitate to contact with us if you have any concerns.


## Citation 
We hope you can cite the article if the software has been helpful for your work.                
[1] Wang, H.; Lei, M.; Chen, Y.; Li, M.; Zou, L. Intelligent Identification of Maceral Components of Coal Based on Image Segmentation and Classification. Applied Sciences 2019, 9, 3245.


## FeedBack 

Any suggestions and problems, please feel free to let us know via Email: liangzou@ece.ubc.ca. Thanks a lot.

## License 

Released under MIT license

## Reference  
1.Mlynarczuk, M.; Skiba, M. The application of artificial intelligence for the identification of the maceral groups and mineral components of coal. Comput. Geosci. 2017, 103, 133-141.     
2.Rallakis, D.; Michels, R.; Brouand, M.; Parize, O.; Cathelineau, M. The Role of Organic Matter on Uranium Precipitation in Zoovch Ovoo, Mongolia. Minerals. 2019, 9, 310.     
3.Chaudhuri, S.N. Coal macerals. Encycl. Mineral Energy Policy. 2016, 1-5.


