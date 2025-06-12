# AList moe
一个简洁优雅的半透明的AList美化

## 👀 预览

站点：[AList-moe Demo](https://github.com/SajunaOo/AList-moe)   
账号：demo   
密码：demo

> 请不要修改用户名和密码

## ✨ 特性

- 🌓 **兼容日/夜间模式** - 不同背景与配色
- 🪟 **毛玻璃效果** - 半透明元素 + 背景模糊
- 🎨 **精心调校的透明度** - 多层次视觉层次
- 📱 **完美响应式** - 适配所有设备屏幕

## 🖼️ 截图 

![PC首页](https://s21.ax1x.com/2025/06/08/pViOJeI.png)
![PC首页本地设置](https://s21.ax1x.com/2025/06/08/pViO3yd.png)
![PC登录页](https://s21.ax1x.com/2025/06/08/pViO8OA.png)

<p align="center">
  <img src="https://s21.ax1x.com/2025/06/08/pViOlSe.png" alt="移动端本地设置" width="45%"/>
  <img src="https://s21.ax1x.com/2025/06/08/pViO1QH.png" alt="移动端登录页" width="45%"/>
</p>

## 🚀 使用  

### 自定义头部
```
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@500&display=swap" rel="stylesheet">
<link href="https://gcore.jsdelivr.net/gh/SajunaOo/AList-moe/css/AList.min.css" rel="stylesheet">
<style>
/** 更改url以更改背景图，删除本css或留空url将调用默认背景图 */
:root {
  --mio-theme-color: 248, 179, 78; /* 该主题色用于修复视图切换按钮背景色 */
  --mio-bg-image: url("https://gcore.jsdelivr.net/gh/SajunaOo/AList-moe/img/background_light.webp"); /* 白天模式背景图 */
}

.hope-ui-dark {
  --mio-bg-image: url("https://gcore.jsdelivr.net/gh/SajunaOo/AList-moe/img/background_dark.webp"); /* 夜间模式背景图 */
}
</style>
```

### 自定义内容

```
<script src="https://gcore.jsdelivr.net/gh/SajunaOo/AList-moe/js/AList.min.js"></script>
```
## 🙏 致谢

[AList](https://github.com/alist-org/alist)  
[安稳](https://anwen-anyi.github.io)   
[kasuie](https://github.com/kasuie/alist-customize)

## 💔 最后

6月11日在知道 **“贵公司”** 收购了AList之后，我心里是五味杂陈的，我为AList有一个稳定维护者而开心，又因为是“贵公司”的收购而难过

AList在被收购后也没有**向社区公布**，令人疑惑的**pr提交**，开发者的沉默，文档内容的**大换血**，贵公司的**光明历史**...最后以至于issue被使用者和贡献者泄愤的言论埋没

在xhofe角度上我理解他，从19年到现在，这个项目几乎由他一人维护，在这个过程中也并没有产生什么收益

....  

不知道在 **“贵公司”** 手中的的AList，路还能走多远？