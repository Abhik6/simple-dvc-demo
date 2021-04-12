1. create env

```bash
conda create -n wineq python=3.7 -y
```

2. activate env

```bash
conda activate wineq
```

3. create a req file

4. install the requirements

```bash
pip install -r requirements.txt
```

5. download the data from

```bash
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
```

6.
```bash
git init
```

7.
```bash
dvc init
```

8.
```bash
dvc add data_given/winequality.csv
```

9.
```bash
git add .
```

10.
```bash
git commit -m "first commit"
```

11.
oneliner update for readme
```bash
git add . && git commit -m "update Readme.md"
```

12.
```bash
git remote add origin https://github.com/Abhik6/simple-dvc-demo.git

git branch -M main

git push -u origin main
```

13. To run the dvc.yaml (different Stages)
```bash
dvc repro
```

14. To check metrics through dvc
```bash
dvc metrics show
```

15. To check, track and compare metrics for different model runs
```bash
dvc metrics diff
```

16. To run tests
```bash
pytest -v
```

17.
To run tests using tox
```bash
tox
```

18. To run setup.py and create packages wherever __init__.py file present
```bash
pip install -e .
```

19. To check all installed packages
```bash
pip freeze
```

20. tox for rebuilding
```bash
tox -r
```

21. pytest command
```bash
pytest -v
```

22. Setup commands
```bash
pip install -e .
```

23. Build your own package commands
```bash
python setup.py sdist bdist wheel
```