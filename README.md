# jblog
A multi-user blog system implemented with Spring /MVC+ Hibernate + MySQL + Bootstrap + freemarker.

# about jblog

> Now deployed in http://51so.info and my blog home is http://kingschan.51so.info 


### 部署方法及二次开发的步骤正在整理中，即将整理好公布 ~ 



## 背景
本人程序员一枚，从事web开发时常要学习各种新技术，总结遇到的各种问题，已便下次遇到些类问题时能快速搞定，并将此分享帮助有需要的人。<br>最好的记性也抵不过岁月的冲击。常言道，时光能冲淡一切！把重要的东西写下来保存是个很不错的选择。
- 写作的过程中会总结增强理解
- 分享能帮助有需要有人，还能在线与人交流一起探讨
- 下次遇到此类问题有据可查
- 温故而知新
- 等等...

## 遇到的问题&诞生
写作找个好的平台还是挺重要的，最初我是在`QQ空间`发表日志，后来发现好友都不是同一个圈子的。另个`QQ空间` 对附件，代码这方面的支持不好。而且交流的圈子也比较有限。不利于交流和传播。后来我在网上找了一下其它博客平台，如`新浪`用了几个月发现功能及界面太丑，发表代码这个是硬伤。后来又加入`iteye`,`CSDN` 代码的问题解决了，但是操作不便利，界面太丑，当然iteye的自定义个性域名，我很喜欢。到最后的`github` 我突然有个想法从脑中闪过，要不我自立门户，自已开发一个？至此51so.info 就诞生了。寓意：`我要搜信息`

## 想法
> 致力打造属于更合适用户使用的博文平台，集百家之长。

