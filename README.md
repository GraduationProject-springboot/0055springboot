# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0055springboot教学资源库

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV16ia6epENY?p=56)


# 研究背景
目前，在网络大环境下，越来越多高校开始实行网络教学，利用网络教学方式有利于学生更好的学习。

网络教学是指以计算机及网络为基础，来实现教学资源的上传、存储、传播和共享的教学手段。它是一种教学活动，必然存在着一定的学习方式，计算机网络是网络教学实现的技术基础，在过程中运用网络技术，来实现数据的互操作性、共享性，通过网络完成教学资源的管理与维护，使教学资源得到传播、扩展和延伸。网络教学是计算机信息工程、网络技术、计算机技术与现代教育技术发展到一定规模下的产物。网络教学具有方便管理、数据资源共享及可重用性的特点，使学生的学习变的方便，有趣，激发学习性，也是未来教学模式的主要趋势。与其它教学方式对比具有独特性。
## 1.2设计原则
在开始开发项目之前，必须要先考虑项目的实用性、科学性，以及该项目是否能够真正让用户受益并尽可能的发挥项目的作用。因此，在开发前，通过以下几条原则对项目进行判断：

（1）可行性原则。项目需要保证经济可行性和技术可行性，这包括了项目在浏览端、服务端等方面上的经济和技术上是可以达成的。

（2）适应性原则。项目要保证可维护性和可扩展性，这是每个非短期项目都需要考虑的，并且不论是维护还是扩展，都必须要建立在适应用户的正常需求的基础上。

（3）安全性及保密性原则。要充分保证用户信息的安全性和保密性，不能因为开发上的疏忽，导致用户的信息泄露。

（4）系统工程原则。为了确保项目的整体性，在项目调查、项目分析、项目设计、项目开发的过程中，都需遵从项目工程的方法和步骤逐步进行。

（5）统一规划、分期实施、逐步完善原则。项目开发的过程中，要按照规划、分期实施，特别是要注意在项目开发过程中要有条理，从点到面，一步步完善，不要贪图进度，要循环渐进的对项目进行开发。
## 1.3论文的组织结构
第一章主要是简单的介绍下设计本网站的研究背景和设计原则，在这一章里主要是让大家了解下我的设计的前因后果，为接下来我的其它章节做铺垫。

第二章主要是介绍在设计过程中所涉及到的技术。

第三章主要是介绍下设计这个网站所需要的需求以及我们的功能需求分析，因为只有更好的分析清楚我们的功能需求才能更好的完成我们的设计。

第四章网站系统设计，主要介绍了网站结构的设计以及展示了数据库E-R图设计，这一章主要是为了能让大家更好的了解网站的一些基本设计信息。

第五章系统的实现，介绍了系统每个模块的设计与实现，让大家能清晰的了解系统的主要功能。

第六章系统的测试，这章主要是测试下各个部分每个功能是否能用，看下是否有错误。

第七章系统总结，进行系统最后的总结工作。


# 2 相关技术简介
## 2.1Java技术
Java是一种非常常用的编程语言，在全球编程语言排行版上总是前三。在方兴未艾的计算机技术发展历程中，Java的身影无处不在，并且拥有旺盛的生命力。Java的跨平台能力十分强大，只需一次编译，任何地方都可以运行。除此之外，它还拥有简单的语法和实用的类库，让编程人员可以尽可能将精力集中在问题的求解上，并且许多开源项目和科研成果都是采用它实现的。

在1995年这一年的5月份，著名的Sun Microsystems公司在程序开发设计上面郑重推出一种面向对象开发的程序设计语言——Java，最开始的时候Java是由詹姆斯.高斯林这位伟大的JAVA之父来进行主导，但是在后来由于各种原因，让甲骨文公司这个针对商业程序创建了oracle大型数据库的公司收购了Java。Java的平台总共算下来有3个，分别为javaME和javaSE以及javaEE这3个java平台。下面将对其进行分别介绍。

（1）在电脑桌面程序的开发上面需要选择JavaME，这个用得也比较多。

（2）企业也会根据工作以及业务需要开发各种软件，那么就会选用JavcEE这个支持企业版软件的开发的Java平台，JavcEE主攻运用在企业领域上面的web应用，JavcEE也在javaSE的基础上获得了比如jsp技术 ，Servlet技术等程序开发技术的支持。

