## Pure implementation of FCOS
Paper: [FCOS:Fully Convolutional One-Stage Object Detection](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tian_FCOS_Fully_Convolutional_One-Stage_Object_Detection_ICCV_2019_paper.pdf)(ICCV 2019)

FCOS is recognized as a nice anchor-free, one-stage detector because of its simple structure and high performance efficiency. This repo is aimed to reach a fast, pure implementation for FCOS. All of you can develop algorithms based on this repo.

![imgs](https://github.com/leviome/fcos_pure/blob/main/assets/FCOS.jpg)

---
# Fast Demo
### For Chinese guys:
you can download the pretrained model by **CSDN** to avoid annoying BaiduPan, click [here](https://download.csdn.net/download/leviopku/13125465) to download.
(Note that 5 C-points is needed. If you have problems with C-point, you can contact my CSDN account [木盏](https://muzhan.blog.csdn.net) to reach model for free.)

After downloading **fcos_pretrained_model.pth**, please put it to folder 'checkpoint', and put the images you want for test to folder 'test_images'
```text
python detect.py
```
Then, you can find results at 'out_images/':

![imgs](https://github.com/leviome/fcos_pure/blob/main/out_images/t1.jpg)
