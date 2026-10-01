# assets · 静态资源中转库

放视频、音频、图片等需要在网上直接调用的资源。公开仓库，通过固定 URL 访问。

## 目录约定

```
├── videos/    # 视频
├── audios/    # 音频
└── images/    # 图片
```

## 怎么用

传文件进来后，用这个格式的 URL 在网页 / 云端直接引用：

```
https://raw.githubusercontent.com/changrong996-droid/assets/main/<路径>
```

例如 `images/logo.png` 对应：

```
https://raw.githubusercontent.com/changrong996-droid/assets/main/images/logo.png
```

也可以用 jsDelivr 加速：

```
https://cdn.jsdelivr.net/gh/changrong996-droid/assets@main/<路径>
```

## 上传方式

直接把文件拖进 GitHub 网页端对应文件夹，或告诉 Muse（我）来传。
