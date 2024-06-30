---
home: true
heroImage: /img/logo.svg
heroText: doc-apis

tagline: 🚀傻瓜级零侵入接口文档自动生成框架
actions:
- actionText: 🚀开始使用
  actionLink: /pages/7ead0d/
- actionText: 💘爱发电
  actionLink: https://afdian.net/a/doc-apis
  actionClass: action-button-doc-apis
bannerBg: /img/back.png # auto => 网格纹背景(有bodyBgImg时无背景)，默认 | none => 无 | '大图地址' | background: 自定义背景样式       提示：如发现文本颜色不适应你的背景时可以到palette.styl修改$bannerTextColor变量
defaultMode: light
features: # 可选的
  - title: 零侵入
    details: 无需增加任何代码或注解,完全透明无感,零学习成本
  - title: 零配置
    details: 无需任何配置,引入即用,甚至无需打包进项目
  - title: 功能强大
    details: 全自动生成多端多格式接口文档,并可在线调试

# 文章列表显示方式: detailed 默认，显示详细版文章列表（包括作者、分类、标签、摘要、分页等）| simple => 显示简约版文章列表（仅标题和日期）| none 不显示文章列表

postList: none
notices: # 可选的
    - id: doc-apis
      title: 🚀 doc-apis v0.9.0 发布！
      content: '<div><ul><li>2024-06</li><li>v0.9.0</li></ul></div><p style="text-align: right;"><a href="/pages/2934a3/">查看详情</a></p>'
      isHtmlContent: true
---
<Notice :data="$frontmatter.notices"/>

<br/>

## ⛵赞助商

::: cardList
```yaml
- name: Easy-Es
  desc: 傻瓜级Elasticsearch 搜索引擎ORM框架...
  avatar: /img/sponsor/easy-es.jpg
  link: https://www.easy-es.cn/
  bgColor: '#25c37d'
  textColor: '#FFFFFF'

- name: Fast Request
  desc: IDEA版Postman, 便捷, 易用, 为简化API调试而生...
  avatar: /img/sponsor/fastRequest-logo.svg
  link: https://api-buddy.cn/
  bgColor: '#25c37d'
  textColor: '#FFFFFF'

- name: AgileBPM
  desc: 快速、简洁且强大的低代码工作流开发平台...
  avatar: /img/sponsor/agile-logo.png
  link: https://www.tongzhouyun.com/
  bgColor: '#25c37d'
  textColor: '#FFFFFF'

```
:::



<style>
  .page-wwads{
    width:100%!important;
    min-height: 0!important;
    margin: 0;
  }
  .page-wwads .wwads-img img{
    width:80px!important;
  }
  .page-wwads .wwads-poweredby{
    width: 40px;
    position: absolute;
    right: 25px;
    bottom: 3px;
  }
  .wwads-content .wwads-text, .page-wwads .wwads-text{
    height: 100%;
    padding-top: 5px;
    display: block;
  }
</style>

<style>
.become-sponsor{
  padding: 8px 20px;
  display: inline-block;
  color:  #25c37d;
  border-radius: 30px;
  box-sizing: border-box;
  border: 2px solid #25c37d;
}
</style>

<!-- AD -->


<p align="center">
  <a class="become-sponsor" href="/pages/fb599d/">成为赞助商</a>
</p>

<br/>

## 🍬优势
- **零侵入:** 不需要像Swagger等框架,需要写额外的业务代码才能生成文档,只要代码符合规范,即可自动生成接口文档
- **零配置:** Springboot最少仅需0行配置,即可自动生成接口文档,所有配置为简单而生,均有默认值,按需配置即可
- **依赖透明:** 引入后对原项目完全透明,无任何影响,甚至都不需要打包进项目,无需担心引入三方依赖带来额外风险
- **功能强大:** 生成后的文档可直接在线调试,调试所需的所有信息均有默认值,亦可手动修改,体验优于swagger及postman
- **内容丰富:** 从请求URL,到请求方式,请求入参,出参应有尽有,参数类型,是否必填,参数描述等所需全部信息一目了然
- **类型丰富**:** 可一次性生成Hmtl,MD等多种格式文档,并且同时适配WEB,IOS,Android等多种类型,适应各种需求场景
- **支持广泛:** 无论是主流的SpringBoot项目,Spring项目还是小众的Jfinal,Player等均可适配
- **多语言:** 支持生成多国语言的接口文档,并且使用文档也支持中英文双语
- **兼容性好:** 不挑食,从JDK8~JDK21均兼容,SpringBoot从1.x~3.x均可兼容,Spring,Jfinal等项目可兼容所有版本
- **使用简单:** 高端的食材仅需简单的烹饪,高端的文档生成框架也仅需简单的操作,绝大多数项目零额外学习成本,个别极端场景亦不超3分钟的学习成本即可快速上手
- **费用低廉:** 个人用户及规模小于等于10人的企业终身免费使用,中大型企业按规模阶梯收取少量费用,非盈利目的,仅为可持续发展

