## Pure implementation of FCOS
Paper: [FCOS:Fully Convolutional One-Stage Object Detection](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tian_FCOS_Fully_Convolutional_One-Stage_Object_Detection_ICCV_2019_paper.pdf)(ICCV 2019)

![imgs](https://github.com/leviome/fcos_pure/blob/main/assets/FCOS.jpg)

---
# Fast Demo
### For Chinese guys:
you can download the pretrained model by **CSDN** to avoid annoying BaiduPan, click [here](https://download.csdn.net/download/leviopku/13125465) to download.
(5 C-points is needed, if you have problems with C-point, you can contact my [CSDN](https://muzhan.blog.csdn.net) to get model for free.)

after downloading **fcos_pretrained_model.pth**, please put it to folder 'checkpoint', and put the image you want for test to folder 'test_images'
```text
python detect.py

```
then, you can find results at 'out_images/':

![imgs](https://github.com/leviome/fcos_pure/blob/main/out_images/t1.jpg)
