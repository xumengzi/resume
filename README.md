## 基本信息

姓名：许孟&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;性别：男  

电话：13260690736&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;邮箱：xumeng@xumeng.life 

学校：西安石油大学&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;专业：网络工程

工作年限：8年&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;个人博客：http://xumeng.life/

## 个人优势
1、擅长html(5)，擅长css(3) 以及相关扩展语言

2、深入理解 Javascript 语言，对JS运行机制等底层有比较深入了解

3、熟悉 Vue，小程序 等框架及其原理，熟悉 Typescript，能熟练运用开发项目

4、熟悉 Webpack 等前端工程化工具，能编写自定义 plugin 或 loader 来实现特定功能

5、了解 Nodejs，数据库等，可通过 Nodejs 开发后台 api 服务，也可开发一些 CLI 工具，为团队提供便利的小工具

6、承担团队技术项目攻坚工作，注重前端标准化，热爱互联网，对互联网技术有着非常浓厚的兴趣, 对用户体验, 数据埋点以及错误统计有独特的见解

## 工作经历

2020.12--now&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;美团三快&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前端开发工程师
2019.07--2020.11&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;深圳丰巢-武汉分公司&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前端开发工程师  
2018.04--2019.06&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;人人网-武汉分公司&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前端开发工程师  
2015.03--2017.11&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;同程网络&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;前端开发工程师

## 项目经验

### 美团优选商家端小程序

**项目简介：**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;作为一个业务复杂，功能多，用户多，DAU超百万的小程序。项目配置，组织结构，代码开发方式等就显得非常重要。

**项目角色：** 核心维护者

**项目经验：** 
1. 小程序采用分包的模式，每个业务方负责一个单独的分包，最后集成到主包里。22年主导了小程序分包总和升级30M的工作，包括前期沟通了解30M的前置要求，然后撰写升级SOP文档，集中测试，上线。最后总包成功升级到30M，并无线上问题爆出。
2. 小程序核心列表（列表分成3个列表，用tab来切换）卡顿问题排查以及优化。作为使用量最多的页面，这个页面功能多，复杂。项目运行到22年低已经出现首屏加载时间一度到5-8s的情况。经过仔细调研排查之后，制定了详细的解决方案。核心方案有：
    1. 列表懒加载（之前进入第一个tab也会加载第二个tab数据）；
    2. 列表加载数据缓存（已加载的列表不在重复加载，记住滚动距离等）；
    3. 部分节点延迟加载（日历筛选项节点延迟渲染，一部分放再点击打开日历事件里渲染）；
    4. 降低setdata次数（从最开始200+，降低到50以下）。

经过一系列运营之后，现在首屏时间约1-3s。对比之前和商家的手机型号等，判定这次优化有效果，后续运营，商家，产品也反馈列表页快了许多

### 美团优选&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;用户信息采集SDK

**项目描述：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;通过无侵入的埋点，定向采集用户在PC端操作过程中的数据，如进入页面PV，页面某模块展示MV，点击按钮MC，发送请求RQ，页面跳转LK等。根据采集到的数据，配置用户的关键动作链路监控，实现关键动作中断时的实时报警。

**项目角色：** owner

**项目成果：**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;优选商品终端共有10个重要项目接入该SDK，通过给关键步骤，行为增加埋点sdk，可以有效发现，提前知道项目是否出错。也给了一些重点资源，请求增加了监控，能够第一时间发现问题，通过大象，电话告知开发。
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;项目运行至今近2年，每天累计监控线上用户几百个关键动作，累计发现十多次由于代码不健壮导致的用户行为中断。

## 个人总结
本人自制力强，有较强的自学能力，也敢于尝试新的知识，会持续不断学习来确保自己不被行业所落下。
闲暇之际会看一些框架的源码，吸收别人写的比较好的点，然后运用到自己代码中