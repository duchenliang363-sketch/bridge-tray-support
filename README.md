# 桥架下料助手支持站

静态站点，用于 App Store 隐私政策和技术支持页。不要把 iOS 源码放到这个站点仓库。

## 本地预览

```bash
python3 -m http.server 8000 --directory release/support-site
```

打开：

- http://127.0.0.1:8000/
- http://127.0.0.1:8000/privacy.html
- http://127.0.0.1:8000/support.html

## 发布

1. 用已登录的 GitHub 账号新建**公开**仓库 `bridge-tray-support`。
2. 只上传本目录内容，不要上传 App 工程。
3. GitHub Pages 选择默认分支根目录。
4. 不要占用 001 已使用的 `app.maomaoxingqiu.xin` CNAME。可先用 GitHub Pages 默认地址。
5. 启用 HTTPS 后确认：

- https://duchenliang363-sketch.github.io/bridge-tray-support/privacy.html
- https://duchenliang363-sketch.github.io/bridge-tray-support/support.html
