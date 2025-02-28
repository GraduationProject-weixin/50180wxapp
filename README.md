# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50180wxapp奶茶点餐小程序ssm

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第一章 绪论
## 1.1 项目背景及问题概述
目前随着智能手机的不断普及，基本上可以达到人均一台智能手机的地步，在这样的背景下。智能手机的好处就是有各种各样的软件，并且交互性很好，用户使用起来方便，在智能手机刚开始的前几年，有很多行业已经开始提前布局移动终端，占领了相当大的市场，不仅提高了客户满意度，也提高了市场知名度，但是随着时代的发展，如果还一直开发移动终端的软件，会导致用户手机里面需要安装各种各样的软件，用户已经从刚开始的新奇，变成了现在的厌烦，手机内存太小，安装太多东西，或者非强制性的软件，用户都不想安装了。面对如今的用户需求情况，依然开发APP软件已经是一种战略性失败。在国内目前市场上所有的智能手机里面肯定安装得有微信，微信已经变成了智能手机通讯的代名词，而微信推出了微信小程序，不需要用户注册账号，也不需要用户安装多余的软件，只需要通过微信软件就可以访问小程序，对用户极其友善，所以很多企业都瞄准了微信小程序。奶茶店用户对象永远都是年轻人为主题，喜欢新奇的东西，所以用流行的微信小程序用来点餐，年轻用户群体接收程度会比较高。本课题就是在这样的大环境下研究和实现一款奶茶店自助点餐系统。
## 1.2 选题意义
奶茶店用户可以不需要安装各种各样的APP，只需要一个微信就可以各种访问程序，用户不需要注册各种信息，微信提供了用户一键访问，并且可以在微信里面对小程序进行删除，定位，搜索，以及收藏，微信小程序是目前最火的一个开发方向。很多商家只需要开发出微信小程序，自己部署服务端，然后有任何需要推广的只需要让用户点击微信小程序访问即可，不仅仅给商家提供了一个十多亿用户的平台，也给用户减轻了安装各种APP的负担，并且微信所在的腾讯公司也能获得利润，微信小程序是一款多赢的选择。

本课题研究的奶茶店自助点餐系统前后台分离，让商品订单，商品信息等相关信息集中在后台让管理员管理，让用户在小程序端点餐，管理个人订单，该系统让信息管理变得高效，也让用户点餐，查看个人订单等信息变得越来越方便。
## 1.3 研究内容
本系统后台采用Java的SSM框架作为奶茶店管理员的操作界面，微信小程序采用uni-app框架开发，数据库用到了MySQL数据库，开发了奶茶店自助点餐系统，解决了用户在奶茶店点餐的不确定性，可以让用户多看看奶茶点的奶茶，然后可以自主点餐，不仅让点餐变得更加生动，订单记录的存在更加贴心。

