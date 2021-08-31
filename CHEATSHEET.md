# Cheat Sheet

Cheat sheet for common tasks

## Git

### Initialize Repository
```bash
# make new directory and cd to it
mkdir ./mydir
cd ./mydir

# initialize repository
git init

# create repository on github
gh repo create my-project
```

### Saving Changes
```bash
# check status of repository
git status

# add all changed files
git add .

# commit changes to repository
git commit -m "message"

# push commit to github
git push
```

## Python

### Installing a venv

```bash
# cd to directory
cd ./mydir

# install the venv
python3 -m venv ./venv

# activate the venv
source ./venv/bin/activate

# update pip if necessary
pip install --upgrade pip
```

### Setting up Jupyter in venv

```bash
# cd to directory
cd ./mydir

# activate the venv
source ./venv/bin/activate

# install jupyter lab
pip install jupyterlab
```