<br/>
<br/>

## ✨最新版本 Latest Version: [![Maven Central](https://img.shields.io/github/v/release/xpc1024/easy-es?include_prereleases&logo=xpc&style=plastic)](https://search.maven.org/search?q=g:io.github.xpc1024%20a:easy-*)

**Maven:**

```xml
<dependency>
    <groupId>com.docapis</groupId>
    <artifactId>doc-apis-starter</artifactId>
    <version>${Latest Version}</version>
</dependency>
```
**Gradle:**

```groovy
compile group: 'com.docapis', name: 'doc-apis-starter', version: 'Latest Version'
```
<br/>
<br/>

:::tip 版本稳定吗？

在版本发布前,我们针对每项功能我们都有测试用例覆盖,

单元测试用例综合覆盖率超95%,已上线的所有功能均有测试用例覆盖,且经过生产环境和开源社区大量用户使用验证,

另外我们针对整个框架的性能,安全等方面都做了理论分析+实际测试,确保每位用户用得放心,具体可查看文档顾虑粉碎模块.

我们由知名开源社区Aizuda社区孵化,并且作者也是Dromara开源社区成员,Easy-Es作者,拥有丰富的开发经验, 且本框架

具备真正零侵入的特性,无需打包进项目即可使用, 所以,请您放心引入使用！
:::

<br/>
<br/>

## 安全 
<a href="https://www.murphysec.com/dr/htY0sMYDQaDn4X8iXp" alt="OSCS Status"><img src="https://www.oscs1024.com/platform/badge/dromara/easy-es.git.svg?size=small"/></a>

我们已接入OSCS墨菲安全扫描源码中未被扫描出任何风险项，我们采用零侵入的设计理念,引入后并不会污染原项目,并且所有源码均已公开,是否有风险您一看便知。
<br/>

<a href="https://www.murphysec.com/dr/htY0sMYDQaDn4X8iXp" alt="OSCS Status"><img class="no-zoom" src="https://www.oscs1024.com/platform/badge/dromara/easy-es.git.svg?size=large"/></a>

<br/>

<br/>

## 🏡代码托管

<a href='https://gitee.com/easy-es/doc-apis' target="_blank">
    <img class="no-zoom" src="https://img.shields.io/badge/Gitee-red?logo=gitee&logoColor=white&style=for-the-badge"/>
</a>

<a href="https://github.com/xpc1024/doc-apis" target="_blank">
    <img class="no-zoom" src="https://img.shields.io/badge/Github-blue?logo=github&logoColor=white&style=for-the-badge"/>
</a>

<br/>
<br/>

## 💪🏻参与开发

欢迎各路好汉一起来参与完善 doc-apis，我们期待您的 PR！

如果您想贡献，请先查看[参与贡献](/pages/7d828w/)。

<br/>
<br/>


## 🧲友情链接
<div>
  <span style="width: 150px;flex:1;text-align: left">
      <a href="https://gitee.com" target="_blank">
          <img :src="$withBase('/img/external/gitee-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
  <span style="width: 150px;text-align: left">
      <a href="https://www.oschina.net" target="_blank">
          <img :src="$withBase('/img/external/oschina-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
  <span style="width: 150px;text-align: left">
      <a href="https://www.easy-es.cn/" target="_blank">
          <img :src="$withBase('/img/link/easy-es.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
  <span style="width: 150px;text-align: left">
      <a href="https://baomidou.com/" target="_blank">
          <img :src="$withBase('/img/external/mp.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
</div>

<br/>

<style lang="stylus">
.action-button-doc-apis
    margin-left 0.7rem
    margin-top 0.5rem
    display inline-block
    font-size 1.2rem
    background-color #68c400
    padding 0.8rem 1.6rem
    border-radius 4px
    transition background-color 0.1s ease
    box-sizing border-box
    border-bottom 1px solid #A63939
    color #000000
    &:hover
        background-color lighten(#68c400, 10%)
</style>