# 第二章 系统的开发的相关技术
开发本系统需要配置开发环境，除了需要开发者安装相应的软件外，也需要对开发中运用的技术进行了解和掌握。
## 2.1 Java语言
Java语言是目前最流行的语言之一，不仅可以做桌面窗口形式的程序，还可以做浏览器访问的程序，目前最流行的就是用Java语言作为基础，做各种程序的后台处理。Java语言是操作变量的语言，而变量则是Java对于数据存在形式的定义，变量用来操作内存，而内存则牵扯到计算机安全问题，这样Java语言反而有了免疫直接针对用Java语言开发出来的程序的病毒，有效的提高了Java语言开发出来程序的生存能力。Java是具有动态运行能力的一种语言，Java的类不仅仅可以用Java核心提供的基础类，还可以进行重写，这样会让Java的功能变得更加丰富，甚至可以编写一些功能模块进行封装，然后其他项目如果需要用到这些可以复用的功能，完全可以直接引用，然后在用得地方调用方法即可。Java是一种开源的语言，可以对Java里面的各种类以及引用方法进行追溯，甚至可以对已经编译过的语言进行反编译，这样不仅仅提高学习的效率，并且可以学习其他从业者提供的优雅的编程方式。Java语言发展到现在，已经在各个行业扎根，学习Java可以从事的行业很多，并且学习的方法很多，网上有很多免费的教程，甚至有些高深的知识也只需要付费就可以进行学习，而不是像Java语言之初，每一个编程人员都需要用记事本进行手动编码，现在有很多集成开发环境帮助Java从业者。选择Java语言进行编程，是一种很好的解决问题的方式。
## 2.2 MYSQL数据库
一般学习程序开发的人员如果学习数据库的话，肯定是要学习MySQL数据库，MySQL数据库通过这么多年的不断发展，社区版本都是免费的，最重要的是小巧，占用电脑空间比较小，让更多的开发人员可以不需要更换更高级的电脑就可以进行学习。学习只是一个方面，最重要的是MySQL市场占有率是世界第一，基本上十个公司就有七八个用得MySQL数据库。MySQL的优点不只是这么粗浅，MySQL首先是开源的，只要不是商用就不用花钱，并且大型的数据也是支持的，只要是市面上存在的操作系统，MySQL都可以有对应的版本可供使用。因为MySQL是开源的，如果有对MySQL有特殊需求的甚至可以自己修改源码，达到符合自己使用的目的。MySQL数据库好处多多，最重要的一点符合本设计的开发需求，可以说本设计只用到了MySQL的一些基础功能，而这点基础功能就完全够用。MySQL学习的教程网上很多，许多关于入门的教程就完全可以达到普通程序员的开发水平，只需要把基本的知识学会了，到公司里面也只是根据不同的业务逻辑进行不同的语句编写而已。
## 2.3 Eclipse开发工具
Eclipse是开源免费的，仅仅这样理解也许会给人一种免费没有好货的感觉，其实不是这样的。Eclipse是一个开发源代码的开发工具，这样会很安全，因为是开源的，如果对使用者的电脑有害，肯定能找到原因所在，所以这一点安全方面是不用担心的。Eclipse是不用安装的，这样就不用对系统盘增加压力，可以放到任何一个盘里，使用的时候打开，不用的时候关闭，不会偷偷的在后台运行，不需要增加注册表负担，启动还必须依靠Java的JDK才可以启动，有效的避免了一些病毒入侵，如果病毒入侵改变了源代码，就不能运行了，只能重新删除文件夹重新解压一份新的Eclipse即可，用起来很安全。Eclipse发展到现在，已经可以支持其他的开发语言了，家族越来越强大，功能越来越多，最重要的还是没有收费，这一点就让新手开发者省下很多的资金用来培养自己的学习，而不用花钱买了开发软件才发现自己不适合进行开发，永远免费的策略可以永远让人有想使用的机会。最重要的是Eclipse并不是免费功能就不够用，恰恰相反，不仅功能强大，用起来完全符合本设计的开发需求，所以选用了Eclipse作为开发工具。
## 2.4 SSM框架
首先SSM框架是指的三个框架，第一个S是Spring MVC的首字母，主要是作为控制视图层的一种框架，第二个S是Spring框架的意思，主要是用来作为Web层，这一层主要是用来获取浏览器提交的一些信息并且把提交的信息处理后反馈给Spring MVC来控制不同的显示页面和内容；第三个M是的意思是MyBatis框架，主要是做为持久层用得，把数据对象转换成数据库表里的值，或者从数据库获取相应的数据转换成对应的Java对象让程序可以有效的进行转换和处理。三个框架可以有效的进行结合，实现不同的作用，起到了承上启下的作用。
## 2.5微信开发者工具
微信开发者工具并不是用来开发微信的一款软件，而是专门用来开发依附于微信的微信小程序和微信公众号的。现如今国内人口差不多14个亿，仅仅微信用户就12个亿之多，基本上覆盖了国内能使用智能手机的所有人群。微信功能相当丰富，可以聊天，视频，移动支付，甚至可以缴各种费用，依靠微信的庞大用户群体，不管是政府机关还是商业公司，都希望借助于微信使用者的庞大用户群体，简化各种支付或者信息推送渠道，让使用微信的人群不用太麻烦就可以完成正常生活的所有操作，极大的方便了人民群众。微信开发者工具就是在聆听到这样的呼唤声而诞生的，为了满足人们的需求，腾讯专门开发出来这个开发工具让其他公司进行使用，并且开放了很多接口以及使用方法，微信开发者工具变得越来越强大。

