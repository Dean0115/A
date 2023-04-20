# Git command instruction 

1. Initialize git 
```
git init
```

2. Add file changes to the repository
```
git add .
```

3. Commit all changes to the repository

```
git commit -m "Add file changes to the repository"
```

4. Push the commit
```
git push origin main
```

## Branch 

1. List all branches
```
git branch
```

2. Create a new branch
```
git branch branch_name
```

3. Switch the branch
```
git checkout brach_name
```

## Merge 
1. Checkout the main branch
```
git checkout main
```

2. Merge 2 branches
```
git merge nhanh_kia
```

3. Push the branch
```
git push origin main
```

## Pull 
1. Check the current branch
```
git branch
```

2. Checkout the branch (if need)
```
git checkout branch_name
```

3. Pull the lastest code 
```
git pull 
```

or 
```
git pull origin branch_name
```

## Fetch 
1. Fetch the latest branch
```
git fetch
```

## Delete the branch
1. Check về nhánh không xóa (ví dụ: đứng ở main -> xóa bai1)
```
git checkout main
```

```
git branch -D bai1
```
