# 音乐欣赏复习

这是一个由课程测试 PPT 生成的静态复习网页，用于手机和电脑浏览器自测。

在线访问：

https://loaf1ng.github.io/music-review-html/

## 内容

- 共 55 道题。
- 题面以幻灯片截图展示，保留原 PPT 版式。
- 音频与视频已转换为 iOS Safari 更兼容的格式。
- 答案来自 PPT 备注区，点击后显示答案并在题面上标出绿色勾。
- 支持关键词搜索。
- 页面带有简单口令入口和 `noindex` 标记。

## 版本

当前版本：`v1.1.0`

## 维护说明

源 PPT 不放入本仓库。本仓库只发布生成后的静态网页和媒体资源。

重新生成网页时，在本地工作空间运行：

```powershell
python .\generate_music_review.py
python .\make_media_ios_compatible.py
```

然后检查 `music_review_html/` 中的结果并推送。
