## Creating a new branch `frontend`

```
git branch frontend
```

## Pushing The New Branch To Remote Git

```
git push origin frontend
```

## Checking Out To The New Created Branch `frontend`

```
git checkout frontend
```

## Pushing the code to Remote Branch `frontend` (For the 1st Time)

```
git push
git push --set-upstream origin frontend
```

## Checking out to `dev` branch

```
git checkout dev
```

## <ins>Merging `frontend` branch with `dev` branch</ins>

- Note: `-no-ff` tells Git to retain all commit messages prior to the merge.
- This will make tracking changes easier in the future.

```
git merge frontend --no-ff
```

## Commit with a Tag & Message of why the merge is necessary

```
"tag : Message"
```

- Enter `i`
- After finishing, press `esc` and type `:wq` to save and exit

## Pushing Local Contents To Git Remote

```
git push
```

## Making all branches aligned with `dev` branch

```
git checkout dev
git pull
git checkout commited-branch-name
git merge dev
git push
```

> The branches which are not aligned with the `dev` branch is not required to be up to date with `dev` branch unless required.

```
git checkout not-aligned-branch
git merge dev
git push
```
