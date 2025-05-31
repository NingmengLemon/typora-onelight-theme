<h1 align='center'>OneLight Theme For Typora</h1>

<p align="center">
    简体中文
    |
    <a href="https://github.com/caolib/typora-onelight-theme/blob/onelight/docs/README_en.md">English</a>
</p>
<p align="center">
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/total?labelColor=grey&color=blue" alt="Downloads">
  <img src="https://img.shields.io/github/v/release/caolib/typora-onelight-theme?labelColor=grey&color=red" alt="Release">
  <img src="https://img.shields.io/github/license/caolib/typora-onelight-theme" alt="License">
  <img src="https://img.shields.io/github/stars/caolib/typora-onelight-theme" alt="Stars">
  <img src="https://img.shields.io/github/issues/caolib/typora-onelight-theme?label=Issues" alt="Issues">
  <img src="https://img.shields.io/github/last-commit/caolib/typora-onelight-theme?label=%E4%B8%8A%E6%AC%A1%E6%8F%90%E4%BA%A4" alt="Last Commit">
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/latest/total">
  <img src="https://github.com/caolib/typora-onelight-theme/actions/workflows/ci.yml/badge.svg" alt="ci">
</p>

## 1.概览

> [!tip]
> **这里有两篇文章使用OneLight主题，可点击查看主题详细效果展示**
>
> 1. **[OneLight](https://bin-sites.pages.dev/onelight)**、**[OneLight-Dark](https://bin-sites.pages.dev/onelight/dark)**
> 2. **[计算机网络](https://bin-sites.pages.dev/net)**

---

![image-20250531153638583](https://s2.loli.net/2025/05/31/Bzxh8GMVeXnYHPb.png)

![image-20250531153718830](https://s2.loli.net/2025/05/31/lN4ZW7GFVAKdw3u.png)

![image-20250511190116728](https://s2.loli.net/2025/05/11/dDVoupIWsH9aQxq.png)

![image-20250511184920000](https://s2.loli.net/2025/05/11/c51PL9yEfrkOCeF.png)

![image-20250511200329113](https://s2.loli.net/2025/05/11/mUofcTY1qNb5OX9.png)

![image-20250511185936255](https://s2.loli.net/2025/05/11/ULwkB9dnPiTEpaM.png)

<details><summary><kbd>展开查看更多截图</summary></kbd>
  <img src="https://s2.loli.net/2025/05/11/23GUxWvkhDE4doF.png"></br>
  <img src="https://s2.loli.net/2025/05/11/JUrxQsdYvVg6OZe.png"></br>
  <img src="https://s2.loli.net/2025/05/11/aZsAW1kXDBqM2hV.png"></br>
  <img src="https://s2.loli.net/2025/05/11/x35yzoV2GC4vXIU.png"></br>
  <img src="https://s2.loli.net/2025/05/11/PrlOStnM3J4Tehz.png"></br>
  <img src="https://s2.loli.net/2025/05/11/4l1rUvLfhHQCc2g.png"></br>
</details>


---

## 2.如何使用

下面两种办法视自己方便程度选一种即可

### 2.1 下载文件

> 1. 下载[主题文件压缩包](https://github.com/caolib/typora-onelight-theme/releases)
> 2. 在typora中选择 文件 → 偏好设置 → 外观 → 打开主题文件夹
> 3. 将下载的压缩包解压，将**css文件**和**文件夹**粘贴到typora的主题文件夹themes中
> 4. 重启Typora然后在菜单栏切换主题，大功告成
>
> 这种方法的优点是下载的文件更少，只含有主题必须的文件，缺点是比较麻烦，如果后续想要更新需要重新下载进行替换

### 2.2 克隆

> [!caution]
>
> 1. 同上找到typora的主题文件夹themes，在这个文件夹下打开一个终端
>
> 2. **为了避免克隆到其他分支的无关文件，请一定要使用下面这条命令克隆！！否则你要下载很长时间**（项目fork自官方仓库，提交历史包含了gh-pages分支的记录）
>
>    ```shell
>    git clone --single-branch https://github.com/caolib/typora-onelight-theme.git
>    ```
>
> 这种方法的优点是比较方便，后续更新只需要`git pull`命令即可获取最新的提交，缺点是clone会将整个项目的文件下载下来，包括一些不必要的md文件等

---

## 3.关于自定义

### 3.1 文件夹结构

```
📂 themes                              # Typora 主题根目录
├── 📂 onelight                        # OneLight 主题资源目录
│   ├── 📂 fonts                       # 字体资源目录
│   │   ├── CascadiaCode.woff2        
│   │   └── MiaoZi-GuoZhiTi.woff2     
│   ├── 📂 img                         # 图片资源目录
│   │   ├── bg.gif                     
│   │   ├── bg2.gif                    
│   │   ├── bg3.gif                    
│   │   ├── bg4.gif                    
│   │   └── bg5.gif                    
│   └── 📂 style                       # 样式文件目录
│       ├── blockquote.css             # 引用块样式定义
│       ├── code.css                   # 代码块样式定义
│       ├── editor.css                 # 编辑器样式定义
│       ├── font.css                   # 字体样式定义
│       ├── list.css                   # 列表样式定义
│       ├── table.css                  # 表格样式定义
│       └── 📂 title                   # 标题样式目录
│           ├── title-colorful.css     # 彩色标题样式
│           └── title.css              # 默认标题样式
├── onelight-dark.css                  # OneLight 暗色主题样式文件
├── onelight.css                       # OneLight 主题的主样式文件
└── onelight.user.css                  # 用户自定义样式文件（仓库中没有，有需可以自己创建，优先级高）     
```

### 3.2 自定义配置

如果你想添加一些自己的样式，不建议你直接修改`onelight.css`文件。

你可以在`onelight.css`同级目录下新建一个`onelight.user.css`文件，将你的样式放在这个文件，它有更高的优先级，而且你后续要更新只需要更新`onelight.css`，不会覆盖你的样式

如果`onelight.user.css`无效，你可能要添加`!important`提高优先级

### 3.2 风格选择

#### 3.2.1 标题

##### 默认风格

见第一张截图中的各级标题

##### 多彩风格

如果你想使用多彩风格，你需要在`onelight.user.css`文件**顶部**添加，注意是顶部！

```css
@import './onelight/style/title/title-colorful.css';
```

![image-20250531154421564](https://s2.loli.net/2025/05/31/f7IV4CkcFxYP5ur.png)



---



## 4.关于字体

在`onelight.css`文件设置了默认字体（搜索root），可以自行修改，如果需要导入字体文件，可在`font.css`中配置
![](https://s2.loli.net/2025/05/31/xO8RQSmHkWTuhXz.png)

---

## 4.背景图片

> [!important]
>
> 背景图片在`onelight/img`文件夹下，文件夹下有几张准备好的图片，你也可以添加自己的图片（最好使用透明背景的图片），然后在`editor.css`文件中搜索 `bg.gif`找到下面代码替换图片名
>
> ```css
> content {
>     background-color: transparent;
>     background-image: url('../img/bg.gif');
>     background-position: 100% 100%;
>     background-repeat: no-repeat;
>     background-size: 100px auto;
>     transition: background-image .5s ease-in-out, background-size .5s ease-in-out
> }
> 
> ```
>
> <img src="https://s2.loli.net/2025/03/05/7Ds8SCmvWnkwraM.png" style="zoom: 50%;" />

---

## 5.其他

<img align='right' src="https://s2.loli.net/2025/01/04/zt7O3daMLDC5EHW.png" alt="喜欢" />⭐ 如果喜欢主题的话，请给一个star吧，感谢🙏！

✅ 一体化模式下主题效果更佳✨

❓ 有问题可以在 [Issues](https://github.com/caolib/typora-onelight-theme/issues) 提问，欢迎各种意见

📄 [docs](https://github.com/caolib/typora-onelight-theme/tree/onelight/docs)文件夹中有示例文章的markdown文件📄

🖼️ [img](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/img)文件夹中有主题的背景图片，如果不需要可以直接删除



