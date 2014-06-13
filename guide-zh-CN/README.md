Yii 2.0 权威指南
===============================

> ### 翻译说明
参与项目前，请先阅读两篇文档：[翻译手册](../translation-guide.md)及[校阅手册](../translation-proofreading.md)
> #### 文档汉化进度分为以下几种状态：
> 等待认领：
>
> - 【待翻译】任何翻译人员都可认领
> - 【需更新】指官方文档已更新，需要翻译人员或校对进行更新，及翻译。
>
> 无需认领：
>
> - 【翻译中】表示该文档已被某位翻译人员认领，正在翻译中，请等他完成再刊错。
> - 【已完成】官方文档无更新，已完成翻译和校对的中文文档，表示该文档翻译结束。
> 
> 翻译状态：
>
> - 【未校对】粗翻完成后更改
> - 【已更新】标明新增了内容，后面往往跟其他标签如：
>     * 【已更新|未校对】更新且汉化完成，但未经严格校对
>     * 【已更新|翻译中】更新大量内容，尚未完全汉化
> - 【已完成】校对完毕更新为该状态，文档需要更新时更改标签为【需更新】
>
> 临时说明：
> 1.目录前 **待定中，编撰中，已定稿** 标示官方文档编写进度情况，【】表示汉化进度。
> 2.标注了截止当天的翻译状态，【翻译中】和【待翻译】的文档可以暂时不翻译，因官方在重新编写文档。如需学习那些内容的同学也欢迎翻译。
> **************************

