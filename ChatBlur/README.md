# ChatBlur 隐私政策

英语为主要版本，附简体中文、日语、韩语、法语。所有文件均位于本目录。生效日期及最后更新日期为 **2026-10-18**。

| 语言 | 文件 |
| --- | --- |
| English（默认） | [index.html](index.html) |
| 简体中文 | [zh-Hans.html](zh-Hans.html) |
| 日本語 | [ja.html](ja.html) |
| 한국어 | [ko.html](ko.html) |
| Français | [fr.html](fr.html) |

各页面可切换语言，支持手机、深色模式和打印。共用本地 `styles.css`，无 JavaScript、远程字体、分析工具或广告，无构建依赖。

## 内容依据

正文依据已确认的产品行为编写：ChatBlur 是完全离线、不联网、不集成第三方数据收集 SDK 的聊天截图一键打码工具，会申请照片权限，支持导出处理结果，以及从“照片”通过分享菜单将图片导入 ChatBlur。此仓库没有 App 源码，因此未对二进制、权限、持久化或依赖进行审计。

正文涵盖本地处理、不收集数据、不跟踪、不共享、照片权限管理、本地保留与删除、系统备份、主动导出和分享、儿童隐私、政策更新及联系渠道。第 3、5 节已明确导入聊天截图、本地打码、从“照片”分享到 ChatBlur，以及导出结果的流程。正文没有承诺未核实的缓存自动清理或加密机制。

已确认公开的隐私联系邮箱为 **1275966245@qq.com**，五种语言第 10 节均提供可点击的邮件链接。该邮箱无需与 Apple 账号登录邮箱相同，只需确实可联系开发者并持续处理隐私请求。

五种语言第 1 节已按用户提供的账户截图填写开发者姓名 **Xuan Liu**。截图展示的是账户名称，尚未展示会员登记信息；正式发布前请核对会员登记姓名或 App Store 销售商姓名的拼写，如有差异，同步更新五种语言第 1 节。若适用地区对经营者身份、地址或联系方式有额外要求，也需填写实际信息。

个人会员的销售商是注册时登记的法定姓名，组织会员则是相应法律实体名称，参见 [Apple 注册说明](https://developer.apple.com/help/account/membership/program-enrollment/)。已上架 App 可在 App Store 产品页底部“信息”中核对“供应商／销售商”；尚未上架时，可登录 [Apple Developer 账号](https://developer.apple.com/account/)，查看 Membership details（会员资格详细信息）中的登记姓名或法律实体名称。账号菜单中的显示姓名不一定与会员登记姓名一致，参见 [Apple 账号信息说明](https://developer.apple.com/help/account/membership/updating-your-account-information/)。

## GitHub Pages 托管

1. 将本目录提交并推送到仓库。
2. 在仓库 Settings → Pages 中配置从 `main` 分支的根目录 `/` 发布，或使用仓库已有的 Pages 工作流。
3. 部署完成后，打开实际网址，确认返回政策正文，且不要求登录。

根据当前仓库 remote，如果采用默认 GitHub Pages 域名且没有自定义域名，预期网址如下。**这些是部署后的预期地址，尚未部署或验证可访问性。**

| 语言 | 预期公开 URL |
| --- | --- |
| English | https://fireflower-march.github.io/app-privacy/ChatBlur/ |
| 简体中文 | https://fireflower-march.github.io/app-privacy/ChatBlur/zh-Hans.html |
| 日本語 | https://fireflower-march.github.io/app-privacy/ChatBlur/ja.html |
| 한국어 | https://fireflower-march.github.io/app-privacy/ChatBlur/ko.html |
| Français | https://fireflower-march.github.io/app-privacy/ChatBlur/fr.html |

## iOS 提交时的对应设置

- 将部署后可公开访问的英文地址填入 App Store Connect 的 Privacy Policy URL；可为各本地化分别填写对应语言的地址。Apple 要求所有 App 提供隐私政策 URL，参见 [Manage app privacy](https://developer.apple.com/help/app-store-connect/manage-app-information/manage-app-privacy)。
- 在 App 内提供容易找到的政策入口。考虑到 App 完全离线，可将对应语言的 HTML 和 CSS 随 App 打包后本地展示，在线页面用于 App Store 的政策 URL。Apple 对政策内容和入口的要求见 [App Review Guidelines 5.1.1(i)](https://developer.apple.com/app-store/review/guidelines/#privacy)。
- 如果发布版本与本政策一致，开发者及集成代码均不收集数据，可在 App Privacy 问卷选择 **“No, we do not collect data from this app”**，对应 **Data Not Collected**。Apple 将仅在设备内处理的数据与向设备外传输的数据区分，参见 [App privacy details](https://developer.apple.com/app-store/app-privacy-details/)。若通过 Apple 诊断渠道实际获取 App 数据，或未来加入联网、SDK、支持表单等行为，需重新核对披露。
- 如果实际访问照片等受保护资源，需在 App 工程中配置真实、具体且已本地化的用途说明；仅有本政策不能替代系统权限说明。参见 [Apple 的用途说明要求](https://developer.apple.com/help/app-review/guideline-reference/5-1-1-purpose-strings/)。
- 本目录只提供政策文档，不会配置 App 的权限、隐私清单、备份排除规则或 App Store Connect。发布时应核对实际实现；政策文档本身不保证审核通过。

## 后续维护

直接编辑五个 HTML 文件中的正文，保持十个章节的内容和更新日期一致。共享样式只修改 `styles.css`。产品新增数据处理行为时，先同步政策、相关权限及 App Store 隐私披露，再发布相应版本。
