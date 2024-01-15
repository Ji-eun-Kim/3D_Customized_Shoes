<h1 align = "center"> 3D Shoes Customization </h1>

<h3 align="center"> D&A Conference Project  (2023-08 ~ 2023-11) </h3>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br>

#### Why I do this Project?
I want anyone to make easily own customization shoes. And I hope to made 3d shoes to be a real shoes in the future by developing 3D printing.

<br>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h3 align="left"> Method </h3>

#### 1. Make the mask of the shoes by using Segmentation
    -  Sometimes the masks are inaccurate so you have to check and trim it.


#### 2. Apply your style that you want to the shoe by Style Transfer Model


#### 3. Convert shoe to 3D object by 3D Reconstruction Model


<br>

<h4 align="left"> Reference Code </h4>

[Segment anything](https://github.com/facebookresearch/segment-anything)
```
@article{kirillov2023segany,
  title={Segment Anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C. and Lo, Wan-Yen and Doll{\'a}r, Piotr and Girshick, Ross},
  journal={arXiv:2304.02643},
  year={2023}
}
```

[CAP-VSTNet](https://github.com/linfengWen98/CAP-VSTNet)
```
@inproceedings{wen2023cap,
  title={CAP-VSTNet: Content Affinity Preserved Versatile Style Transfer},
  author={Wen, Linfeng and Gao, Chengying and Zou, Changqing},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={18300--18309},
  year={2023}
}
```

[One-2-3-45](https://github.com/One-2-3-45/One-2-3-45)
```
@article{liu2023one2345,
  title={One-2-3-45: Any single image to 3d mesh in 45 seconds without per-shape optimization},
  author={Liu, Minghua and Xu, Chao and Jin, Haian and Chen, Linghao and Xu, Zexiang and Su, Hao and others},
  journal={arXiv preprint arXiv:2306.16928},
  year={2023}
}
```

[DreamGaussian](https://github.com/dreamgaussian/dreamgaussian)
```
@article{tang2023dreamgaussian,
  title={DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation},
  author={Tang, Jiaxiang and Ren, Jiawei and Zhou, Hang and Liu, Ziwei and Zeng, Gang},
  journal={arXiv preprint arXiv:2309.16653},
  year={2023}
}
```
<br>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<br>
<div align="center">

<h2 align="center"> Demo Gif & transfered images </h2>

<br>

<p float="center">
  <img src="video.gif" alt="Animated gif pacman game" height="360px" width="640px" />
</p>

</div>


<br>
<div align="center">

![stronghold logo](result1.png)

<br>

![stronghold logo](result2.png)
</div>


## 느낀점 및 한계점

약 **6개월 동안 진행한** 첫 컨퍼런스 참여는 정말 의미있었다. 팀원들과의 협업을 통해 얻은 성취감은 상상 이상이었고, 나 자신에게는 **새로운 성장의 기회**를 가지게 해준 프로젝트였다. 프로젝트를 통해 얻은 지식과 경험을 **컨퍼런스에서 발표하고 공유하는 과정은 매우 소중한 경험**이었으며, 이번 경험을 통해 더 많은 프로젝트에 참여하고자 하는 욕구를 더욱 강하게 만들어주었다. 앞으로의 프로젝트에서도 이러한 성장과 협업의 경험을 더욱 향상시키고 싶다.     

<br>

<br>

## 팀원 및 담당 역할  

<팀원>  
- 전공생 5명   

<br>
  
<담당 역할>    
- SAM을 통한 segmentation 수행 및 mask 생성
- Style Transfer - CAP-VSTNet 연구
- Composition 코드 구현
- 전체 일정 관리
- 홀로그램 / 발표 PPT 제작

<br/>

<br>

## 발표 자료 

- 발표 자료  
https://drive.google.com/file/d/1Jt1fnHNPGgiIQA1vgt_MnyuqAvgECDib/view?usp=sharing  
