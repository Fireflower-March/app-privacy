# ChatBlur 隐私政策

正式政策页面，英语为主要版本，另提供简体中文、日语、韩语和法语。生效日期及最后更新日期为 **2026-10-18**。

- 开发者：**Xuan Liu**
- 隐私联系邮箱：**liuxuan0011@qq.com**
- 产品行为：完全离线处理聊天截图，支持一键打码、照片权限、从“照片”分享到 ChatBlur，以及导出处理结果。
- 数据实践：不联网、不向开发者上传内容、不跟踪、不集成第三方数据收集 SDK。

## 页面与公开地址

| 语言 | 本地文件 | 默认 GitHub Pages 地址 |
| --- | --- | --- |
| English（默认） | [index.html](index.html) | [英文政策](https://fireflower-march.github.io/app-privacy/ChatBlur/) |
| 简体中文 | [zh-Hans.html](zh-Hans.html) | [中文政策](https://fireflower-march.github.io/app-privacy/ChatBlur/zh-Hans.html) |
| 日本語 | [ja.html](ja.html) | [日文政策](https://fireflower-march.github.io/app-privacy/ChatBlur/ja.html) |
| 한국어 | [ko.html](ko.html) | [韩文政策](https://fireflower-march.github.io/app-privacy/ChatBlur/ko.html) |
| Français | [fr.html](fr.html) | [法文政策](https://fireflower-march.github.io/app-privacy/ChatBlur/fr.html) |

上表公开地址适用于当前仓库采用默认 GitHub Pages 域名、从仓库根目录发布的配置。公开访问以 GitHub Pages 部署成功为准；使用自定义域名时，改用对应地址。

## 部署

这是可直接托管的静态 HTML，无需安装依赖或执行构建。五个页面共用本地 `styles.css`，可切换语言，支持手机、深色模式及打印。页面没有 JavaScript、远程字体、分析工具或广告。

1. 将 `ChatBlur` 目录中的全部文件提交并推送至 `main` 分支。
2. 在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，发布来源选择 **main / (root)**，保存。若仓库已有 Pages 工作流，则将本目录保留在发布产物的 `ChatBlur/` 路径下。
3. 等待部署完成，再打开上表的五个公开地址，确认页面与邮箱已更新。

部署机制见 [GitHub Pages 官方说明](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)。将 HTML 与 CSS 原样保留即可使用，也可直接部署到其他静态托管服务。

## App Store 配置

- **Privacy Policy URL**：填写部署成功后的英文政策地址；其他语言可分别填写对应本地化地址。见 [Apple 的隐私政策 URL 说明](https://developer.apple.com/help/app-store-connect/manage-app-information/manage-app-privacy)。
- **App 内入口**：在设置或关于页面提供容易找到的隐私政策入口。完全离线展示时，将五个 HTML 文件和 `styles.css` 一起打包到 App，使用本地页面。见 [App Review Guidelines 5.1.1(i)](https://developer.apple.com/app-store/review/guidelines/#privacy)。
- **App Privacy**：当实际发布版本及其扩展、集成代码均符合本政策时，选择 **No, we do not collect data from this app**，对应 **Data Not Collected**。仅在设备上处理图片不属于 Apple 隐私标签中的数据收集。见 [App privacy details](https://developer.apple.com/app-store/app-privacy-details/)。
- **照片权限**：在实际 App 工程中提供与读取截图、保存结果相符的本地化用途说明；本政策不能替代系统权限提示。见 [Apple 用途说明要求](https://developer.apple.com/help/app-review/guideline-reference/5-1-1-purpose-strings/)。

本目录交付的是可部署的政策页面。App 权限、隐私清单、实际数据处理及 App Store 审核属于 App 工程和提交环节，需要与政策保持一致。

## 维护

正文已包含开发者身份及联系方式，没有待填写字段。修改任意语言的政策时，同步其余四种语言的相关章节和日期；样式统一修改 `styles.css`。未来增加联网、诊断收集、SDK 或其他数据处理行为时，同步更新政策与 App Store 隐私披露。