本教程的发布遵循[ Yii 文档使用许可](http://www.yiiframework.com/doc/terms/).

版权所有

2014 (c) Yii Software LLC.

介绍
-----

* **已定稿**【需更新-20140505|已完成-20140430】[关于 Yii](intro-yii.md)
* **已定稿**【需更新|未校对-20140502】[从 Yii 1.1 升级](intro-upgrade-from-v1.md)


入门
-----

* **已定稿**【待翻译-20140510】[安装 Yii](start-installation.md)
* **已定稿**【待翻译-20140510】[运行应用](start-workflow.md)
* **已定稿**【待翻译-20140510】[第一次问候](start-hello.md)
* **已定稿**【待翻译-20140510】[使用 Forms](start-forms.md)
* **已定稿**【待翻译-20140510】[玩转 Databases](start-databases.md)
* **已定稿**【待翻译-20140510】[用 Gii 生成代码](start-gii.md)
* **已定稿**【待翻译-20140510】[更上一层楼](start-looking-head.md)

应用结构
--------

* **编撰中**[结构总览](structure-overview.md)
* **已定稿**【待翻译-20140502】[入口脚本](structure-entry-scripts.md)
* **已定稿** [应用](structure-applications.md)
* **编撰中** [应用组件](structure-application-components.md)
* **已定稿**【未校对-20140501】[控制器](structure-controllers.md)
* **已定稿**【未校对-20140501】[视图（View）](structure-views.md)
* **已定稿**【未校对-20140501】[模型（Model）](structure-models.md)
* **待定中** [过滤器](structure-filters.md)
* **待定中** [小部件](structure-widgets.md)
* **待定中** [模块](structure-modules.md)
* **编撰中**【未校对-20140501】[前端资源](structure-assets.md)
* **待定中** [扩展（extensions）](structure-extensions.md)

请求处理
--------

* **待定中** [引导（Bootstrapping）](runtime-bootstrapping.md)
* **待定中** [路由（Routing）](runtime-routing.md)
* **待定中** [请求（Request）](runtime-requests.md)
* **待定中** [响应（Response）](runtime-responses.md)
* **待定中** [Sessions（会话）和 Cookies](runtime-sessions-cookies.md)
* **已定稿**【未校对-20140501】[URL 解析和生成](runtime-url-handling.md)
* **编撰中** 【未校对-20140502】[错误处理](runtime-handling-errors.md)
* **编撰中** 【未校对-20140502】[日志](runtime-logging.md)

关键概念
--------

* **已定稿**【待翻译-20140502】[组件（Component）](concept-components.md)
* **已定稿**【未校对-20140501】[属性（Property）](concept-properties.md)
* **已定稿**【未校对-20140501】[事件（Event）](concept-events.md)
* **已定稿**【未校对-20140501】[行为（Behavior）](concept-behaviors.md)
* **已定稿**【需更新-20140502】[配置（Configs）](concept-configs.md)
* **已定稿**【未校对-20140501】[类自动加载（Autoloading）](concept-autoloading.md)
* **已定稿**【未校对-20140501】[别名（Alias）](concept-alias.md)
* **已定稿**【翻译中-20140501】[服务定位器（Service Locator）](concept-service-locator.md)
* **已定稿**【翻译中-20140501】[依赖注入容器（DI Container）](concept-di-container.md)

配合数据库工作
-------------

* **编撰中**【未校对-20140501】[数据访问对象（DAO）](db-dao.md) - 数据库连接、基本查询、事务和模式操作
* **编撰中**【未校对-20140501】[查询生成器（Query Builder）](db-query-builder.md) - 使用简单抽象层查询数据库
* **编撰中**【未校对-20140501】[活动记录（Active Record）](db-active-record.md) - 活动记录对象关系映射（ORM），检索和操作记录、定义关联关系
* ****【未校对-20140501】[数据库迁移（Migration）](db-migrations.md)
* **待定中** [Sphinx](db-sphinx.md)
* **待定中** [Redis](db-redis.md)
* **待定中** [MongoDB](db-mongodb.md)
* **待定中** [ElasticSearch](db-elastic-search.md)

接收用户数据
-----------

* **编撰中**【未校对-20140501】[创建表单](input-forms.md)
* **已定稿**【翻译中-20140501】[输入验证](input-validation.md)
* **编撰中** [文件上传](input-file-uploading.md)
* **待定中** [多模型同时输入](input-multiple-models.md)

显示数据
--------

* **待定中** [格式化输出数据](output-formatting.md)
* **待定中** [分页（Pagination）](output-pagination.md)
* **待定中** [排序（Sorting）](output-sorting.md)
* **编撰中**【未校对-20140501】[数据提供器](output-data-providers.md)
* **编撰中**【需更新|翻译中-20140501】[数据小部件](output-data-widgets.md)
* **编撰中** 【未校对-20140502】[主题](output-theming.md)

安全
-----

* **编撰中**【未校对-20140501】[认证（Authentication）](security-authentication.md)
* **编撰中**【翻译中-20140501】[授权（Authorization）](security-authorization.md)
* **编撰中**【未校对-20140501】[处理密码](security-passwords.md)
* **待定中** [客户端认证](security-auth-clients.md)
* **待定中** [安全领域的最佳实践](security-best-practices.md)

缓存
-----

* **编撰中**【未校对-20140501】[概述](caching-overview.md)
* **编撰中** [数据缓存](caching-data.md)
* **编撰中** [片段缓存](caching-fragment.md)
* **编撰中** [分页缓存](caching-page.md)
* **编撰中** [HTTP 缓存](caching-http.md)

RESTful Web 服务
----------------

* **已定稿**【翻译中-20140501】[快速入门](rest-quick-start.md)
* **已定稿** [资源](rest-resources.md)
* **已定稿** [路由](rest-routing.md)
* **已定稿** [格式化响应](rest-response-formatting.md)
* **已定稿** [授权验证](rest-authentication.md)
* **已定稿** [速率限制](rest-rate-limiting.md)
* **已定稿** [版本化](rest-versioning.md)
* **已定稿** [错误处理](rest-error-handling.md)
* **已定稿** [测试](rest-testing.md)

开发工具
--------

* **编撰中**【未校对-20140501】[调试工具栏和调试器](tool-debugger.md)
* **编撰中**【翻译中-20140501】[使用 Gii 生成代码](tool-gii.md)
* **待定中** [生成 API 文档](tool-api-doc.md)


测试
-----

* **编撰中** [概述](test-overview.md)
* **待定中** [单元测试](test-unit.md)
* **待定中** [功能测试](test-functional.md)
* **待定中** [验收测试](test-acceptance.md)
* **编撰中** 【未校对-20140502】[定制器](test-fixtures.md)

扩展 Yii
--------

* **编撰中** 【未校对-20140502】[创建扩展](extend-creating-extensions.md)
* **编撰中** 【未校对-20140502】[定制核心代码](extend-customizing-core.md)
* **编撰中** 【未校对-20140502】[使用第三方库](extend-using-libs.md)
* **待定中** [在第三方系统使用 Yii](extend-embedding-in-others.md)
* **待定中** [Yii 1.1 和 2.0 共用](extend-using-v1-v2.md)
* **编撰中** 【未校对-20140502】[使用依赖包管理器 Composer](extend-using-composer.md)


高级专题
--------

* **编撰中** [高级应用模版](tutorial-advanced-app.md)
* **编撰中** [从头自定义模版](tutorial-start-from-scratch.md)
* **编撰中** 【未校对-20140502】[控制台命令](tutorial-console.md)
* **已定稿** [核心验证器](tutorial-core-validators.md)
* **编撰中** 【未校对-20140502】[国际化](tutorial-i18n.md)
* **编撰中** [收发邮件](tutorial-mailing.md)
* **编撰中** 【未校对-20140502】[性能优化](tutorial-performance-tuning.md)
* **待定中** [共享主机环境](tutorial-shared-hosting.md)
* **编撰中** 【未校对-20140502】[模板引擎](tutorial-template-engines.md)

小部件
------

* 表格视图（GridView）：链接到 demo 页
* 列表视图（ListView）：链接到 demo 页
* 详情视图（DetailView）：链接到 demo 页
* 活动表单（ActiveForm）：链接到 demo 页
* Pjax：链接到 demo 页
* 菜单（Menu）：链接到 demo 页
* LinkPager：链接到 demo 页
* LinkSorter：链接到 demo 页
* **编撰中** 【待翻译-20140502】[Bootstrap 小部件](bootstrap-widgets.md)
* **待定中** [Jquery UI 小部件](jui-widgets.md)

助手类
------

* **编撰中** 【待翻译-20140502】[概述](helper-overview.md)
* **待定中** [ArrayHelper](helper-array.md)
* **待定中** [Html](helper-html.md)
* **待定中** [Url](helper-url.md)
* **待定中** [security](helper-security.md)