### Parent Repository of Anar Framework

#### Setup Guide

##### With .sh Script
```aidl

git clone https://github.com/Anar-Framework/anar-parent.git

cd anar-parent/script/setup/

bash setup.sh
```

##### With Python Script

```python
git clone https://github.com/Anar-Framework/anar-parent.git

cd anar-parent

pip install -r ./requirements.txt

mkdir ./../anar-framework

python ./script/setup/python/setup.py --org Anar-Framwork --echo-urls --threads 10 -o ./../anar-framework/
```
the script will clone all the required libraries and modules.

open the parent repository in `intellij` as new existing project. 

##### With Shell Script with Authentication
First open ./script/setup/setup_v2.sh file and set your username and password when you checkout the anar-parent repository
```python
git clone https://github.com/Anar-Framework/anar-parent.git

cd anar-parent

bash ./script/setup/setup_v2.sh
```
the script will clone all the required libraries and modules.