（3）现在生活中手机的普及化，也使得手机端这样的移动设备的软件的兴起，JavaME这个迷你版java平台就能运用于移动端的软件开发操作。
## 2.2B/S结构
此次设计的网络结构模式B/S结构（Browser/Server）。B/S架构也称为B/S模式，是一种服务器以及浏览器架构模式。B/S的工作模式都是先由浏览器请求，服务器再响应。B/S体系结构解决了异构系统中的连接难题，大大改善了系统的开放性，让系统的扩展和维护更加简单；同时，B/S体系结构操作也比较容易，界面全都为浏览器模式，容易分发数据的捕获程序。只要安装通用的浏览器（如WWW浏览器）就能通过Web服务器与数据库进行数据交互。此结构的好处之一在于由于它使用的统一的浏览器，使其可以在不同的地方且不需要用专门的软件进行操作，实现了不论你使用怎样的接入网的方式都可以对公共的数据进行调用和浏览。

相对于C/S模式，B/S模式是对C/S模式应用的扩展，B/S模式不用对不同的计算机安装不同应用程序，还有安全性的要求及对模式上手难度都比前者更好。B/S模式可以让客户机的压力大大减轻，工作的负荷被合理的分配了。

![](/md/blog.002.png)

图2-1  B/S模式三层结构图
## 2.3MYSQL数据库
Mysql现隶属于Oracle公司，之前隶属于SUN公司，却是MySQL AB公司研发出来的数据库[5]。

MySQL数据库是一种开源的关系行数据库操作系统其使用的SQL语言是用来访问数据库较为标准的常用数据库操作语言。而且MySQL数据库体积较小易于安装、运行速度较快、所花费的成本较低搭载超文本预处理器接口与web服务器软件或服务可以组成良好的开发环境。

Mysql是当今最为热门的数据库之一，它是用于WEB应用程序的最佳RDBMS（关系数据库管理系统）应用程序。Mysql所使用的语言也是访问数据库最常用的语言，而且体积较小，速度较快，并且成本较低，所以本系统选择Mysql作为系统的数据库，许多中小型的网站一般都是选择Mysql作为网站的数据库。Mysql的数据库是存放在表中的，所以它的速度较快，而且也较为的灵活。MySQL操作起来十分简便，因为MySQL不是讲所有的数据堆放在一起，这样数据量大，查找起来需要的时间很多。它是将数据保存在不同的表中，这些表具有关联性，查找时直接从表中获取数据，这样大大提高了查找的速度。且MySQL是免费的，这对于大多数研发人员来说，是极大的诱惑。MySQL可以使用标准的sql数据语句，使用起来简单方便。
## 2.4 Springboot框架
Spring Boot是一个简化程序设置的拥有开箱即用的框架，它主要的优点是根据程序员不同的设置而生成不同的代码配置文件，这样开发人员就不用每个项目都配置相同的文件，从而减低了开发人员对于传统配置文件的时间，提高了开发效率。它内嵌Tomcat服务器，简化了Maven的配置，自动配置Spring，通过这样的框架，开发人员就不用头疼各种配置文件，可以减少时间，同时提高了代码的整体性，使开发人员工作效率大大提高。




# 3 系统分析
## 3.1可行性分析
在进行可行性分析时，我们通常根据软件工程里方法，通过四个方面来进行分析，分别是技术、经济、操作和法律可行性。因此，在基于对目标系统的基本调查和研究后，对提出的基本方案进行可行性分析。
### 3.1.1技术可行性
技术可行性是指学习的技术是否能够完成本项目，如果团队本身没有相关的技术储备，而又能够迅速掌握此类技术，那项目应该达不到我们的设计要求。本教学资源库系统的设计与实现采用Java技术和MYSQL数据库进行开发设计，作为计算机专业学生，在学校期间就接触到许多关于编程方面的知识，当然也包括各种编程软件，对他们的了解度也比较系统，所以技术开发上面还是有一定把握。
### 3.1.2操作可行性
本系统操作页面简洁明了，操作极其容易，用户登陆后一眼便可看到自己所需要的信息，而管理员的操作也十分轻松便捷，只要操作人员具有一定的文字水平以及简单的逻辑思维，就可以轻松操作本系统，因此本系统在操作上是可行的。
### 3.1.3经济可行性
该系统的开发工具使用的都是免费的开发工具，且内容较为简单，一台计算机便可以开发出这个系统，且后期的维护，修改等对本系统的改动，都可以只通过一台计算机实现，因此开发该系统的成本在有计算机的情况下基本为0，所以本系统在经济上是可行的。
### 3.1.4法律可行性
本教学资源库系统的设计与实现开发的所有技术资料都为合法，知识产权问题不会发生在开发过程中，而且没有抄袭其他相关系统，不会有侵犯版权的问题。所以在开发过程中不会涉及法律责任。

