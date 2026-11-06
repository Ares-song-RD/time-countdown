# 时间倒计时 (time-countdown)

一个单文件、零依赖的网页倒计时页面。直接用浏览器打开 `index.html` 即可使用，也可以部署到任意静态托管（GitHub Pages / Vercel / 本地 nginx）。

## 使用

```bash
# 方式一：直接打开
open index.html

# 方式二：本地起个静态服务
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 文件说明

| 文件 | 说明 |
| --- | --- |
| `index.html` | 主页面（单文件，HTML + CSS + JS 全部内联） |
| `时间倒计时.html` | 同一页面的中文文件名副本，方便本地双击打开 |

## 部署到 GitHub Pages

在仓库 **Settings → Pages** 中选择 `main` 分支的 `/ (root)` 目录即可，页面地址形如：

```
https://ares-song-rd.github.io/time-countdown/
```
