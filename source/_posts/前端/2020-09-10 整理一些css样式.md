---
title: 整理一些css样式
date: 2020-09-10 16:54:31
tags: ['前端', 'css']
categories: 前端
id: several-css-style
reward: true
---

# 整理一些css样式

### 渐变文字

```css
background: linear-gradient(360deg, #97E9FF 0%, #FFFFFF 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
```

### 文字阴影

```css
text-shadow: 0 0 12px rgba(24, 230, 255, 0.63);
```

### 适应多种情况的自动换行

```css
word-break: keep-all;
word-wrap: break-word;
white-space: pre-wrap;
```

### 小天才的margin呢

```css
.iconfont + .iconfont {
    margin-left: 10px;
}
/* 任意两个连续的 `iconfont` 类中后面一个添加 `margin-left` 属性 */
```

