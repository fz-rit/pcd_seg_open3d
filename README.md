# pcd_seg_open3d
Point Cloud Segmentation with Open3D_ml

# Installation

1. create and activate a new environment: 
	conda create -n pcd_seg_open3d_env python=3.12
	conda activate pcd_seg_open3d_env
2. upgrad pip
	pip install --upgrade pip
3. install open3d
	pip install open3d
4. Install torch with cuda, open3d v0.19.0 only supports torch2.2.*; Don't use the requirements.txt files in the official repository!!
	pip install torch==2.2.2 torchvision==0.17.2 torchaudio==2.2.2 --index-url https://download.pytorch.org/whl/cu121
5. Downgrad numpy: 
	pip install "numpy<2.0.0"
6. Test the installation:
	python -c "import open3d.ml.torch as ml3d"
	python -c "import torch; print(torch.cuda.is_available())"