# 第三章 系统分析
这个阶段，需要依靠大量的资料作为研究本系统的基础数据，除了分析系统开发可行问题之外，还要再通过调查本系统针对的目标人群的需求来确定本系统功能，并在本系统的性能上做出进一步分析。
## 3.1可行性分析
在项目进行开发之前，必须要有可行性分析报告，分别从技术角度，经济角度，操作角度上面进行分析，经过可行性分析是实现科学开发的必要步骤。
### 3.1.1技术可行性
从技术的角度出发，目前采用开发的技术完全能满足系统开发需要。目前市场上有现成的软件开发工具和开发技术，这些可以保证系统开发的顺利进展。
### 3.1.2操作可行性
奶茶店自助点餐系统是根据用户经常使用的页面操作流程来进行设计的，并且页面保证统一，从视觉角度和操作角度上都能达到使用要求。
### 3.1.3经济可行性
在本次开发过程中，因为需要通过电脑来进行配置开发的环境，通过对技术的分析，发现目前正在使用的电脑是可以满足开发需要的，并不需要太多的金钱对电脑进行更换。所以，从经济角度上分析，可以满足开发要求。

从以上三个角度来进行分析论证，证明了奶茶店自助点餐系统是可以正常开发并且使用的。

## 3.2 系统性能分析
系统在使用过程中，用户会享受到系统带来的便利。那么如何保持在长时间的使用过程中，不出现乱七八糟的问题，让使用系统变成一种操作上的享受，使用上的便捷，这就是需要考虑的问题。以下主要从系统的性能分析上面进行描述，从数据完整以及数据安全，包括系统的可扩展等方面进行介绍。
### 3.2.1系统安全性
注册用户与游客用户的区别就在于是否有账号，如果有账号，那么就有相关的注册用户权限，有账号就有密码，密码是保证账号安全性的前提，游客只能浏览一些公共性信息，如果需要用户登录才能观看的信息，那么也需要使用账号登录的。对于系统安全性上面，主要考虑角色的密码加密问题，这样可以防止有效的密码数据拦截后的破解工作。一般密码如果有安全性要求的话，是可以考虑加密存储。密码的加密存储大致有两种设计方法，一种是密码在前台提交后就用Java Script进行MD5加密，然后直接提交密文，这样的好处是密文传输的安全性，另一种是提交密码后在后台处理的过程中对密码进行加密或者解密，这样会增加后台的处理负担。一般都居中考虑，如果登录的话会把密码在后台进行加密与数据库密码进行对比。目前常用的加密方式是MD5加密方式。
### 3.2.2数据完整性
系统进行开发的最重要的目的就是数据的处理，计算机有其擅长数据的存储以及处理工作，所以数据的完整性是必须保证的，不然系统的存在是没有必要的。数据不管是设计还是存储，都必须完整，从数据的输入就从各个方面保证数据的合法性，违规数据不能直接提交的。数据处理逻辑也会保证数据的加工正常，进而进行数据存储，也会保证数据设计的合理，这些都是有数据设定要求的。目前对数据的存储采用的关系型数据库，关系型数据库有多年的历史，功能强大，迁移备份以及无人值守都可以进行自动备份的。
### 3.2.3系统可扩展性
系统是有必要存在扩展性的。在设计之初就要考虑可能存在的业务，所以对系统的设计就要模块化设计，这样需要进行扩展的时候，只要在对应模块进行增加，对应逻辑进行调试即可。系统可扩展性的提升会让系统增加不必要的工作量，让程序设计更加符合规范。
## 3.3系统功能分析
本系统在功能分析上，主要是根据目标用户群的角度进行分析，为了便于展示分析结果，这里就使用用例图进行功能展示。

管理员用例图的绘制结果见图3-1。管理员登录进入本系统操作的功能包括管理商品，回复商品评价，为商品订单进行出餐，管理新闻和用户，管理客服聊天。

![](/md/blog.002.png)

图3-1 管理员用例图

用户用例图的绘制结果见图3-2。用户登录进入本系统操作的功能包括管理购物车，下单购买商品，在线充值，查看商品评价，管理商品订单等。

![](/md/blog.003.png)

图3-2 用户用例图
# 第四章 系统设计
到目前为止，市面上已经存在了各种各样的软件系统，从系统的分类着手，主要应用范围倾向于办公系统，娱乐系统，社交系统，然后下面有很多比较细的分支系统。很多系统已经经过了市场的考验，针对不同的业务场景已经开始出现了业务模块化，程序员减代码化的各种设计方式。到目前为止，当要设计一个系统的时候，首先根据业务模型基本上都可以在网上找到类似的模板，然后根据具体业务具体分析，进而实现具体功能，大众的就是最好的，毕竟符合市场主流的就代表着肯定符合常规操作流程。
## 4.1 系统设计目标
系统设计的时候，就要制定需要达成的目标。在功能上，要严格符合设计需求，不仅仅要减少操作步骤，也要符合预期。因此，在规范化的今天设计出符合项目要求的系统，必须要达到下面设定的目标。

