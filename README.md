## 使用教程

### 现有配置功能
- 部分路由配置 ✅
- 默认中文 ✅
- 自动昼夜模式 ✅
- 右下角小工具（可手动设置开启阅读模式、昼夜模式、繁简切换及回到顶部） ✅
- 代码块高亮（支持复制，并且携带作者授权信息，超出隐藏，展开收起，代码块溢出自动换行） ✅
- 标签/分类随机颜色 ✅
- 显示文章封面 ✅
- 文章锚点地址栏跟踪（滚动时浏览器地址栏自动更新当前锚点#） ✅
- 文章打赏 ✅
- 文章阅读/浏览量统计 ✅
- 本地文章搜索 ✅
- 相关文章展示 ✅
- 文章分享（facebook,twitter,wechat,weibo,qq） ✅
- 网站分析 ✅
- 鼠标左键动画 ✅
- 网站进入loading效果 ✅
- 网站内容背景特效 ✅
- 美化网页提示 ✅
- 主页子标题打字效果 ✅
- 网页加载动画 ✅
- 网站字数统计 ✅
- 图片放大器 ✅
- fancybox 画廊 ✅
- 网站资源预加载 ✅
- 中英文自动缩进空格 ✅
- 图片懒加载 ✅
- 网页爬虫 ✅
- `Vercel`站点分析 ✅

> 主题很强大，还有更多的功能可以提供使用者自行开启使用
### 下载代码
```shell
git clone https://github.com/hiiiiiiixiaohui/fast-hexo-butterfly-template.git
```
### 命令使用
- 安装npm包
```shell
yarn install
```
- 检查`_config.yml`和`_config.butterfly.yml`配置文件，根据自己网站情况修改相关内容（大概字段）
- `_config.yml`
    - `title`：网站标题
    - `subtitle`：网站子标题
    - `description`：网站描述
    - `author`：作者
    - `url`：你部署代码后的个人域名

- `_config.butterfly.yml`
    - `favicon`：网站浏览器小图标
    - `avatar`：作者信息
    - `index_img`（可选）：网站首页背景
    - `default_top_img`（可选）：当部分页面没设置背景时所用的默认背景
    - `QR_code`：文章打赏二维码
    - `footer`：网站底部信息
    - `aside`：网站侧边栏内容
    - `clickShowText`：鼠标左键特效
    - `subtitle`：主页子标题打字效果

- 运行项目
```shell
# 同等于hexo server
hexo s
```
- 构建资源
```shell
hexo build
```
- 清理缓存
```shell
hexo clean
```
- 查看路由列表
```shell
hexo list route
```
- 更多指令自己可以查看帮助瞎捣鼓了解了解
```shell
hexo --help
```
### 如何上线
> 参考[官方文档-一键部署](https://hexo.io/zh-cn/docs/one-command-deployment)
- 个人使用的是`Vercel`，傻瓜式部署，连接github自动CI/CD部署。

### 致谢
> 感谢主题作者`jerryc127`大佬贡献，这是他的[主题教程](https://butterfly.js.org/posts/21cfbf15/)，及[github](https://github.com/jerryc127)

> hexo 相关内容参考[官网](https://hexo.io/zh-cn/docs/)

> 如果你用得上且有一定帮助，可以的话麻烦给个star啦