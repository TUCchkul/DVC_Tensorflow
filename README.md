# DVC -DL-TF -Demo

## commands - 
## create a new env 
```bash 
conda create -prefix ./env python=3.7 -y 
```
### activate new env with
```bash 
source activate ./env
```
### init dvc     
```bash 
git init  
dvc init 
```
### Create empty file 
```bash 
mkdir -p src/utils config
touch src/__init__.py src/utils/__init__.py params.yaml config/config.yaml src/stage_01_load_save.py src/utils/all_utils.py setup.py .gitignore