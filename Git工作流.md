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
## 用户设置
Open the working directory

%% 打开工作目录 %%

`$ git config --global user.name YourName`

`$ git config --global user.email YourEmail`

`$ git init`
%% 初始化 %%

---

## 文件操作

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
## from 工作区 to 缓存区
1. 工作区 to 暂存区
`$ git add FileName.md
`



