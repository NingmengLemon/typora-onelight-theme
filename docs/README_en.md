<h1 align='center'>OneLight Theme For Typora</h1>

<p align="center">
    <a href="https://github.com/caolib/typora-onelight-theme/blob/onelight/README.md">简体中文</a>
    |
    English
</p>
<p align="center">
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/total?labelColor=grey&color=blue" alt="Downloads">
  <img src="https://img.shields.io/github/v/release/caolib/typora-onelight-theme?labelColor=grey&color=red" alt="Release">
  <img src="https://img.shields.io/github/license/caolib/typora-onelight-theme" alt="License">
  <img src="https://img.shields.io/github/stars/caolib/typora-onelight-theme" alt="Stars">
  <img src="https://img.shields.io/github/issues/caolib/typora-onelight-theme?label=Issues" alt="Issues">
  <img src="https://img.shields.io/github/last-commit/caolib/typora-onelight-theme?label=Last%20Commit" alt="Last Commit">
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/latest/total">
  <img src="https://github.com/caolib/typora-onelight-theme/actions/workflows/ci.yml/badge.svg" alt="ci">
</p>


## 1. Overview


> [!tip]
> **Here are two articles using the OneLight theme, click to see detailed theme effect demonstrations**
>
> 1. **[OneLight](https://bin-sites.pages.dev/onelight)**、**[OneLight-Dark](https://bin-sites.pages.dev/onelight/dark)**
> 2. **[Computer Networks](https://bin-sites.pages.dev/net)**

---

![image-20250531153638583](https://s2.loli.net/2025/05/31/Bzxh8GMVeXnYHPb.png)

![image-20250531153718830](https://s2.loli.net/2025/05/31/lN4ZW7GFVAKdw3u.png)

![image-20250511190116728](https://s2.loli.net/2025/05/11/dDVoupIWsH9aQxq.png)

![image-20250511184920000](https://s2.loli.net/2025/05/11/c51PL9yEfrkOCeF.png)

![image-20250511200329113](https://s2.loli.net/2025/05/11/mUofcTY1qNb5OX9.png)

![image-20250511185936255](https://s2.loli.net/2025/05/11/ULwkB9dnPiTEpaM.png)

<details><summary><kbd>Expand to see more screenshots</kbd></summary>
  <img src="https://s2.loli.net/2025/05/11/23GUxWvkhDE4doF.png"></br>
  <img src="https://s2.loli.net/2025/05/11/JUrxQsdYvVg6OZe.png"></br>
  <img src="https://s2.loli.net/2025/05/11/aZsAW1kXDBqM2hV.png"></br>
  <img src="https://s2.loli.net/2025/05/11/x35yzoV2GC4vXIU.png"></br>
  <img src="https://s2.loli.net/2025/05/11/PrlOStnM3J4Tehz.png"></br>
  <img src="https://s2.loli.net/2025/05/11/4l1rUvLfhHQCc2g.png"></br>
</details>

---

## 2. How to Use

### 2.1 Download Files

> 1. Download the [theme file package](https://github.com/caolib/typora-onelight-theme/releases)
> 2. In Typora, select File → Preferences → Appearance → Open Theme Folder
> 3. Extract the downloaded package, paste the **CSS files** and **folders** into Typora's theme folder (themes)
> 4. Restart Typora and switch the theme in the menu bar, and you're done
>
> The advantage of this method is that you download fewer files, containing only the necessary theme files. The disadvantage is that it's more complicated, and if you want to update later, you'll need to download and replace the files again.

### 2.2 Clone

> [!caution]
>
> 1. Find Typora's theme folder (themes) as mentioned above, and open a terminal in this folder
>
> 2. **To avoid cloning irrelevant files from other branches, please make sure to use the command below!! Otherwise, you'll have to download for a long time** (The project is forked from the official repository, and the commit history includes records from the gh-pages branch)
>
>    ```shell
>    git clone --single-branch https://github.com/caolib/typora-onelight-theme.git
>    ```
>
> The advantage of this method is that it's more convenient. For future updates, you only need to use the `git pull` command to get the latest commits. The disadvantage is that cloning will download all the project files, including some unnecessary md files, etc.

---

## 3. About Customization

### 3.1 Folder Structure

```
📂 themes                              # Typora theme root directory
├── 📂 onelight                        # OneLight theme resource directory
│   ├── 📂 fonts                       # Font resource directory
│   │   ├── CascadiaCode.woff2        
│   │   └── MiaoZi-GuoZhiTi.woff2     
│   ├── 📂 img                         # Image resource directory
│   │   ├── bg.gif                     
│   │   ├── bg2.gif                    
│   │   ├── bg3.gif                    
│   │   ├── bg4.gif                    
│   │   └── bg5.gif                    
│   └── 📂 style                       # Style file directory
│       ├── blockquote.css             # Blockquote style definition
│       ├── code.css                   # Code block style definition
│       ├── editor.css                 # Editor style definition
│       ├── font.css                   # Font style definition
│       ├── list.css                   # List style definition
│       ├── table.css                  # Table style definition
│       └── 📂 title                   # Title style directory
│           ├── title-colorful.css     # Colorful title style
│           └── title.css              # Default title style
├── onelight-dark.css                  # OneLight dark theme style file
├── onelight.css                       # OneLight theme main style file
└── onelight.user.css                  # User custom style file (not in repository, create as needed, higher priority)     
```

### 3.2 Custom Configuration

If you want to add your own styles, it's not recommended to modify the `onelight.css` file directly.

You can create a new `onelight.user.css` file in the same directory as `onelight.css`, and put your styles in this file. It has higher priority, and when you update later, you only need to update `onelight.css` without overriding your styles.

⚠️Add `onelight-dark.user.css` file for dark theme.

If `onelight.user.css` doesn't work, you may need to add `!important` to increase priority.

### 3.3 Style Options

#### 3.3.1 Headings

##### Default Style

See the headings in the first screenshot

##### Colorful Style

If you want to use the colorful style, you need to add the following at the **top** of the `onelight.user.css` file. Note that it must be at the top!

```css
@import './onelight/style/title/title-colorful.css';
```

![image-20250531154421564](https://s2.loli.net/2025/05/31/f7IV4CkcFxYP5ur.png)

## 4. About Fonts

Default fonts are set in the `onelight.css` file (search for root), which you can modify as needed. If you need to import font files, you can configure them in the `font.css` file.
![](https://s2.loli.net/2025/05/31/xO8RQSmHkWTuhXz.png)

---

## 5. Background Image

> [!important]
>
> Background images are in the `onelight/img` folder. There are several prepared images in the folder, and you can also add your own images (preferably with transparent backgrounds). Then search for `bg.gif` in the `editor.css` file to find the code below and replace the image name
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

## 6. Other

<img align='right' src="https://s2.loli.net/2025/01/04/zt7O3daMLDC5EHW.png" alt="Like" />⭐ If you like this theme, please give it a star, thank you! 🙏

✅ The theme works best in integrated mode ✨

❓ If you have any questions, you can ask in [Issues](https://github.com/caolib/typora-onelight-theme/issues). All kinds of feedback are welcome.

📄 The [docs](https://github.com/caolib/typora-onelight-theme/tree/onelight/docs) folder contains markdown files of sample articles 📄

🖼️ The [img](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/img) folder contains background images for the theme. If you don't need them, you can delete them directly.

[translated by AI]