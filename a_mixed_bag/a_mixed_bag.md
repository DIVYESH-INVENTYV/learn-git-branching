## LEVEL - 1: Grabbing Just 1 Commit

### commands used

```
git checkout main
git cherry-pick c4
```

### Screenshot

![alt text](image-10.png)

## LEVEL - 2: Juggling Commits

### commands used

```
git rebase -i c1
git commit --amend
git rebase -i c1
git checkout main
git merge main
```

### Screenshot

![alt text](image-11.png)

## LEVEL - 3: Juggling Commits #2

### commands used

```
git rebase -i c1
git checkout main
git cherry-pick c2' c3
```

### Screenshot

![alt text](image-12.png)

## LEVEL - 4: Git tags

### commands used

```
git tag v0 c1
git tag v1 c2
git checkout c2
```

### Screenshot

![alt text](image-13.png)

## LEVEL - 5: Git describe

### commands used

```
git describe side
git describe main
git describe bugFix
git commit
```

### Screenshot

![alt text](image-14.png)