通过以上可行性分析得知，可以利用现有的技术和合理的成本开发出本网站，并且能够在遵守相关法律的基础上运行该系统。
## 3.2系统性能分析
（1）完整性分析

要求各种信息记录的完整性，内容不能为空，各种数据间联系应保持正确性，且相同的数据在不同记录中的一致性。

（2）系统运行速度分析

页面响应时问应该在3秒以内，最长不能超过4秒。

（3）界面分析

系统界面要求简单明了，容易操作，符合用户操作习惯。

（4）安全性分析

要充分保证系统的安全性、稳定性。要想对系统进行管理，必须经过正确的账号密码进行登录，否则无权进行管理。在具体实现中对不同的权限进行设定，不同权限的用户在系统中登陆后，不可以越级操作。
## 3.3系统功能分析
此教学资源库系统的设计与实现功能分析主要分为管理员功能模块、教师功能模块和学生功能模块三大模块，下面详细介绍这三大模块的主要功能：

（1）管理员：管理员登陆后可对系统进行全面管理，管理员主要功能模块包括个人中心、教师管理、学生管理、课程信息管理、课程作业管理、学生选课管理、学生作业管理、学生成绩管理、系统管理，管理员实现了对系统信息的查看、添加、修改和删除的功能。管理员用例图如图3-1所示。

![](/md/blog.003.png)

图3-1 管理员用例图

（2）学生：学生进入本教学资源库系统的设计与实现前台可查看系统信息，包括首页、课程信息、课程作业、试卷列表、公告信息等，注册登录后主要功能模块包括个人中心、考试记录、错题本、学生选课管理、学生作业管理、学生成绩管理和我的收藏管理。

![](/md/blog.004.png)

图3-2 学生用例图

（3）教师：教师注册登录后主要实现的功能模块包括个人中心、课程信息管理、课程作业管理、学生选课管理、学生作业管理、学生成绩管理、试卷管理、试题管理、考试管理。

![](/md/blog.005.png)

图3-3 教师用例图
## 3.4系统流程分析
### 3.4.1注册流程
未有账号的学生和教师均可进行注册操作，在注册时系统首先判断账号是否存在，存在则提示账号已存在，不存在则判断输入的信息是否合法，合法则在数据库添加注册信息，注册成功，反之注册失败，注册流程如图3-4所示。

![](/md/blog.006.png)

图3-4  用户注册流程图
### 3.4.2登录流程
登录模块主要满足了学生、教师以及管理员的权限登录，学生登录流程图如图3-5所示。

![](/md/blog.007.png)

图 3-5 学生登录流程图
### 3.4.3添加信息流程
管理员、教师和学生登录后均可进行信息的添加操作，添加信息流程图如图3-6所示。

![](/md/blog.008.png)

图3-6添加信息流程图



# 4 系统设计
## 4.1系统概要设计
教学资源库系统的设计与实现主要分为管理员、教师和学生三个角色，系统采用B/S结构(Browser/Server,浏览器/服务器结构)和基于Web服务两种模式，是一个适用于Internet环境下的模型结构。只要用户能连上Internet，便可以在任何时间、任何地点使用。系统工作原理图如图4-1所示：

![](/md/blog.009.png)

图4-1 系统工作原理图
## 4.2系统结构设计
系统架构的整体设计是一个将一个庞大的任务细分为多个小的任务的过程，这些小的任务分段完成后，组合在一起形成一个完整的任务。本教学资源库系统的设计与实现主要包括学生功能模块、教师功能模块和管理员功能模块三大部分，系统结构设计如图4-2所示。

![](/md/blog.010.png)

图4-2系统结构图
## 4.3 系统顺序图
（1）登陆顺序图

