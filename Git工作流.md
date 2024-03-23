---
loop: true
autoSlideStoppable: false
autoSlide: 10000
transition: fade
slideNumber: false
enableTimeBar: true
timeForPresentation: 100
---

![[Pasted image 20240323140215.png]]



---
### 用户设置
Open the working directory

%% 打开工作目录 %%

`$ git config --global user.name YourName`

`$ git config --global user.email YourEmail`

`$ git init`
%% 初始化 %%

---

### 文件操作

`$ echo "file content" > FileName.md`

%% 添加文件 %%

`$ git status`
%% 查看当前状态 %%

```shell
On branch main # 当前所处分支
No commits yet
Untracked files: # 未追踪文件
  (use "git add <file>..." to include in what will be committed)
```

---
### from 工作区 to 缓存区
1. 工作区 to 暂存区

`$ git add FileName.md`

`$ git commit FileName.md`

在vim中编辑并退出

> 附：快速提交并添加说明

`$ git commit FileName.md -m "commit instructions"`

%% 提交说明 %%

---

### 查看提交日志

`$ git log`

```shell
commit d86f441f47ba2788c8493a12573396dfd42dbcaf (HEAD -> main)
Author: YourName  <YourEmail>
Date:   Sat Mar 23 19:44:03 2024 +0800

    版本2
```

---

### 添加忽略文件
`touch .gitignore`

编辑 .gitignore文件

例：
```
.obsidian
```

---

### 创建工作分支并查看

`$ git branch develop`


`$ git branch`

```Bash
$ git branch
  develop
* main
```

`git checkout develop `



