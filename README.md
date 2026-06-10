**1. VIFNet**

Source: https://github.com/mengyu212/VIFNet_dehazing.git

>@article  
{yu2024vifnet,  
  title={VIFNet: An end-to-end visible-infrared fusion network for image dehazing},  
  author={Yu, Meng and Cui, Te and Lu, Haoyang and Yue, Yufeng},  
  journal={Neurocomputing},  
  pages={128105},  
  year={2024},  
  publisher={Elsevier}  
}


***
**training**

>cd your/path/to/VIFNet  
python train_vifnet.py

The trained models will be placed in the /trained_models folder.

***
**testing**
>cd your/path/to/VIFNet  
python test.py

The predicted image will be placed in the /pred_imgs_rgbt folder.

**2. FADE**

Source: https://github.com/hangxiaotian/CEEF.git

>@arctile{liu2021joint, % CEEF  
  title={Joint Contrast Enhancement and Exposure Fusion for Real-World Image Dehazing},  
  author={Liu, Xiaoning and Li, Hui and Zhu, Ce},   
  journal={IEEE Transactions on Multimedia},   
  year={2022},  
  volume={24},  
  number={},  
  pages={3934-3946},  
  doi={10.1109/TMM.2021.3110483}
}