第一个目标就是友好性：友好性主要体现在用户使用过程中，不会对系统的操作产生一种不满，减少操作者的愤怒，这是相当重要的一个体现。前几年好多软件在这个友好性方面失去了市场，就是因为在友好性这方面没有做好。国内互联网发展初期，软件设计的目的就是能用就行，至于友好性的对比，那是不存在的，因为硬件效率比较低，计算机属于新兴行业，所以大哥不说二哥，都是不友好的。随着计算机硬件的提升，很多开发者开始注意到要牺牲一定的计算器性能来提升友好性，因为计算机发展到现在，第一印象很重要，一个软件设计的不好看，会让大部分人对其产生质疑，所以要在友好性上面下很大功夫进行雕琢。

第二个目标就是安全性：安全性其实贯穿着整个软件行业的发展史，计算机就是为解决人类重复性计算以及数据存储的目的而诞生的，很多行业都需要计算机来进行计算，减少出错几率，并且把数据保留，可以实时查询，所以数据的安全性也很重要。

只要保证数据安全性的前提，开发出符合功能需求的友好界面操作，那么就达到了系统设计的目的。
## 4.2功能结构设计
本系统主要是基于数据的增加，修改，删除等操作，使用者能够通过提前设定的登录功能进入指定的操作区，这里对使用者设计的功能进行结构展示。

管理员功能结构图的绘制结果见图4-1。管理员登录进入本系统操作的功能包括管理商品，回复商品评价，为商品订单进行出餐，管理新闻和用户，管理客服聊天。

![](/md/blog.004.png)

图4-1 管理员功能结构图

用户功能结构图的绘制结果见图4-2。用户登录进入本系统操作的功能包括管理购物车，下单购买商品，在线充值，查看商品评价，管理商品订单等。

![](/md/blog.005.png)

图4-2 用户功能结构图
## 4.3数据库设计
如果说设计系统的功能很重要，那么设计该系统的数据库将更重要，毕竟系统服务于用户，数据库服务于系统，用户访问系统，操作系统的所有数据都要依赖于数据库，而系统的数据几乎都是保存在数据库中的，所以，一个高质量的程序，必然拥有一个安全，快速响应，稳定可靠的数据库。本系统的MySQL数据库可以通过SQL语言来实现对系统数据的管理，包括在指定表中插入数据，在规定的表中更改数据，以及删除指定表中的部分数据等操作。一般来说，像MySQL这样的关系型数据库，对于结构化查询语言SQL都能很好的进行支持。在编程中，通过合理运用SQL语言便能操作数据库的各种数据，真是非常方便快捷！
### 4.3.1 数据库概念设计
本节内容主要是使用图形的方式来描述数据库中的实体，每个实体的相应属性，还有实体之间的相互联系，常用的Visio工具即可满足绘制E-R图的需求。E-R图是由矩形，椭圆，菱形等图形元素组成，矩形框中主要写实体的名称，椭圆框中主要是登记该实体的属性，而菱形框中主要是登记实体之间的联系名称，最后使用实心线段把这些图形元素进行连接，即可完成E-R图的绘制。当初步得到一个E-R图时，需要进行检查，使用分析的方式去修改，重构E-R图，以达到消除数据冗余，或者是消除实体间联系冗余的目的。从而保持数据库的完整性，以及降低数据库维护上面的难度。

（1）使用Visio这样的常用的实体属性图绘制工具来绘制商品订单实体属性图，绘制结果见图4-3。

![](/md/blog.006.png)

图4-3 商品订单实体属性图

（2）使用Visio这样的常用的实体属性图绘制工具来绘制商品实体属性图，绘制结果见图4-4。

![](/md/blog.007.png)

图4-4 商品实体属性图

（3）使用Visio这样的常用的实体属性图绘制工具来绘制管理员实体属性图，绘制结果见图4-5。

![](/md/blog.008.png)

图4-5 管理员实体属性图

（4）使用Visio这样的常用的实体属性图绘制工具来绘制用户实体属性图，绘制结果见图4-6。

![](/md/blog.009.png)

图4-6 用户实体属性图

（5）绘制的上述实体间存在的联系见图4-7。

