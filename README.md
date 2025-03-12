# Frontend Mentor - Meet landing page solution

## Table of contents 目錄

- [Overview 概述](#overview-概述)
  - [The challenge 挑戰目標](#the-challenge-挑戰目標)
  - [Screenshot 截圖](#screenshot-截圖)
  - [Links 相關連結](#links-相關連結)
- [My process 我的過程](#my-process-我的過程)
  - [Built with 使用技術](#built-with-使用技術)
  - [What I learned 學到的事](#what-i-learned-學到的事)
  - [Continued development 持續發展](#continued-development-持續發展)
- [Author 作者](#author-作者)

## Overview 概述

### The challenge 挑戰目標

Users should be able to:
使用者應該能夠：

- View the optimal layout depending on their device's screen size
  - 根據裝置螢幕大小查看最佳佈局
- See hover states for interactive elements
  - 查看互動元素的懸停狀態

### Screenshot 截圖

![](/Screenshot.jpg)

### Links 相關連結

- Solution URL: [GitHub Repository](https://github.com/ylin320/Meet-landing-page)
- Live Site URL: [GitHub Pages](https://ylin320.github.io/Meet-landing-page/)

## My process 我的過程

### Built with 使用技術

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS Background Images

### What I learned 學到的事

在這個專案中，我主要學習到了關於 CSS background-image 的應用和其挑戰：

#### Background Image vs. IMG Tag 背景圖片與圖片標籤的比較:

```css
.hero-image {
  background-image: url(./assets/desktop/image-hero-left.png);
  background-size: cover;
  background-position: top;
  background-repeat: no-repeat;
}
```

I initially explored ways to optimize image loading performance using only HTML and CSS, particularly focusing on loading different image sizes for different screen resolutions. While investigating this, I discovered that pure HTML/CSS solutions have limitations. I chose to use background-image because it allowed me to split one image into two parts for the desktop version, which provided more flexibility for positioning and manipulation.

我一開始研究如何只用 HTML 和 CSS 來優化圖片載入效能，特別是在不同螢幕解析度下載入不同尺寸的圖片。在研究過程中發現純 HTML/CSS 的解決方案有其限制。最後選擇使用 background-image 是因為它允許我在桌面版本中將一張圖片分成兩部分，這樣在定位和操作上提供了更多的彈性。

#### 主要挑戰 Main Challenges:

The most time-consuming aspect was adjusting the images across different viewport sizes. Background images proved to be more challenging to control compared to regular img tags, especially when it came to:

- Positioning the images correctly
- Maintaining proper sizing across different screen sizes
- Handling the transition between mobile, tablet, and desktop layouts

最耗時的部分是調整不同視口大小下的圖片。相較於一般的 img 標籤，背景圖片的控制更具挑戰性，特別是在：

- 正確定位圖片
- 在不同螢幕尺寸下維持適當的大小
- 處理手機、平板和桌面版面配置之間的轉換

### Continued development 持續發展

For future projects, I would like to:

- Explore more efficient ways to handle responsive images
- Learn more about modern image optimization techniques
- Investigate JavaScript solutions for better image loading control

在未來的項目中，我想要：

- 探索更有效率的響應式圖片處理方式
- 學習更多現代圖片優化技術
- 研究使用 JavaScript 來更好地控制圖片載入

## Author 作者

- GitHub - [@ylin320](https://github.com/ylin320)
- Frontend Mentor - [@ylin320](https://www.frontendmentor.io/profile/ylin320)
