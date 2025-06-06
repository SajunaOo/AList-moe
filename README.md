# AList moe
一个简单的AList美化

## 🖼️ 截图 
![首页](https://s21.ax1x.com/2025/06/06/pViQwi6.png)
![登录页](https://s21.ax1x.com/2025/06/06/pViQaIx.png)
![移动端首页](https://s21.ax1x.com/2025/06/06/pViQsQe.png)

## 🚀 使用  
### 自定义头部
```
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@500&display=swap" rel="stylesheet">
<link href="https://gcore.jsdelivr.net/gh/SajunaOo/AList-moe/css/AList.min.css" rel="stylesheet">
<style>
/** 更改url以更改背景图，删除本css或留空url将调用默认背景图 */
:root {
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
[安稳](https://anwen-anyi.github.io)
[kasuie](https://github.com/kasuie/alist-customize)