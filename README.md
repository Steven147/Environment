# Environment 我的环境仓库

- [Environment 我的环境仓库](#environment-%e6%88%91%e7%9a%84%e7%8e%af%e5%a2%83%e4%bb%93%e5%ba%93)
  - [macOS 环境搭建](#macos-%e7%8e%af%e5%a2%83%e6%90%ad%e5%bb%ba)
    - [设置](#%e8%ae%be%e7%bd%ae)
  - [Alfred： mac入口、文件管理、脚本载体](#alfred-mac%e5%85%a5%e5%8f%a3%e6%96%87%e4%bb%b6%e7%ae%a1%e7%90%86%e8%84%9a%e6%9c%ac%e8%bd%bd%e4%bd%93)
  - [homebrew](#homebrew)
  - [fq过程](#fq%e8%bf%87%e7%a8%8b)
  - [邮箱同步](#%e9%82%ae%e7%ae%b1%e5%90%8c%e6%ad%a5)
    - [anaconda](#anaconda)
    - [软件安装](#%e8%bd%af%e4%bb%b6%e5%ae%89%e8%a3%85)
  - [百度网盘：网盘、下载器](#%e7%99%be%e5%ba%a6%e7%bd%91%e7%9b%98%e7%bd%91%e7%9b%98%e4%b8%8b%e8%bd%bd%e5%99%a8)
  - [chrome：网页书签、扩展插件](#chrome%e7%bd%91%e9%a1%b5%e4%b9%a6%e7%ad%be%e6%89%a9%e5%b1%95%e6%8f%92%e4%bb%b6)
  - [VScode：文本编辑、扩展插件](#vscode%e6%96%87%e6%9c%ac%e7%bc%96%e8%be%91%e6%89%a9%e5%b1%95%e6%8f%92%e4%bb%b6)

储存与编程、代码、workflow、脚本相关的
基础软件、配置文件

## macOS 环境搭建

[Mac软件管家](https://mp.weixin.qq.com/s/mVxJYiGrfselJx1b9XdvYw)

### 设置

三指拖移：完全替代**点击及拖动**

## Alfred： mac入口、文件管理、脚本载体

> ```sudo mdutil -a -i on``` 
> 如果搜索失败，试着打开索引试试

- 同步：[Syncing Your Alfred Settings Between Macs](https://www.alfredapp.com/help/advanced/sync/)
  - github repositories：Environment/Alfred
  - advanced -> Syncing -> set preferrence folders...

- [Tutorial-Alfred-Workflow](http://www.deanishe.net/alfred-workflow/tutorial.html)
- [Github-A collection of Alfred 3 and 4 workflows that will rock your world](https://github.com/zenorocha/alfred-workflows)
- [Workflows](https://www.alfredapp.com/help/workflows/)

## [homebrew](https://brew.sh/)

> brew install <package name> // 安装
> brew upgrade <package name> // 更新
> brew info <package name> // 查看信息
> brew uninstall <package name> // 卸载
> brew search <package name> // 搜索
> brew list // 查看安装的包

使用清华大学开源软件镜像站中的Homebrew 镜像来提升速度：

```shell
 cd "$(brew --repo)"
 git remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/brew.git
 ​
 cd "$(brew --repo)/Library/Taps/homebrew/homebrew-core"
 git remote set-url origin https://mirrors.tuna.tsinghua.edu.cn/git/homebrew/homebrew-core.git
 ​
 brew update
```

## fq过程

[KOPCLOUD加速器 最新地址发布](https://kopcloud-com.oss-cn-hongkong.aliyuncs.com/)

[KOPCLOUD加速器 永久域名（需翻墙访问）](https://www.kopcloud.com/)

购买套餐，下载客户端

[**软件需求**](https://wiki.kopjiasu.top/)

- macOS：shadowsocks
- iOS：[shadowrocket](https://github.com/v2net/Apple)
  - 下载
    - 注册美区appid
    - 自动发货-价值$2.99的苹果美区Shadowrocket小火箭兑换码
    - 通过App Store兑换渠道兑换
  - 填入[订阅地址](https://www.kopcloud.com/user)，自动同步

## 邮箱同步

- [QQ邮箱，常联系](https://mail.qq.com/)
  - 账户，开启服务，生成授权码
  - qq安全中心app
- [edu邮箱 苹果IOS 邮件应用如何连接邮箱](https://net.sjtu.edu.cn/info/1079/1299.htm)

### [anaconda](https://www.anaconda.com/)


windows powershell [准备](https://blog.csdn.net/www110120119/article/details/97613040)
> windows 在powershell中使用需要先更新conda
```shell
> conda init powershell
```

激活环境

```shell
> activate <name>
```


### 软件安装

## 百度网盘：网盘、下载器

[百度网盘](http://pan.baidu.com/download#pan)：[在线网盘](https://pan.baidu.com/disk/home?#/all?path=%2F&vmode=list)

## [chrome](https://www.google.cn/chrome/index.html)：网页书签、扩展插件

  1. [谷歌访问助手](https://www.crx4chrome.com/crx/49307/)

> 可以用翻q插件完全代替

## [VScode](https://code.visualstudio.com/)：文本编辑、扩展插件

- c++：

```shell
> g++ main.cpp -o problem
> ./problem
```

- 同步：
  > Sync: 上传完成。[Gist](https://gist.github.com/mine)ID:1add6afffd60e8846d95dee2ff943089。请复制这个 ID 并将其用于其他设备来下载配置。