![](/md/blog.010.png)

图4-7 实体间关系E-R图
### 4.3.2 数据库物理设计
本系统数据在数据库中都是通过各种二维表进行记录保存的，在数据库中设计这样的二维表也是比较重要的内容，因为它影响着数据的存储效率。在设计二维表也就是关系模型之前，一些有关二维表方面的常用概念需要进行充分了解。

关系：一张具体的数据表即表示关系，关系的名称与数据表的名称保持一致；

元组：数据表中，每行显示的数据即代表元组；

属性：数据表中，每列表示的数据即代表属性；

关键字：数据表中，为了与其他数据表进行区分，则需要在每张表中进行主键的设置；

通过上节内容可以知晓数据库中的各个实体，并通过一定方式把这些实体表示的内容进行数据表的转换，通常来说，每个实体都会对应一张具体的数据表，在本系统指定的数据库中创建命名好的数据库，才可以对数据表进行创建与设计。奶茶店自助点餐系统数据表设计结果展示如下：

表4.1 购物车表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|yonghu\_id|所属用户|int(11)|是|
|goods\_id|商品|int(11)|是|
|buy\_number|购买数量|int(11)|是|
|create\_time|添加时间|timestamp|是|
|update\_time|更新时间|timestamp|是|
|insert\_time|创建时间|timestamp|是|
表4.2 客服聊天表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|yonghu\_id|提问用户|int(11)|是|
|chat\_issue|问题|varchar(200)|是|
|issue\_time|问题时间 |timestamp|是|
|chat\_reply|回复|varchar(200)|是|
|reply\_time|回复时间 |timestamp|是|
|zhuangtai\_types|状态|int(255)|是|
|chat\_types|数据类型|int(11)|是|
|insert\_time|创建时间|timestamp|是|
表4.3 商品信息表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|goods\_name|商品名称 |varchar(200)|是|
|goods\_types|商品类型 |int(11)|是|
|goods\_photo|商品照片|varchar(200)|是|
|goods\_kucun\_number|商品库存|int(11)|是|
|goods\_old\_money|商品原价|decimal(10,2)|是|
|goods\_new\_money|现价|decimal(10,2)|是|
|goods\_clicknum|点击次数|int(11)|是|
|shangxia\_types|是否上架|int(11)|是|
|goods\_delete|逻辑删除|int(11)|是|
|goods\_content|商品简介|text|是|
|create\_time|创建时间 |timestamp|是|
表4.4 商品收藏表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|goods\_id|商品|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|goods\_collection\_types|类型|int(11)|是|
|insert\_time|收藏时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|
表4.5 商品评价表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|goods\_id|商品|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|goods\_commentback\_text|评价内容|text|是|
|reply\_text|回复内容|text|是|
|insert\_time|评价时间|timestamp|是|
|update\_time|回复时间|timestamp|是|
|create\_time|创建时间|timestamp|是|
表4.6 商品订单表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|goods\_order\_uuid\_number|订单号|varchar(200)|是|
|goods\_id|商品|int(11)|是|
|yonghu\_id|用户|int(11)|是|
|buy\_number|购买的数量|int(200)|是|
|goods\_order\_true\_price|实付价格|decimal(10,2)|是|
|goods\_order\_types|订单类型|int(11)|是|
|goods\_order\_payment\_types|支付类型|int(11)|是|
|insert\_time|订单创建时间|timestamp|是|
|create\_time|创建时间 |timestamp|是|
表4.7 新闻信息表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|news\_name|新闻名称 |varchar(200)|是|
|news\_photo|新闻图片|varchar(200)|是|
|news\_types|新闻类型|int(11)|否|
|insert\_time|新闻发布时间|timestamp|是|
|news\_content|新闻详情|text|是|
|create\_time|创建时间 |timestamp|是|
表4.8 管理员表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|bigint(20)|否|
|username|用户名|varchar(100)|否|
|password|密码|varchar(100)|否|
|role|角色|varchar(100)|是|
|addtime|新增时间|timestamp|否|
表4.9 用户表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|username|账户|varchar(200)|是|
|password|密码|varchar(200)|是|
|yonghu\_name|用户姓名 |varchar(200)|是|
|yonghu\_photo|头像|varchar(255)|是|
|yonghu\_phone|用户手机号|varchar(200)|是|
|yonghu\_id\_number|用户身份证号|varchar(200)|是|
|sex\_types|性别 |int(11)|是|
|new\_money|余额|decimal(10,2)|是|
|yonghu\_delete|假删|int(11)|是|
|create\_time|创建时间|timestamp|是|

