### 2.4 绑定本地仓库到GitHub

#### 进入文件夹路径，初始化为git仓库

```
git init
```

如果初始化错误，将.git隐藏文件删除并重新初始化

#### 绑定远程仓库

```
git remote add origin 仓库地址
```

可以使用 命令查看当前git仓库绑定的远程仓库

```
git remote -v
```

如果绑定错误，可以移除绑定

```
git remote remove origin
```

