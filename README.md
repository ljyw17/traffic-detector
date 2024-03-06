# traffic-detector

Only the core codes are available here.

This project is developed based on mmdetection.

Please refer to the tutorial: https://github.com/open-mmlab/mmdetection

Only a simple installation reference is provided here.

conda create --name openmmlab python=3.8 -y

conda activate openmmlab

pip install openmim

mim install mmcv-full

git clone https://github.com/open-mmlab/mmdetection.git

cd mmdetection

pip install -r requirements/build.txt

pip install -v -e .