## 4.4系统流程设计
从系统的角色上分析，每个用户角色都代表了不同的账号身份，而不同的身份则代表着功能的异同，所以首先要区分用户的角色身份问题。设置用户登录需要输入账号和密码，输入的信息必须与数据库里已经存在的账号密码信息进行比对，只有正确的账号和密码才可以进行下一步的页面显示操作，如果不正确的账号密码，则拒绝用户登录，也代表着用户没有继续访问的权限，系统是无法继续提供服务的。

![](/md/blog.011.png)

图4-8 操作流程图

任何一个系统都有一个操作流程，本设计里面，对于任何数据的存储都有一定的合法要求，只有符合设定要求的数据才可以进行存储。具体步骤参考下图。

![](/md/blog.012.png)

图4-9 添加信息流程图

数据的存储并不是一成不变的，当需要对已经存在的数据进行改变的时候，同样也遵循着操作流程，想更改数据首先要确定更改之前的数据是什么，然后输入新的数据是否合法，都要符合流程，只有合法数据才可以被更新到数据库里存储。具体步骤参考下图。

![](/md/blog.013.png)

图4-10 修改信息流程图

删除操作，在数据存储方面是一件比较慎重的事件，很有可能会产生失误操作，所以一般删除操作的时候都要提示是否删除，确定删除才会更新数据库内容，实现删除目的。具体步骤参考下图。

![](/md/blog.014.png)

图4-11删除信息流程图

# 第五章 系统实现
这里主要是对系统设计实现进行描述，通过系统的设计和数据库的设计，通过编码后变成了可以进行操作的界面，让一切想法变成了结果，通过文字和具体程序操作界面的截图之间的配合，可以把功能更直观的描述起来。
## 5.1管理员功能实现
### 5.1.1 商品信息管理
管理员进入如图5-1所示的商品信息管理界面之后，管理员点击信息显示栏中最右侧的修改，删除按钮可依次完成商品信息的修改，删除等操作，管理员也能在当前界面下架商品，增加商品的库存，减少商品的库存等。

![](/md/blog.015.png)

图5-1 商品信息管理界面
### 5.1.2 商品评价管理
管理员进入如图5-2所示的商品评价管理界面之后，管理员点击信息显示栏中最右侧的回复，删除按钮可依次完成商品评价信息的回复，删除等操作。

![](/md/blog.016.png)

图5-2 商品评价管理界面
### 5.1.3 商品订单管理
管理员进入如图5-3所示的商品订单管理界面之后，管理员点击信息显示栏右侧的删除，出餐按钮可依次完成商品订单的删除，出餐等操作。

![](/md/blog.017.png)

图5-3 商品订单管理界面
### 5.1.4 用户管理
管理员进入如图5-4所示的用户管理界面之后，管理员点击信息显示栏中最右侧的修改，删除按钮可依次完成用户信息的修改，删除操作，管理员在本界面也能查询用户信息，重置用户的密码等。

![](/md/blog.018.png)

图5-4 用户管理界面
## 5.2用户功能实现
### 5.2.1 商品信息
用户进入如图5-5所示的商品信息界面之后，用户可以通过商品的评价和商品的介绍来了解商品信息，用户购买商品可以通过加入购物车或点击立即购买按钮来实现，不过加入购物车需要用户亲自在购物车模块去完成订单提交操作，立即购买功能可以帮助用户在本界面就能下单购买商品。

![](/md/blog.019.png)

图5-5 商品信息界面
### 5.2.2 订单确认
用户进入如图5-6所示的订单确认界面之后，用户点击确认支付就可以支付订单。

![](/md/blog.020.png)

图5-6 订单确认界面
### 5.2.3 商品信息订单
用户进入如图5-7所示的商品信息订单界面之后，用户可以查看已评价订单，查看已取餐订单，查看已出餐订单，查看已支付订单，查看退款订单等，而用户可以在本模块进行订单退款，订单评价等操作。

` `![](/md/blog.021.png)

图5-7 商品信息订单界面
### 5.2.4 用户充值
用户进入如图5-8所示的用户充值界面之后，用户需要输入充值的金额，该金额信息必须是数值信息才可以提交。

![](/md/blog.022.png)

图5-8 用户充值界面