用户在登录时，首先进入系统登录窗口，用户需要输入用户名和密码，点击登录按钮进行登录操作，系统会以用户名和密码为参数在数据库中进行登录信息的验证，验证成功则登录成功，进入用户主界面。登录模块顺序图如图4-3所示。

![](/md/blog.011.png)

图4-3 登录顺序图

（2）注册顺序图

未有账号的用户可进入注册界面进行注册操作，在注册界面输入注册信息，点击提交按钮，系统首先判断用户名是否存在，存在则提示重新输入，不存在则验证注册信息是否正确，正确则在数据库中添加注册数据，提示注册成功。用户注册模块顺序图如图4-4所示。

![](/md/blog.012.png)

图4-4 注册顺序图

（3）修改密码顺序图

用户登录后可进入修改密码界面进行修改密码操作，在修改密码时，需要输入原始密码和新密码，系统会在数据库中进行原密码的验证，原密码正确则在数据库中添加修改数据，修改成功。修改密码顺序图如图4-5所示。

![](/md/blog.013.png)

图4-5 修改密码顺序图
## 4.4数据库设计
### 4.4.1 数据库实体（E-R图）
E-R图是一种描述显示数据类型间的关系的数据描述方法，E-R图可以完整地映射出现实模型的关系。

实体联系模型反映出来的是现实世界中实体的相互间关联的关系，是用来在数据库设计过程中表示数据库系统结构的方法。它的思想是使用现有的数据模型来表现出目前项目实体间所具有的现实关联。E-R图是可以表示实体间相互关联的意义，直观反映出实体间的关联。

在为实体设计属性与关联的时候便可以确定实体间主外键的关联关系，实体所具有的延伸性。在E-R图中这些都能直观的显示出来。像这样将数据分类成组后，就会产生了与相关的分组所不同的信心，这样更加的易于用户进行观察和实际分析。本教学资源库系统的设计与实现的E-R图如下所示：

（1）试卷实体属性E-R图如图4-6所示。

![](/md/blog.014.png)

图4-6  试卷实体属性E-R图

（2）试题实体属性E-R图如图4-7所示。

![](/md/blog.015.png)

图4-7 试题实体属性E-R图

（3）管理员实体属性E-R图如图4-8所示。

![](/md/blog.016.png)

图4-8  管理员实体属性E-R图

（4）教师实体属性E-R图如图4-9所示。

![](/md/blog.017.png)

图4-9   教师实体属性E-R图

（5）学生实体属性E-R图如图4-10所示。

![](/md/blog.018.png)

图4-10 学生实体属性E-R图
### 4.4.2 数据库表设计
本教学资源库系统的设计与实现采用了MYSQL数据库管理系统，各个表的设计结果如下：

表4-1  exampaper试卷信息表

|字段名|数据类型|是否允许空|字段含义|
| :-: | :-: | :-: | :-: |
|id|bigint(20)|NOT NULL|编号|
|addtime|timestamp|NULL|添加时间|
|name|varchar(200)|NULL|试卷名称|
|time|int(11)|NULL|考试时长|
|status|int(11)|NULL|试卷状态|

表4-2  examquestion试题信息表

|字段名|数据类型|是否允许空|字段含义|
| :-: | :-: | :-: | :-: |
|id|bigint(20)|NOT NULL|编号|
|addtime|timestamp|NULL|添加时间|
|paperid|bigint(20)|NULL|试卷编号|
|papername|varchar(200)|NULL|试卷名称|
|questionname`|varchar(200)|NULL|试题名称|
|options|longtext|NULL|选项|
|score|bigint(20)|NULL|分值|
|answer|varchar(200)|NULL|正确答案|
|analysis|longtext|NULL|答案解析|
|type|bigint(20)|NULL|试题类型|
|sequence|bigint(20)|NULL|试题排序|

表4-3  users管理员信息表

|字段名|数据类型|是否允许空|字段含义|
| :-: | :-: | :-: | :-: |
|id|bigint(20)|NOT NULL|编号|
|username|varchar(100)|NULL|用户名|
|password|varchar(100)|NULL|密码|
|role|varchar(100)|NULL|角色|
|addtime|timestamp|NULL|添加时间|

表4-4  jiaoshi教师信息表

|字段名|数据类型|是否允许空|字段含义|
| :-: | :-: | :-: | :-: |
|id|bigint(20)|NOT NULL|编号|
|addtime|timestamp|NULL|添加时间|
|jiaoshigonghao|varchar(200)|NULL|教师工号|
|mima|varchar(200)|NULL|密码|
|jiaoshixingming|varchar(200)|NULL|教师姓名|
|`xingbie|varchar(200)|NULL|性别|
|zhaopian|varchar(200)|NULL|照片|
|zhicheng|varchar(200)|NULL|职称|
|lianxidianhua|varchar(200)|NULL|联系电话|
|jiaoshiyouxiang|varchar(200)|NULL|教师邮箱|

