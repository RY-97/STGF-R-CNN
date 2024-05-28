1 Code description <br/>
  1.1: The code .yml file used has been uploaded and is in the root directory ../STGF-R-CNN/faster_rcnn_swin_tiny_fpn_gn_3x.yml<br/>
  1.2: You need to place the faster_rcnn_swin_tiny_fpn_gn_3x.yml file in Paddle's folder ../STGF-R-CNN/config/faster_rcnn. Just copy the path when running.<br/>
  1.3: Pay attention to version compatibility issues. The PaddleDetection version used is:<br/>
  PaddleDetection：https://github.com/PaddlePaddle/PaddleDetection <br/>
  full_version    = '2.4.0' <br/>
  commit          = 'bb4fbe84252608a3bb52dc794fec10af169b5c0e' <br/>

2 For details on the installation of Paddle, see：https://github.com/PaddlePaddle/PaddleDetection <br/>

3 Dataset configuration file<br/>
  ../configs/datasets/iMSC_pro_detection.yml and ../dataset/iMSC_pro<br/>

4 Training<br/>
   python tools/train.py -c configs/faster_rcnn/faster_rcnn_swin_tiny_fpn_gn_3x.yml -o<br/>
   
5 test <br>
 ![image](dataset/iMSC_pro/infer_result/iMSC-P9-B1_12_13.2.png)

6 datasets: The dataset used in this study is private. If you are interested in our work, please contact us.<br>


