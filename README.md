这不是本人做的工程，本人正在学习数字图像处理，经同学获得此工程代码，由于联系不上原作，所以冒昧上传到本人github上，如有人知晓原作者或工程原码地址，敬请告知我，谢谢！

# GraphCut

本项目参考了https://github.com/NathanZabriskie/GraphCut  
GUI界面将在后续时间进行实现

## 运行环境
python3.6  
所需库函数：numpy,opencv-python,PyMaxflow     
  
## 代码运行步骤
1.python -i [输入文件名] -o [输出文件名]  
  例：python GraphCut.py -i resource/dood.jpg -o output
2.使用鼠标进行前后背景标注  
3.功能：  
  （1）‘esc’：退出；  
  （2）‘c’：清除所有标注；  
  （3）‘g’：进行图片分割；  
  （4）‘t’：前后背景标准的切换；  
  （5）‘s’：将分割后的图片保存到输出文件。  