表4-5   xuesheng学生信息表

|字段名|数据类型|是否允许空|字段含义|
| :-: | :-: | :-: | :-: |
|id|bigint(20)|NOT NULL|编号|
|addtime|timestamp|NULL|添加时间|
|xuehao|varchar(200)|NULL|学号|
|mima|varchar(200)|NULL|密码|
|xueshengxingming|varchar(200)|NULL|学生姓名|
|xingbie|varchar(200)|NULL|性别|
|touxiang|int(11)|NULL|头像|
|shouji|varchar(200)|NULL|手机|
|banji|varchar(200)|NULL|班级|
|youxiang|varchar(200)|NULL|邮箱|



# 5 系统的实现
## 5.1学生功能模块的实现
学生进入本系统可查看系统信息，系统主界面展示如图5-1所示。

![](/md/blog.019.png)

图5-1系统主界面图
### 5.1.1 学生注册界面
没有账号的学生可进行注册操作，学生注册界面展示如图5-2所示。

![](/md/blog.020.png)

图5-2 学生注册界面图
### 5.1.2 课程详情信息界面
学生可选择课程信息查看详情，登录后可进行选课、收藏等操作，课程详情界面展示如图5-3所示。

![](/md/blog.021.png)

图5-3   课程详情界面图
### 5.1.3 试卷列表界面
学生在试卷列表界面可查看所有试卷，并可选择考试，试卷列表界面展示如图5-4所示，考试界面展示如图5-5所示。

![](/md/blog.022.png)

图5-4 试卷列表界面图

![](/md/blog.023.png)

图5-5  考试界面图
### 5.1.4 课程作业界面
学生可查看课程作业信息，登录后可提交作业，课程作业界面展示如图5-6所示。

![](/md/blog.024.png)

图5-6  课程作业界面图
## 5.2管理员功能模块的实现
### 5.2.1 管理员登录界面
管理员要想进入后台进行管理操作，必须登录系统后台，管理员登录界面展示如图5-7所示。

![](/md/blog.025.png)

图5-7 管理员登录界面图
### 5.2.2 学生管理界面
管理在学生管理界面可查看所有学生信息，并可对其进行修改和删除操作，学生管理界面展示如图5-8所示。

![](/md/blog.026.png)

图5-8 学生管理界面图
### 5.2.3 教师管理界面
管理员可增删改查教师信息，教师管理界面展示如图5-9所示。

![](/md/blog.027.png)

图5-9 教师管理界面图
### 5.2.4 学生成绩管理界面
管理员可管理学生成绩信息，学生成绩管理界面如图5-10所示。

![](/md/blog.028.png)

图5-10  学生成绩管理界面图
## 5.3教师功能模块的实现
### 5.3.1 教师注册界面
没有账号的教师可进行注册操作，教师注册界面展示如图5-11所示。

![](/md/blog.029.png)

图5-11 教师注册界面图
### 5.3.2 课程信息管理界面
教师可增删改查课程信息，并可添加作业和查看评论，课程信息管理界面展示如图5-12所示。

![](/md/blog.030.png)

图5-12 课程信息管理界面图
### 5.3.3 添加作业界面
教师可添加课程作业信息，添加作业界面展示如图5-13所示。

![](/md/blog.031.png)

图5-13  添加作业界面图
### 5.3.4 学生选课管理界面
教师可查看学生选课信息，并可进行审核操作，学生选课管理界面展示如图5-14所示。

![](/md/blog.032.png)

图5-14 学生选课管理界面图
### 5.3.5 试题管理界面
教师可增删改查试题信息，试题管理界面展示如图5-15所示。

![](/md/blog.033.png)

图5-15 试题管理界面图



# 系统










