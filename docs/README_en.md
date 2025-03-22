<h1 align='center'>OneLight Theme For Typora</h1>

<p align="center">
    English
    |
    <a href="https://github.com/caolib/typora-onelight-theme">简体中文</a>
</p>
<p align="center">
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/total?labelColor=grey&color=blue" alt="Downloads">
  <img src="https://img.shields.io/github/v/release/caolib/typora-onelight-theme?labelColor=grey&color=red" alt="Release">
  <img src="https://img.shields.io/github/license/caolib/typora-onelight-theme" alt="License">
  <img src="https://img.shields.io/github/stars/caolib/typora-onelight-theme" alt="Stars">
  <img src="https://img.shields.io/github/issues/caolib/typora-onelight-theme?label=Issues" alt="Issues">
  <img src="https://img.shields.io/github/last-commit/caolib/typora-onelight-theme?label=Last%20Commit" alt="Last Commit">
</p>


## **1. Overview**


> [!tip]
> **Here are two articles using the OneLight theme, click to see detailed theme effects**
>
> 1. **[OneLight](https://bin-sites.pages.dev/onelight)**
> 2. **[Computer Network](https://bin-sites.pages.dev/net)**

---

![image-20250108140354139](https://s2.loli.net/2025/01/08/fNQF1ZCOgGydEUL.png)

![image-20250108140529374](https://s2.loli.net/2025/01/08/aMkKwdmVuTCtW4G.png)

![image-20250119102419998](https://s2.loli.net/2025/01/19/4jotBCzeDdlAwfF.png)

<details><summary><kbd>Click to see more screenshots</summary></kbd>
  <img src="https://s2.loli.net/2025/01/08/Ir1mgZCto4YS6lj.png"></br>
  <img src="https://s2.loli.net/2025/03/04/YzmsQOAFJ2UkpC7.png"></br>
  <img src="https://s2.loli.net/2025/01/08/cAgBOqFoCMYE8S6.png"></br>
	Integrated menu interface
  <img src="https://s2.loli.net/2025/01/08/QF2UA9zPOW5X6ji.png"></br>
</details>

---

## 2. How to Use

### 2.1 Download Files

> 1. Download the [theme file package](https://github.com/caolib/typora-onelight-theme/releases)
> 2. In Typora, select File → Preferences → Appearance → Open Theme Folder
> 3. Unzip the downloaded package, paste the **css files** and **folders** into Typora's theme folder
> 4. Restart Typora and switch the theme from the menu bar, done

### 2.2 Clone

> [!caution]
>
> 1. Open a command line in Typora's themes folder
>
> 2. **To avoid cloning irrelevant files from other branches, be sure to use the command below to clone!! Otherwise, it will take a long time to download**
>
>    ```shell
>    git clone --single-branch https://github.com/caolib/typora-onelight-theme.git
>    ```

---

## **3. About Fonts**

The default font is set at the beginning of the `onelight.css` file, you can modify it yourself. The font files are in the [fonts](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/fonts) folder
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)

---

## **4. Background Image**

> [!important]
>
> Background images are in the `onelight/img` folder. There are several prepared images in the folder, you can also add your own images (preferably with a transparent background), then search for `background-image` in the css file to find the code below to replace the image path
>
> ```css
> content {
>      background-color: transparent;
>      /* You can replace the image here, or comment out this section if you don't want it displayed */
>      background-image: url('./onelight/img/bg.gif');
>      background-position: 100% 100%;
>      background-repeat: no-repeat;
>      background-size: 100px auto; /* Adjust the display size of the image */
>      transition: background-image .5s ease-in-out, background-size .5s ease-in-out
> }
> ```
>
> <img src="https://s2.loli.net/2025/03/05/7Ds8SCmvWnkwraM.png" style="zoom: 50%;" />

---

## 5. Others

<img align='right' src="https://s2.loli.net/2025/01/04/zt7O3daMLDC5EHW.png" alt="Like" />⭐ If you like the theme, please give it a star, thank you 🙏!

✅ The theme looks better in integrated mode ✨

❓ If you have any questions, you can ask in [Issues](https://github.com/caolib/typora-onelight-theme/issues), all opinions are welcome

📄 The [docs](https://github.com/caolib/typora-onelight-theme/tree/onelight/docs) folder contains markdown files of example articles 📄

🖼️ The [img](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/img) folder contains background images for the theme, you can delete them if not needed

[translated by AI]
