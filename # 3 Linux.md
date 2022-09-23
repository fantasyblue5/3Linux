# 3 Linux
## markdown已上传github,链接如下：https://github.com/fantasyblue5/3Linux
## 任务-在虚拟机软件中安装配置 Ubuntu 发行版
### 1.在官网下载Ubuntu和VMware

![ubuntu](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/QQ图片20220907112556.png)
![vm](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/QQ图片20220907161623.png)

### 2.在vm上安装ubuntu
#### i.创建虚拟机并完成配置
![vm](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/QQ图片20220907162632.png)
![图片](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/QQ图片20220907162639.png)
#### ii.在虚拟机上安装ubuntu
* 这一过程忘记了截图……等待时间是真的很漫长……
* 最后达到的效果就是这样啦
![ubuntu](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/结果.png)

## 加分题-通过 VScode 的 Remote 插件连接至虚拟机
### 1.在vscode中安装Romote-ssh插件
### 2.在linux中开启ssh服务
* 安装ssh
  #### 输入如下命令：
  ```
  sudo apt-get install ssh
  ```
![](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/linux1.jpg)
* 开启ssh服务
  #### 输入：
  ```
  sudo service ssh start
  ```
![](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/kaiqi.png)
### 3.配置ssh-config文件
![图片](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/remote1.png)
* 其中HostName为虚拟机ip地址，User为虚拟机系统名
* 虚拟机ip地址获取方式：
  #### 输入ifconfig
![](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/ip1.jpg)
### 4.连接
* 点击linux并输入密码
![](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/lian1.png)
* 连接成功，显示如下界面
![](https://cdn.jsdelivr.net/gh/fantasyblue5/Jotang-img@main/img/lian2.png)

