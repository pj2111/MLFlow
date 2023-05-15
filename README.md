create env
```bash

conda create-n wineeq python=3.7 -y
```

activate env
```
bash
conda activate wineeq
```
install requirements

pip install requirements.txt

git commit

  822  pip install dvc
  823  pip install -r requirements.txt
  824  pip install -r requirements.txt
  825  touch README.md
  826  touch template.py
  827  python template.py
  828  python template.py
  829  mkdir data_given
  830  git init
  831   git config
  832  dvc init
  833  dvc add datagiven/winequality.csv
  834  dvc add data_given/winequality.csv
  835  git add ,
  836  git add .
  837  git commit -m "first commit"




create env 

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirements.txt
```
download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

```bash
git init
```
```bash
dvc init 
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```

oneliner updates  for readme

```bash
git add . && git commit -m "update Readme.md"
```
```bash
git remote add origin https://github.com/c17hawke/simple-dvc-demo.git
git branch -M main
git push origin main
```

tox command -
```bash
tox
```
for rebuilding -
```bash
tox -r 
```
pytest command
```bash
pytest -v
```

setup commands -
```bash
pip install -e . 
```

build your own package commands- 
```bash
python setup.py sdist bdist_wheel
```