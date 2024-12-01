# 全目录

3000套系统，根据编号搜索演示视频，复制至流浪器：www.yuque.com/wisebit/blog


![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/11/06/qq_wechat.png)
# 042wxapp居住证申报系统
# 第五章 系统实现
## 5.1群众用户客户端功能实现
群众用户注册通过注册窗口，进行在线填写自己的用户账号、真实姓名、性别等，信息编辑完成后核对信息无误后进行选择注册，系统核对群众用户所输入的账号信息是否准确，核对信息准确无误后系统进入到操作界面。

群众用户通过登录进入到系统操作界面后，可以根据需求对首页、公告栏、我的等模块进行管理维护操作。

如图5-1所示。

![](/md/blog.011.png)

图5-1群众用户注册界面图

群众用户登录通过账号、密码行页面，进入到居住证申报系统主界面，进入到操作界面，进行相对应操作，如图5-2所示。

![](/md/blog.012.png)

图5-2群众用户登录界面图

群众用户首页页面可以查看首页、公告栏、我的等信息，进行提交操作，如图5-3所示。

![](/md/blog.013.png)

图5-3首页界面图

群众用户进入公告栏页面可以填写公告标题、封面图片、发布日期、发布人等信息，进行提交操作，如图5-4所示。

![](/md/blog.014.png)

图5-4公告栏界面图

群众用户进入我的页面可以填写居住证登记、回执单、领证信息等信息，进行提交操作，如图5-5-所示。

![](/md/blog.015.png)

图5-5我的界面图

群众用户进入用户信息页面可以填写用户账号、真实姓名、性别、年龄、照片等信息，进行保存、退出登录操作，如图5-6-所示。

![](/md/blog.016.png)

图5-6用户信息界面图

群众用户进入居住证登记页面可以填写申报编号、用户账号、真实姓名、性别、年龄、出生日期、民族、身份证、照片、所在户籍、政治面貌、联系电话、户主、与户主关系等信息，进行提交操作，如图5-7-所示。

![](/md/blog.017.png)

图5-7居住证登记界面图

5.2警方客户端功能实现

警方登录通过账号、密码行页面，进入到居住证申报系统主界面，进入到操作界面，进行相对应操作，如图5-8所示。

![](/md/blog.018.png)

图5-8警方登录界面图

警方首页页面可以查看首页、公告栏、我的等信息，进行提交操作，如图5-9所示。

![](/md/blog.019.png)

图5-9首页界面图

警方进入居住证登记页面可以填写申报编号、用户账号、真实姓名、性别、年龄、出生日期、民族、身份证、照片、所在户籍、政治面貌、联系电话、户主、与户主关系、申报时间、审核回复等信息，进行回执单、预约领证、审核操作，如图5-10所示。

![](/md/blog.020.png)

图5-10居住证登记界面图

警方进入回执单页面可以填写用户账号、真实姓名、性别、年龄、照片、联系电话、工号、回执内容、回执时间等信息，进行提交操作，如图5-11-所示。

![](/md/blog.021.png)

图5-11回执单界面图

警方进入领证信息页面可以填写用户账号、真实姓名、申报时间、领证时间、领证地点、说明、工号、警察姓名等信息，进行提交操作，如图5-12-所示。

![](/md/blog.022.png)

图5-12领证信息界面图

## 5.3管理员服务端功能实现
管理员通过居住证申报系统进行确认，管理员进入到居住证申报系统主界面，管理员进入到操作界面，通过登录窗口进行在线填写自己的用户名和密码、角色进行登录，登录成功后进入到系统操作界面进行相应信息的获取，如图5-13所示。

![](/md/blog.023.png)

图5-13管理员登录主界面图

管理员进入到界面，通过界面的任务大厅，登录成功后进入到系统可以进行查看首页、个人中心、群众用户管理、警方管理、居住证登记管理、回执单管理、领证信息管理、公告栏管理、系统管理等功能模块，进行相对应操作，如图5-14所示。

![](/md/blog.024.png)

图5-14管理员功能界面图

管理员点击进入警方管理页面可以查看工号、警察姓名、性别、年龄、联系电话、照片等信息，进行详情、修改、删除操作，如图5-15示。

![](/md/blog.025.png)

图5-15警方管理界面图

管理员进入居住证登记管理界面，通过界面的任务大厅，登录成功后进入到系统可以进行查看申报编号、用户账号、真实姓名、性别、年龄、出生日期、民族、身份证、照片、所在户籍、政治面貌、联系电话、户主、与户主关系、申报时间、审核回复、审核状态等信息，进行详情、修改、删除操作，如图5-16所示。

![](/md/blog.026.png)

图5-16居住证登记管理界面图

管理员进入到回执单管理界面，通过界面的任务大厅，登录成功后进入到系统可以查看用户账号、真实姓名、性别、年龄、照片、联系电话、工号、回执内容、回执时间等信息，进行详情、修改、删除操作，如图5-17所示。

![](/md/blog.027.png)

图5-17回执单管理界面图

管理员进入到领证信息管理界面，通过界面的任务大厅，登录成功后进入到系统可以查看用户账号、真实姓名、申报时间、领证时间、领证地点、说明、工号、警察姓名等信息，进行详情、修改、删除操作，如图5-18所示。

![](/md/blog.028.png)

图5-18领证信息管理界面图

管理员进入到公告栏管理界面，通过界面的任务大厅，登录成功后进入到系统可以查看公告标题、封面图片、发布日期、发布人等信息，进行详情、修改、删除操作，如图5-19所示。

![](/md/blog.029.png)

图5-19公告栏管理界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图5-20所示。

![](/md/blog.030.png)

图5-20轮播图管理界面图







