Version 0.3.5 (未发布)
---------------------

新功能:

改进:

* 调整项目、任务和子任务相关模板路径
* 新增Manage管理模块，将项目管理相关的功能置入

Bug修复:

* 修复OAuth授权系统报错的问题
* 修复插件路径重复携带controller的bug

Version 0.3.4 (2016-01-05)
--------------------------

新功能:

* 可以设置项目默认显示页面，可设置为概况、看板、日历、列表和甘特图，默认是概况

改进:

* 合并TaskGanttController的功能到TaskController
* 删除项目设置的概况页(功能与项目概况页有重叠)
* 调整中文措辞，将`过滤`修改为`筛选`
* 修改子任务图标，并显示状态title
* 可根据需要设置弹出框大小，定义了大、中、小3个尺寸。
* 优化后台标签和关联管理
* 改进控制台、项目相关页面导航切换选中显示
* 改进后台管理中标签和关联设置

Bug修复:

* 修复开启`双重认证`导致用户登录失败的bug
* 修复勾选“继续创建新任务”会导致页面404
* 编辑任务弹框与创建保持一致，弹出大窗口
* 修复任务描述带双引号双重编码的bug

Version 0.3.3 (2016-01-04)
--------------------------

新功能:

* 在左侧导航`创建`新增`创建任务`功能

改进:

* 新增windows安装与升级步骤
* 补充部分中文翻译
* 调整dropdown样式，新增条目分隔符
* 改进搜索任务与动态切换导航

Bug修复:

* 解决后台不能添加用户的bug
* 解决项目权限页，团队搜索实时建议报错的bug