<h1 align='center'>OneLight Theme For Typora</h1>

<p align="center">
    Simplified Chinese
    |
    <a href="https://github.com/caolib/typora-onelight-theme/blob/onelight/docs/README_en.md">English</a>
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
> **Below are two articles using the OneLight theme. Click to view detailed effect demos:**
>
> 1. **[OneLight](https://bin-sites.pages.dev/onelight)**、**[OneLight-Dark](https://bin-sites.pages.dev/onelight/dark)**
> 2. **[Computer Networks](https://bin-sites.pages.dev/net)**

---

![Preview Image](https://s2.loli.net/2025/05/31/Bzxh8GMVeXnYHPb.png)

![Preview Image](https://s2.loli.net/2025/05/31/lN4ZW7GFVAKdw3u.png)

![Preview Image](https://s2.loli.net/2025/06/24/shrmC7xiy9tKQH1.png)

![Preview Image](https://s2.loli.net/2025/06/24/ZVsQ1O3FSRpbJgE.png)

![Preview Image](https://s2.loli.net/2025/05/11/mUofcTY1qNb5OX9.png)

![Preview Image](https://s2.loli.net/2025/05/11/ULwkB9dnPiTEpaM.png)

<details><summary><kbd>Expand for more screenshots</kbd></summary>
  <img src="https://s2.loli.net/2025/05/11/23GUxWvkhDE4doF.png"></br>
  <img src="https://s2.loli.net/2025/05/11/JUrxQsdYvVg6OZe.png"></br>
  <img src="https://s2.loli.net/2025/05/11/aZsAW1kXDBqM2hV.png"></br>
  <img src="https://s2.loli.net/2025/05/11/x35yzoV2GC4vXIU.png"></br>
  <img src="https://s2.loli.net/2025/05/11/PrlOStnM3J4Tehz.png"></br>
  <img src="https://s2.loli.net/2025/05/11/4l1rUvLfhHQCc2g.png"></br>
</details>

---

## 2. How to Use

Choose one of the following methods:

### 2.1 Download Files

> 1. Download the [theme zip file](https://github.com/caolib/typora-onelight-theme/releases)
> 2. In Typora: File → Preferences → Appearance → Open Theme Folder
> 3. Unzip the downloaded file, then copy the **CSS files** and **folder** into Typora's themes directory
> 4. Restart Typora and switch themes via the menu bar
>
> *Pros: Smaller download size.  
> Cons: Manual updates require re-downloading.*

### 2.2 Clone Repository

> [!caution]
>
> 1. Navigate to Typora's themes folder and open a terminal
> 2. **Use this command to avoid unnecessary files from other branches:**
>
>    ```shell
>    git clone --single-branch https://github.com/caolib/typora-onelight-theme.git
>    ```
>
> *Pros: Easy updates via `git pull`.  
> Cons: Downloads entire project including non-essential files.*

---

## 3. Customization

### 3.1 Folder Structure

📂 themes                              
├── 📂 onelight                        
│   ├── 📂 fonts                       
│   │   ├── CascadiaCode.woff2        
│   │   └── MiaoZi-GuoZhiTi.woff2     
│   ├── 📂 img                         
│   │   ├── bg.gif                     
│   │   ├── ...                        
│   └── 📂 style                       
│       ├── blockquote.css             
│       ├── code.css                   
│       ├── editor.css                 
│       └── ...
├── onelight-dark.css                  
├── onelight.css                       
├── onelight.user.css                  
└── onelight-dark.user.css             


### 3.2 Custom Configuration

Place custom styles in `onelight.user.css` (or `onelight-dark.user.css` for dark mode) instead of modifying `onelight.css` directly. This file has higher priority.  
Add `!important` if styles don't apply.

### 3.3 Style Options

> [!important]
>
> **How to switch styles?**  
> Edit `onelight.css` (light) / `onelight-dark.css` (dark), then toggle imports:
>
> ```css
> /* Blockquote styles: original | default */
> /* @import './onelight/style/blockquote/blockquote.css'; */
> @import './onelight/style/blockquote/blockquote2.css';
> ```
>
> Example (switch to original blockquote style):
> ```css
> @import './onelight/style/blockquote/blockquote.css';
> /* @import './onelight/style/blockquote/blockquote2.css'; */
> ```

#### 3.3.1 Headers

<div align="center">
  <table>
    <tr>
      <th>Default</th>
      <th>Colorful</th>
      <th>Starry Sky</th>
    </tr>
    <tr>
      <td><img src="https://s2.loli.net/2025/06/24/9YwPCWLauKxq6E7.png"/></td>
      <td><img src="https://pic1.imgdb.cn/item/68621c9058cb8da5c87ebcae.gif"/></td>
    </tr>
    <tr>
	    <td><img src="https://s2.loli.net/2025/06/24/Bao4lWrA7q23L1F.png"/></td>
      <td><img src="https://pic1.imgdb.cn/item/68621c9658cb8da5c87ebcb3.gif"/></td>
    </tr>
  </table>
</div>

#### 3.3.2 Lists

> [!warning]
> Default style may cause [alignment](https://github.com/caolib/typora-onelight-theme/issues/32) or [numbering](https://github.com/caolib/typora-onelight-theme/issues/28) issues.

<div align="center">
  <table>
    <tr>
      <th>Default</th>
      <th>Simplified</th>
    </tr>
    <tr>
      <td><img src="https://s2.loli.net/2025/06/24/ofGeAEH1acyK8WB.png"/></td>
      <td><img src="https://s2.loli.net/2025/06/24/rNpkRxn6PJ4SfWe.png"/></td>
    </tr>
    <tr>
	    <td><img src="https://s2.loli.net/2025/06/24/ZaflTqwb8tFo6OV.png"/></td>
      <td><img src="https://s2.loli.net/2025/06/24/MuYtWmLU1rXoHwk.png"/></td>
    </tr>
  </table>
</div>

#### 3.3.3 Callouts

<div align="center">
  <table>
    <tr>
      <th>Default</th>
      <th>Original</th>
    </tr>
    <tr>
      <td><img src="https://s2.loli.net/2025/06/24/a98iYcERykNHQfv.png"/></td>
      <td><img src="https://s2.loli.net/2025/06/24/RNgQLvaqszKUVn4.png"/></td>
    </tr>
    <tr>
	    <td><img src="https://s2.loli.net/2025/06/24/FpqluvZdcAH71my.png"/></td>
      <td><img src="https://s2.loli.net/2025/06/24/v26zKmDYxMNyUfr.png"/></td>
    </tr>
  </table>
</div>
#### 3.2.4 background

Dynamic starry background For the dark theme, at the top of `onelight-dark.user.css`,add:
```css
@import './onelight/style/background/grok.css';
@import './onelight/style/background/grok-gpu.css';
```

<div align="center">
  <table>
    <tr>
      <th>Default</th>
      <th>Dynamic starry background</th>
    </tr>
    <tr>
      <td><img src="https://s2.loli.net/2025/06/28/4hVHnSvQeaMCs2b.png"/></td>
      <td><img src="https://pic1.imgdb.cn/item/68621f3158cb8da5c87ec9f2.gif"/></td>
    </tr>
  </table>
</div>

## 4. Fonts

Font settings are in `root{}` of `onelight.css`. Import fonts via `font.css`.
![](https://s2.loli.net/2025/05/31/xO8RQSmHkWTuhXz.png)

---

## 5. Background Images

> [!important]
>
> 1. Find background images in `onelight/img`
> 2. Replace `bg.gif` in `editor.css`:
> ```css
> content {
>     background-image: url('../img/YOUR_IMAGE.gif');
> }
> ```
> <img src="https://s2.loli.net/2025/03/05/7Ds8SCmvWnkwraM.png" style="zoom: 50%;" />

---

## 6. Additional Notes

<img align='right' src="https://s2.loli.net/2025/01/04/zt7O3daMLDC5EHW.png" alt="like" />⭐ If you like this theme, please give it a star! 🙏  

✅ Best viewed in Focus Mode (Distraction Free) ✨  

❓ Questions? Open an [Issue](https://github.com/caolib/typora-onelight-theme/issues)  

📄 Sample documents in [docs](https://github.com/caolib/typora-onelight-theme/tree/onelight/docs) folder  

🖼️ Theme backgrounds in [img](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/img) folder (delete if unused)