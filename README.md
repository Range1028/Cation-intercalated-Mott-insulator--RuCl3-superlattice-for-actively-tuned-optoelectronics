@article{yu2024vifnet,
  title={VIFNet: An end-to-end visible-infrared fusion network for image dehazing},
  author={Yu, Meng and Cui, Te and Lu, Haoyang and Yue, Yufeng},
  journal={Neurocomputing},
  pages={128105},
  year={2024},
  publisher={Elsevier}
}

training
cd your/path/to/VIFNet
python train_vifnet.py
The trained models will be placed in the /trained_models folder.

testing
cd your/path/to/VIFNet
python test.py
The predicted image will be placed in the /pred_imgs_rgbt folder.


