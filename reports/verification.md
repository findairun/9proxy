# 验收记录

项目：9proxy-affiliate-site

## 已完成
- 创建项目目录：`/home/ubuntu/.hermes/projects/9proxy-affiliate-site`
- 创建首页：`public/index.html`
- 支持浏览器语言自动识别（zh -> 中文，其他 -> 英文）
- 支持顶部手动语言切换
- 已写入邀请码、注册链接、5% 持续折扣、周日 10% 返还活动信息
- 已本地启动静态服务并用浏览器验收中英文内容切换

## 验收结果
- 本地访问成功：`http://127.0.0.1:8765/`
- 英文默认文案正常显示
- 点击“中文”后页面切换正常
- CTA 链接指向：`https://9proxy.com/sign-up?inviteCode=9P_YYaAHEsN`

## 当前上线方式
这是一个纯静态页面，可直接部署到：
- Cloudflare Pages
- Vercel
- Netlify
- 任意 Nginx 静态站点目录

## 注意
- 尚未接入真实统计脚本
- 尚未做 robots.txt / sitemap.xml / 域名绑定 / CDN 配置
- 当前页面可上线，但若要做 SEO 正式投放，建议补充这些基础资产
