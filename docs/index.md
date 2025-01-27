---
layout: home
layoutClass: 'm-home-layout'

hero:
  name: 数字化文档
  text: 助力 Flex 的转型之路
  tagline: 知识是进步的阶梯, 开辟视野全新领域
  image:
    src: /logo.png
    alt: 数字化文档
  actions:
    - text: 导航首页
      link: /nav
    - text: 前端物语
      link: /fe/es6/
      theme: alt
    - text: 日常笔记
      link: /daily-notes/
    - text: EMCT
      link: http://shznt803.asia.ad.flextronics.com:38080/#/login
      theme: alt
features:
  - icon: 📖
    title: 前端物语
    details: 整理前端常用知识点<small>(八股文)</small><br />深入对前端的理解, 学以致用
    link: /fe/javascript/types
    linkText: 前端常用知识
  - icon: 📘
    title: 源码阅读
    details: 了解各种库的实现原理<br />学习其中的小技巧和冷知识
    link: /analysis/utils/only-allow
    linkText: 源码阅读
  - icon: 💡
    title: Workflow
    details: 在日常工作中学到的一切<small>（常用库/工具/高效技巧等）</small><br />配合 CV 大法来更好的摸鱼
    link: /workflow/utils/library
    linkText: 常用工具库
  - icon: 🧰
    title: 提效工具
    details: 工欲善其事，必先利其器<br />记录开发和日常使用中所用到的软件、插件、扩展等
    link: /efficiency/online-tools
    linkText: 提效工具
  - icon: 🐞
    title: 踩坑记录
    details: 那些年我们踩过的坑<br />总有一些让我们意想不到的问题
    link: /pit/npm
    linkText: 踩坑记录
  - icon: 💯
    title: 始终朝着正确的方向前进。
    details: '<small class="bottom-small">Dev Team</small>'
    link: /dev_team
---

<script setup>
import MFriends from './home/MFriends.vue'
</script>

<ClientOnly>
  <MFriends/>
</ClientOnly>

::: details 申请快捷链接

**快捷链接要求**:

- 网站应合规且对工作生活有积极作用
- 网站需要有良好的稳定性和高可靠性

**申请方式**:

1. 在本页面留言
2. 直接邮箱联系 [开发团队成员: egon.li@flex.com] 沟通您的申请

**本站信息**：

- 网站名称: **数字化文档**
- 网站描述: **助力Flex的转型之路，包含前端常用知识、源码阅读笔记、各种高效技巧、日常提效工具等**
- 网站地址：**<http://shznt803.asia.ad.flextronics.com:38082>**
- 网站图标：**<http://shznt803.asia.ad.flextronics.com:38082/logo.png>**

```json
{
  "title": "数字化文档",
  "desc": "助力Flex的转型之路，包含前端常用知识、源码阅读笔记、各种高效技巧、日常提效工具等",
  "link": "http://shznt803.asia.ad.flextronics.com:38082",
  "icon": "http://shznt803.asia.ad.flextronics.com:38082/logo.png"
}
```

:::

<style>
/*爱的魔力转圈圈*/
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .item:last-child .details {
  display: flex;
  justify-content: flex-end;
  align-items: flex-end;
}
</style>
