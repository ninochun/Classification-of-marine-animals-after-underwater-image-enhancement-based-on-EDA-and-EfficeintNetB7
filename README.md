#基于EDA与EfficeintNetB7的水下图像增强后的海洋动物分类
<br>上海海事大学《PyTorch深度学习框架》结课论文<br/>
基于python编写，图像处理代码修改并借鉴https://github.com/hainh/sea-thru <br>
theory paper:https://openaccess.thecvf.com/content_CVPR_2019/papers/Akkaynak_Sea-Thru_A_Method_for_Removing_Water_From_Underwater_Images_CVPR_2019_paper.pdf<br/>
<br/>
代码介绍在smu_pytorch_final.ipynb中。<br/>
原始文件在data文件中，处理过的文件在afterdata文件中<br/>
dataprocessing.py文件可自行修改自己的数据集文件路径，将其写入data_paths.csv文件，读入csv文件进入画面增强脚本后，将模仿原始文件目录，放入afterdata文件夹中。<br/>
在EfficeintNetB7.py文件中，可基于EfficeintNet函数进行海洋生物识别,修改文件路径，可自行对比画面增强前后的区别。
