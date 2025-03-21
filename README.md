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
  <a href="https://typora-theme.netlify.app">
    <img src="https://api.netlify.com/api/v1/badges/6ca72e1b-7dc6-4d51-8542-e07bf9ad0a88/deploy-status" alt="Netlify Status">
  </a>
</p>



## **1.概览**


> [!tip]
> **这里有两篇文章使用OneLight主题，可点击查看主题详细效果展示**
>
> 1. **[OneLight](https://bin-sites.pages.dev/onelight)**
> 2. **[计算机网络](https://bin-sites.pages.dev/net/计算机网络)**

---

![image-20250108140354139](https://s2.loli.net/2025/01/08/fNQF1ZCOgGydEUL.png)

![image-20250108140529374](https://s2.loli.net/2025/01/08/aMkKwdmVuTCtW4G.png)

![image-20250119102419998](https://s2.loli.net/2025/01/19/4jotBCzeDdlAwfF.png)

<details><summary><kbd>展开查看更多截图</summary></kbd>
  <img src="https://s2.loli.net/2025/01/08/Ir1mgZCto4YS6lj.png"></br>
  <img src="https://s2.loli.net/2025/03/04/YzmsQOAFJ2UkpC7.png"></br>
  <img src="https://s2.loli.net/2025/01/08/cAgBOqFoCMYE8S6.png"></br>
	一体化菜单界面
  <img src="https://s2.loli.net/2025/01/08/QF2UA9zPOW5X6ji.png"></br>
</details>

---

## 2.如何使用

### 2.1 下载文件（推荐）

> [!important]
>
> 1. 下载[主题文件压缩包](https://github.com/caolib/typora-onelight-theme/releases)
> 2. 在typora中选择 文件 → 偏好设置 → 外观 → 打开主题文件夹
> 3. 将下载的压缩包解压，将**css文件**和**文件夹**粘贴到typora的主题文件夹中
> 4. 重启Typora然后在菜单栏切换主题，大功告成

### 2.2 克隆

> [!caution]
>
> **如果你想克隆本仓库，为了避免克隆到其他分支，请使用下面这条命令,这样只会克隆主分支**
>
> ```shell
> git clone --single-branch https://github.com/caolib/typora-onelight-theme.git
> ```

---

## **3.关于字体**

在`onelight.css`文件开头设置了默认字体，可以自行修改，字体文件在[fonts](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/fonts)文件夹下
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)

---

## **4.背景图片**

> [!important]
>
> 背景图片在`onelight/img`文件夹下，文件夹下有几张准备好的图片，你也可以添加自己的图片（最好使用透明背景的图片），然后在css文件中搜索 `background-image`找到下面代码替换图片路径
>
> ```css
> content {
>      background-color: transparent;
>      /* 可以替换此处的图片，不想显示可以将这段整个注释掉 */
>      background-image: url('./onelight/img/bg.gif');
>      background-position: 100% 100%;
>      background-repeat: no-repeat;
>      background-size: 100px auto; /* 调整图片显示大小 */
>      transition: background-image .5s ease-in-out, background-size .5s ease-in-out
> }
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



