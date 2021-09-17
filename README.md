create env

```bash
virtualenv -p 'python_path' wineq
```

activate env
```bash
cd wineq\Scripts\
.\activate
```

created a req file
```
pip install -r requirements.txt
```

git init

dvc init

dvc add data_given\winequality.csv

git add .

git commit -m "first commit"


update the readme file
git add .
git commit -m "Updating the readme file"

git remote add origin https://github.com/SunnyTamang/simple-dvc-demo.git
git branch -M main
git push origin main