![51so.info](https://raw.githubusercontent.com/kingschan1204/jblog/master/git-res/blog.png )

## 现状
目前平台已上线了第一版，个人博客功能基本完成。目前内测阶段。暂未开放注册。[平台主页](http://51so.info),[登录](http://51so.info/pub/login.do)，[我的博客](http://kingschan.51so.info)
由于此项目设计，开发，测试，部署等等都是我一个人在搞，所以目前进度不是很理想 T_T... ... 只能在业余时间开展。

## 现有功能
- **泛型域名访问个人主页：用户名.51so.info**
- **响应式布局，一套UI自适应手机，电脑，平板电脑**
- 文章管理
- 书签
- 文章分类
- 留言板
- **文章评论，点赞，回复，emojify表情**
- 文章标签
- **文章全文检索**
- 博客banner设置
- **博客多皮肤（目前只开发了一套皮肤，往后会有多套）**
- 新浪微薄登录
- **多编辑器支持html,markdown风格编写博文**

## 界面截图
登录界面：
![登录](https://raw.githubusercontent.com/kingschan1204/jblog/f75356d181547441ebdbbcd5908b247d6dfef568/git-res/login.png )

后台首页
![后台首页](https://raw.githubusercontent.com/kingschan1204/jblog/7fb25f7b03bd0a9c4cbbb1dfe58c5aeec28ca206/git-res/admin_home.png )

文章列表
![文章列表](https://raw.githubusercontent.com/kingschan1204/jblog/ad4738caf523ad68bcf2885a4f64e16b20cf933c/git-res/admin_article_list.png )
文章发布
![文章发布](https://raw.githubusercontent.com/kingschan1204/jblog/fecdf33aa234a1f2a13a823ce6bd4c61ed3e02ce/git-res/admin_article_edit.png )

文件管理
![文件管理](https://raw.githubusercontent.com/kingschan1204/jblog/1aa8b0b1739aecf526f69c278f99e648606b957b/git-res/admin_res_list.png )

博客信息设置
![](https://raw.githubusercontent.com/kingschan1204/jblog/f69a0b4e0e973f42e053fa8b4a09f7d901ab0fc9/git-res/admin_site_info.png )

### 手机访问效果

![](https://raw.githubusercontent.com/kingschan1204/jblog/f69a0b4e0e973f42e053fa8b4a09f7d901ab0fc9/git-res/mobile-article-info.PNG )

![](https://raw.githubusercontent.com/kingschan1204/jblog/f69a0b4e0e973f42e053fa8b4a09f7d901ab0fc9/git-res/mobile-home.PNG )

![](https://raw.githubusercontent.com/kingschan1204/jblog/f69a0b4e0e973f42e053fa8b4a09f7d901ab0fc9/git-res/mobile-list.PNG )

![](https://raw.githubusercontent.com/kingschan1204/jblog/f69a0b4e0e973f42e053fa8b4a09f7d901ab0fc9/git-res/mobile.PNG )

### 文章详情

![](https://raw.githubusercontent.com/kingschan1204/jblog/master/git-res/font-article-info.png )

### 评论
emojify表情支持
![](https://raw.githubusercontent.com/kingschan1204/jblog/7fb25f7b03bd0a9c4cbbb1dfe58c5aeec28ca206/git-res/facebox.png )
![](https://raw.githubusercontent.com/kingschan1204/jblog/master/git-res/article-info-comment1.png )
![](https://raw.githubusercontent.com/kingschan1204/jblog/master/git-res/article-info-comment.png )


## 立项功能待开发
- 专题的概念
- 关注 博文收藏,点赞
- 好友功能
- 回复可以像新浪微博一样统计条数，及显示回复列表
- 评论编辑器位置优化
- 随机阅读文章
- 自定义导航
- 草稿箱
- 评论点赞明细
- 打赏
- ...

## 所用技术(感谢己下项目)
- [Spring](https://spring.io/projects ) : Spring ,Spring MVC 
- [Hibernate](https://github.com/hibernate/hibernate-orm ):ORM 框架
- [Hibernate Search](https://github.com/hibernate/hibernate-search ):全文检索
- [HanLP](https://github.com/hankcs/HanLP ):中文分词处理
- [Quartz](https://github.com/quartz-scheduler/quartz) :任务调度
- [Junit4](https://github.com/junit-team/junit4 ):单元测试
- [pegdown](https://github.com/sirthias/pegdown ):java markdown 处理
- [jsoup](https://github.com/jhy/jsoup ):HTML分析器
- [druid](https://github.com/alibaba/druid ):一个好用的数据源
- [java-uuid-generator](https://github.com/cowtowncoder/java-uuid-generator ):java uuid 时间戳式的生成
- [user-agent-utils](https://github.com/HaraldWalker/user-agent-utils ):use-agent 分析处理
- [bootstrap](https://github.com/twbs/bootstrap ):bootstrap 前端流行的UI
- [ueditor](https://github.com/fex-team/ueditor ):html 编辑器
- [bootstrap-popover-x](https://github.com/kartik-v/bootstrap-popover-x ):提示框
- [bootstrap-notify](https://github.com/mouse0270/bootstrap-notify ):bootstrap 消息通知插件
- [bootstrap-markdown](https://github.com/toopay/bootstrap-markdown ):bootstrap markdown 编辑器
- [bootstrap-tokenfield](https://github.com/sliptree/bootstrap-tokenfield ):bootstrap 标签插件
- [scrollfix](https://github.com/kujian/scrollfix):jquery插件：滚动到某个位置固定起来
- [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe ):图片浏览插件
- [viewerjs](https://github.com/fengyuanchen/viewerjs ):又一个图片浏览插件
- [cropbox](https://github.com/hongkhanh/cropbox ):base64图像裁剪插件
- [echarts](https://github.com/ecomfe/echarts ):百度echarts
- [highlight](https://github.com/isagalaev/highlight.js ):语法高亮
- [emojify](https://github.com/Ranks/emojify.js):emojify 表情包
- [nprogress](https://github.com/rstacruz/nprogress ):jquery 进度条 
- [animate.css](https://github.com/daneden/animate.css ):css 动画
- [webuploader](https://github.com/fex-team/webuploader ):百度文件上传插件