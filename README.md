# Ekiben_TD Image Warehouse

用于 **Minecraft Slideshow 模组** 的公开图片仓库。图片上传到本仓库的 `images/` 文件夹后，可通过 HTTPS 直链在游戏中加载。

## 立即测试

仓库内现有测试图片：

- GitHub 图片页面：[images/airport03.jpg](https://github.com/Sarutofish/Ekiben_TD-Image-Warehouse/blob/main/images/airport03.jpg)
- Slideshow 可用直链：

```text
https://raw.githubusercontent.com/Sarutofish/Ekiben_TD-Image-Warehouse/main/images/airport03.jpg
```

## 上传图片

1. 打开仓库中的 [images 文件夹](https://github.com/Sarutofish/Ekiben_TD-Image-Warehouse/tree/main/images)。
2. 点击右上方 **Add file → Upload files**。
3. 选择图片，等待上传完成。
4. 在页面下方点击 **Commit changes**。
5. 等待约几十秒，再按下方规则生成图片直链。

> 本仓库是公开仓库。上传的图片和提交记录均可被任何人查看，请勿上传含个人隐私、账号凭据或其他敏感信息的文件。

## 生成图片直链

固定格式：

```text
https://raw.githubusercontent.com/Sarutofish/Ekiben_TD-Image-Warehouse/main/images/文件名.扩展名
```

例如，上传 `station-sign-01.png` 后，直链是：

```text
https://raw.githubusercontent.com/Sarutofish/Ekiben_TD-Image-Warehouse/main/images/station-sign-01.png
```

也可以打开 GitHub 上的图片文件，点击 **Raw**，再复制浏览器地址栏中的网址。

### 不要复制这种地址

```text
https://github.com/Sarutofish/Ekiben_TD-Image-Warehouse/blob/main/images/airport03.jpg
```

带有 `/blob/main/` 的地址是 GitHub 图片预览网页，不是供 Slideshow 直接读取的图片直链。

## 导入 Slideshow

1. 在 Slideshow 的图片或幻灯片设置界面中选择在线图片（URL）。
2. 粘贴上述 `raw.githubusercontent.com` 直链。
3. 保存设置并等待图片下载。
4. 若游戏内未立即显示，请重新打开该幻灯片或重新进入世界。

PNG、JPG/JPEG 和 GIF 适合作为仓库图片。为减少玩家加载时间，建议单张图片尽量控制在 4 MB 以内，并按展示区域的比例提前裁剪。

## 文件命名规范

推荐只使用：

- 小写英文字母：`a-z`
- 数字：`0-9`
- 连字符：`-`
- 下划线：`_`

推荐示例：

```text
airport-terminal-01.jpg
metro-map-line1.png
ad_screen_20260811.gif
```

尽量不要使用中文、空格、`#`、`?`、`%` 等字符，以免复制直链时出现编码问题。文件名区分大小写。

## 替换和删除图片

- 更新图片时，推荐上传新文件名，例如把 `poster-v1.png` 改为 `poster-v2.png`，然后在 Slideshow 中换成新直链。
- 直接覆盖同名文件可能受到客户端或网络缓存影响，游戏里不会立刻刷新。
- 删除或重命名图片会让旧直链失效；在操作前先确认 Minecraft 场景中是否仍在使用。

## 常见问题

### 浏览器能打开，游戏里加载失败

依次检查：

1. 链接是否以 `https://raw.githubusercontent.com/` 开头。
2. 链接中是否错误地包含 `/blob/main/`。
3. 文件名、大小写和扩展名是否完全一致。
4. 仓库是否仍为 **Public**。
5. 当前网络是否能访问 `raw.githubusercontent.com`。
6. 图片是否过大或格式异常。

### 上传后出现 404

GitHub 的新提交可能需要短暂同步。等待几十秒后刷新；若仍然 404，重点检查路径和文件名大小写。

---

仓库主页：<https://github.com/Sarutofish/Ekiben_TD-Image-Warehouse>
