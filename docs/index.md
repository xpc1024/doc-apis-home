---
home: true
heroImage: /img/logo.svg
heroText: doc-apis

tagline: 🚀傻瓜级零侵入接口文档自动生成框架
actions:
- actionText: 🚀开始使用
  actionLink: /pages/7ead0d/
  actionClass: action-button-doc-apis
bannerBg: /img/back.png # auto => 网格纹背景(有bodyBgImg时无背景)，默认 | none => 无 | '大图地址' | background: 自定义背景样式       提示：如发现文本颜色不适应你的背景时可以到palette.styl修改$bannerTextColor变量
defaultMode: light
features: # 可选的
  - title: 零侵入
    details: 无需增加任何代码或注解,完全透明无感,甚至无需打包进项目
  - title: 零配置
    details: 无需任何配置,开箱即用,零学习成本
  - title: 功能强大
    details: 全自动生成多端多格式多语种接口文档,并可在线调试

# 文章列表显示方式: detailed 默认，显示详细版文章列表（包括作者、分类、标签、摘要、分页等）| simple => 显示简约版文章列表（仅标题和日期）| none 不显示文章列表

postList: none
notices: # 可选的
    - id: doc-apis
      title: 🚀 doc-apis v1.0.0 正式版发布！
      content: '<div><ul><li>2024-07</li><li>v1.0.0</li></ul></div><p style="text-align: right;"><a href="/pages/2934a3/">查看详情</a></p>'
      isHtmlContent: true
---
<Notice :data="$frontmatter.notices"/>

<br/>

## ⛵赞助商

::: cardList
```yaml
- name: Easy-Es
  desc: 傻瓜级Elasticsearch 搜索引擎ORM框架...
  avatar: /img/sponsor/easy-es-logo.jpg
  link: https://www.easy-es.cn/
  bgColor: '#25c37d'
  textColor: '#FFFFFF'

- name: 明道云零代码平台
  desc: 快速响应业务需求, 从"IT背锅侠"变成"IT英雄"...
  avatar: /img/sponsor/mingdao-logo.jpg
  link: https://www.mingdao.com?s=utm_206&utm_source=doc-apis&utm_campaign=IT%E7%BD%91%E7%AB%99&utm_content=%E6%B3%A8%E5%86%8C%E4%BD%93%E9%AA%8C
  bgColor: '#25c37d'
  textColor: '#FFFFFF'

- name: FastBee
  desc: 简单易用更适合中小企业和个人学习的物联网平台...
  avatar: /img/sponsor/fxwl-logo.gif
  link: https://fastbee.cn/
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
- **零侵入:** 不需要像Swagger等框架,需要写额外的业务代码才能生成文档,只要代码符合基本代码规范,即可自动生成接口文档
- **零配置:** Springboot项目最少仅需0行配置,即可自动生成接口文档,所有配置为易用而生,均有默认值,按需配置即可
- **依赖透明:** 引入后对原项目完全透明,无任何影响,甚至都不需要打包进项目,无需担心引入三方依赖带来额外风险
- **敏捷开发:** 无需实现接口,仅需要定义好接口请求URL,请求类型,请求出入参即可生成,便于前后端快速投入开发
- **内容丰富:** 从请求URL,到请求方式,请求入参,出参应有尽有,参数类型,是否必填,参数描述等所需全部信息一目了然
- **类型丰富:** 可一次性生成Hmtl,MD等多种格式文档,并且同时适配WEB,IOS,Android等多种类型,适应各种需求场景
- **支持广泛:** 无论是主流的SpringBoot项目,Spring项目还是小众的Jfinal,Player等均可适配
- **功能强大:** 支持在线调试功能,支持多种请求方式,支持自定义请求头等功能,一站式搞定接口文档及接口调试
- **多语言:** 支持生成多国语言的接口文档,并且使用文档目前也已支持中英文双语,其它语种欢迎有志之士贡献
- **兼容性好:** 不挑食,从JDK8~JDK21均兼容,SpringBoot从1.x~3.x均可兼容,Spring,Jfinal等项目可兼容所有版本
- **规范代码:** 从源头监控代码质量,哪个模块代码未写注释,未遵循Restful风格接口设计等一目了然,反向督促开发者规范代码
- **使用简单:** 高端的食材仅需简单的烹饪,高端的文档生成框架也仅需简单的操作,从入门到精通0~5分钟光速上手
- **智能客服:** 官网提供了针对doc-apis全部使用文档专项训练增强的AI答疑机器人,可辅助解决您在使用中遇到的各种问题
- **费用低廉:** 个人用户及规模小于等于10人的企业终身免费使用,中大型企业按规模阶梯收取少量费用,非盈利目的,仅为可持续发展
- **持续更新:** 活跃的开源社区,强大的研发团队,未来可期...

<br/>
<br/>

## ✨最新版本 Latest Version: [![Maven Central](https://img.shields.io/github/v/release/xpc1024/doc-apis?include_prereleases&logo=xpc&style=plastic)](https://search.maven.org/search?q=g:com.doc-apis)

### Springboot项目

**Maven:**

```xml
<dependency>
    <groupId>com.doc-apis</groupId>
    <artifactId>doc-apis-starter</artifactId>
    <version>${Latest Version}</version>
</dependency>
```
**Gradle:**

```groovy
compile group: 'com.doc-apis', name: 'doc-apis-starter', version: 'Latest Version'
```

### 非Springboot项目

```xml
        <dependency>
            <groupId>com.doc-apis</groupId>
            <artifactId>doc-apis-core</artifactId>
            <version>Latest Version</version>
        </dependency>
```

**Gradle:**

```groovy
compile group: 'com.doc-apis', name: 'doc-apis-core', version: 'Latest Version'
```
<br/>
<br/>

:::tip 版本稳定吗？

在版本发布前,我们针对每项功能我们都进行了严密测试和Code Review.

另外我们针对整个框架的性能,安全等方面都做了理论分析+实际测试,确保每位用户用得放心,具体可查看文档顾虑粉碎模块.

我们由知名开源社区Aizuda社区孵化,并且作者也是Dromara开源社区成员,Easy-Es作者,拥有丰富的开发经验, 且本框架

具备真正零侵入的特性,无需打包进项目即可使用, 所以,请您放心引入使用！
:::

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
  <span style="width: 150px;text-align: left">
      <a href="https://www.easy-es.cn/" target="_blank">
          <img :src="$withBase('/img/external/easy-es.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
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
      <a href="https://aizuda.com/" target="_blank">
          <img :src="$withBase('/img/aizuda/aizuda.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
  <span style="width: 150px;text-align: left">
      <a href="https://dromara.org/" target="_blank">
          <img :src="$withBase('/img/dromara/dromara.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
  <span style="width: 150px;text-align: left">
      <a href="https://snailjob.opensnail.com/" target="_blank">
          <img :src="$withBase('/img/aizuda/snail.svg')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
  <span style="width: 150px;text-align: left">
      <a href="https://www.mongoplus.com/" target="_blank">
          <img :src="$withBase('/img/aizuda/mongo-plus.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
      </a>
  </span>
  <span style="width: 150px;text-align: left">
      <a href="https://fastbee.cn/" target="_blank">
          <img :src="$withBase('/img/external/fxwl-friend.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
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

