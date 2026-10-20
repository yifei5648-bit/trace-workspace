# TRACE
AI Creative Research Workspace

## 文件
- index.html：可交互的 TRACE 原型，含完整五步研究流程。
- portfolio.html：固定四页作品集介绍，包含原型入口。

两份 HTML 均已内嵌图片、样式与脚本，无需安装、构建或额外 assets 文件夹。字体采用本机系统字体。

## 放入已有网站
将整个 trace-website 文件夹放入网站公开目录，例如 public/trace-website/。
- 原型入口：/trace-website/index.html
- 作品集入口：/trace-website/portfolio.html
两页通过相对链接互相跳转。网站首页可添加“TRACE”链接到其中一页。

如果使用 Next.js、Vite 等网站，将本文件夹放在 public 下，以普通链接访问这些静态 HTML，不要直接把完整 HTML 粘入组件。
若新网站的编辑器不接受 HTML 文件上传，需要使用该平台提供的静态托管或外部页面入口。

## 作为独立网站
将文件夹内容放入静态网站的发布目录，index.html 会作为首页。
尚未自动部署到任何网站；无需放入密钥。

## 打开与使用
本地双击 index.html 或 portfolio.html。
研究流程：INPUT → CONNECTIONS → DIRECTIONS → HUMAN CHOICE → DEVELOP。
设计师主动选择方向；Brief 五项可编辑并导出 Markdown。
上传图片与研究草稿仅在当前页面保存，刷新后清除。默认 10 张图片已嵌入，刷新后仍存在。

## 作品集说明
项目定位：AI Creative Research Workspace。
当前为可交互概念原型；默认研究内容由人工策划，未接入实时 AI。
自定义图片模式只提供观察练习和通用方向模板，不识别图片内容。
参考图由用户提供，原作作者与名称尚待补充；公开发布前补齐来源和使用授权。

## 维护
本文件夹是迁移用发布文件，不是完整源代码副本。
可维护源代码仍在原项目目录：script.js、styles.css、assets、build.mjs。
修改源代码后运行 node build.mjs，再将更新后的 index.html、portfolio.html复制到本文件夹。

## 验证范围
已确认两份 HTML 与当前项目完全一致，默认图像内嵌且页面间链接完整。
原项目流程逻辑检查已通过。本次未在新网站环境验证浏览器布局、下载或平台安全策略。
