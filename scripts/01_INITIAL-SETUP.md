# Initial Setup

The purpose of this file is to document the workflow of the initial setup of this project.

## Directory Creation & Navigation

```sh
mkdir dailyDo
cd dailyDo
```

## PipEnv Installation Using Pip3

```sh
pip3 install pipenv
```

## Creation & Activation of Virtual Environment

```sh
pipenv shell
```

## Deactivation of Virtual Environment

```sh
deactivate
```

## Re-activation of Virtual Environment

```sh
pipenv shell
```

## Git Initialization

```sh
git init
```

## Created a GitIgnore File (Include Python Check ✅)

## Checking Any Remote Git Repositories Connection

```sh
git remote -v
```

## Creation of a new Repository In Github

## Creation of a `README` File

## Connecting Remote Repository With Local Repository

```sh
git remote add origin https://github.com/jeet-khondker/dailyDo.git
```

## Pulling the Remote Repository Contents In Local

```sh
git pull origin dev
```

## Checking out to new default `dev` branch

```sh
git checkout dev
```

## Checking the current and available branches

```sh
git branch
```

## Deleted `master` branch

```sh
git branch -D master
```

## Checking Git Status

```sh
git status
```

## Adding File(s) To Git

```sh
git add file-name
```

## Commit With A Tag & A Message

```sh
git commit -m "tag : Message"
```

## Pushing the code to Remote

```sh
git push
```