# Project Log

## [Micro-Sprint-01] Setup Repository

* Created README.md, project logo (ChatGPT/Photoshop)
* Created GitHub repository - Mission Ready, Level 5, Mission 01, AI 
  * [mr-level-05-fsd-mission-01-ai](https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/)

  ```
  cd ~/mission-ready
  mkdir -p /level-05/mission-01/research && cd /level-05/mission-01/research
  nano README.md
  git init
  git add .
  git commit -m "repo - mr-level-05-fsd-mission-01-ai - first commit"
  git branch -M main
  git remote add origin https://[ghp_access_token]@github.com/Astrotope/mr-level-05-fsd-mission-01-ai.git
  git push -u origin HEAD
  ```
* Download the Stanford Cars Dataset
  *  Setup Python virtual environment

	```
	> python3 --version
	Python 3.8.3
	
	> pip3 install virtualenv
	
	> python3.10 --version
	Python 3.10.14
	
	> python3.10 -m venv venv
	
	> source venv/bin/activate
	
	> nano requirements.txt
	kagglehub
	
	> pip install -r requirements.txt
	
	> python3 --version
	Python 3.10.14
	
	# Download the dataset
	
	> nano download-standford-cars.py
	import kagglehub
	```
* Downolad the dataset

	```
	# Download latest version
	path = kagglehub.dataset_download("jessicali9530/stanford-cars-dataset")
	
	print("Path to dataset files:", path)
	
	> python3 download-standford-cars.py                                                                                                                                                                    ─╯
	Downloading from https://www.kaggle.com/api/v1/datasets/download/jessicali9530/stanford-cars-dataset?dataset_version_number=2...
	100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 1.82G/1.82G [04:50<00:00, 6.75MB/s]
	Extracting files...
	Path to dataset files: ~/.cache/kagglehub/datasets/jessicali9530/stanford-cars-dataset/versions/2
	
	> ls -all ~/.cache/kagglehub/datasets/jessicali9530/stanford-cars-dataset/versions/2
	   rwxr-xr-x   5   cmcewing   staff    160 B     Thu Nov 14 12:21:02 2024    ./
	   rwxr-xr-x   3   cmcewing   staff     96 B     Thu Nov 14 12:20:51 2024    ../
	   rw-r--r--   1   cmcewing   staff    385 KiB   Thu Nov 14 12:20:51 2024    cars_annos.mat
	   rwxr-xr-x   3   cmcewing   staff     96 B     Thu Nov 14 12:20:51 2024    cars_test/
	   rwxr-xr-x   3   cmcewing   staff     96 B     Thu Nov 14 12:21:02 2024    cars_train/
	
	[Training data here ... ~/.cache/kagglehub/datasets/jessicali9530/stanford-cars-dataset/versions/2/cars_train/cars_train]
	
	```
	
  * Unpack the annotations file

	```
	
	```	