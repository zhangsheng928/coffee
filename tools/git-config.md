# config

全局配置文件： ~/.gitconfig
每个仓库的配置文件: 	.git/config

## 配置别名

```
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch
git config --global alias.unstage 'reset HEAD'
```


```
[alias]
    ad = add
    co = checkout
    ss = status
    cm = commit -m
    br = branch
    bm = branch -m
    bd = branch -D
    cb = checkout -b
    df = diff
    ls = log --stat
    lp = log -p
    plo = pull origin
    plode = pull origin develop
    pho = push origin
```




## 常用命令

```
git status
git add .                           添加所有修改的文件
git add file1 file2
git add dir

git commit -m "chang log"
git push origin master              提交到远程主干     

```

```
git reset HEAD file                 把暂存区的修改撤销掉（unstage），重新放回工作区

```


```
git stash 
git stash pop
```

