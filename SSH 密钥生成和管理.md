---
loop: true
autoSlideStoppable: false
autoSlide: 10000
transition: fade
slideNumber: false
enableTimeBar: true
timeForPresentation: 100
---


**生成 SSH 密钥**： 

在 Git Bash 终端中，执行以下命令生成 SSH 密钥：
`ssh-keygen -t rsa -b 4096 -C "your_email@example.com" -f /c/Users/Administrator/.ssh/id_rsa`


这个命令会生成一对新的 SSH 密钥，根据提示操作完成密钥生成过程。

---


**添加公钥到 GitHub 账户**： 

打开生成的公钥文件，通常位于 `C:\Users\YourUsername\.ssh\id_rsa.pub`，将公钥内容复制到剪贴板中。然后登录到你的 GitHub 账户，在 "Settings" > "SSH and GPG keys" > "New SSH key" 中添加你的公钥。

---

**使用 SSH 连接**： 在你的 Git 项目中使用 SSH URL，例如 `git@github.com:username/repo.git`，来连接到 GitHub 远程仓库。这样 Git 就会使用你的 SSH 密钥来进行安全的身份验证。

---

you can in Windows set and use SSH 密钥与 GitHub to save conect。


---

