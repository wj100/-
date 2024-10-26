[下载pdf简历](https://raw.githubusercontent.com/wj100/resume/gh-pages/汪骏（前端）.pdf)

## 个人资料

* 个人信息：汪骏  /  男  /  29岁  /  19937785238  /  本科
* 邮 箱：<mail@wangjun.work>
* github：[github.com/wj100](http://github.com/wj100){:target="_blank"}
* 博 客：[csdn.wangjun.work](http://csdn.wangjun.work){:target="_blank"}

## 专业技能

* 掌握 Javascript, Vue, React, Node, 小程序

## 工作经历

* 2021.05-至今&emsp;&emsp;&emsp;网易（杭州）网络有限公司（外包）
* 2020.08至2021.05&emsp;杭州柯莱特科技股份有限公司
* 2019.06至2020.08&emsp;南京英斯特信息科技有限公司

## 项目经历

### 网易企业邮箱业务

* __主要技术__  
    AngularJs + Vue2 + React + Node
* __项目描述__  
    **参与**维护网易企业邮箱产品线，包含官网，webmail，小程序，邮箱管理后台，对接个人邮、邮箱大师等项目。  
    **独⽴设计**实现搭建企微，飞书，钉钉第三方办公平台⼩程序研发产品化⽅案，包括平台登录授权、发布迭代流程化管控等，解决开发、测试、发布各个阶段的沟通协作问题，研发测试体感提升明显。  
    **负责**邮箱管理后台（AngularJs）业务迭代，期间实现企业年终报告，英文版，邮箱全产品明水印等功能。  
    **负责**wework管理平台（React + antd pro）业务迭代，该系统供部门技术，售前售后，销售，实施人员使用，涵盖邮箱产品运维系统、查询系统、直邮系统、团队管理、客群系统等。
    难点：各系统业务关联性强，与 163 邮箱对接场景复杂，涉及大量登录，授权，cookie，重定向等技术
    

### 网易云工厂

* __主要技术__  
    React + Vue2
* __项目描述__  
    支撑部门外贸业务探索开发 官网+供应链管理系统。独立完成项目技术选型及开发部署。  
    官网使用 React + 预渲染 + TailwindCSS实现。为保证海外用户访问速度，进行测试优化。包括使用 node 实现静态资源的 cdn上传替换，对 webpack进行打包优化([方案调研](https://blog.csdn.net/qq_44472722/article/details/142899417?sharetype=blogdetail&sharerId=142899417&sharerefer=PC&sharesource=qq_44472722&spm=1011.2480.3001.8118))。  
    供应链管理系统在开源项目 [vue-element-admin](https://github.com/PanJiaChen/vue-element-admin)上进行开发，修改了部分角色权限。主要实现对产品业务线，供应商，业务员，客户，订单流转状态的管理。

### 气象大数据治理中心

* __主要技术__  
    Vue2 + Echarts + 天地图
* __项目描述__
    该项目下分多个子系统，供气象管理单位使用。我主要负责数据可视化监控页面，对地图坐标，覆盖物的操作，通过大量表单创建站点格点信息，选择城市获取经纬度，可拖拽的折线图与柱形图，可同步可编辑的表格等功能模块。
* __技术实现__  
    使用echarts及数字滚动插件开发可视化监控页面，调用天地图相关api对地图进行点选圈选框选获取经纬度，使用element表单表格等组件创建资源信息，运用相关插件实现省市区地域的选择，树形结构的展开合并，禁用原生鼠标右击菜单并生成系统所需菜单，运用echarts库及相关算法实现可拖拽改变的折线图柱形图。

### 某单位建设管理平台

* __主要技术__
    JQuery+Vue+ECharts+WebGis
* __项目描述__
    该项目为数据可视化建设管理平台、运用内部开发的 gis 地图结合 ECharts 进行数据展示与切换，通过地图的悬浮、点击等事件绘制各类地图覆盖物，并与 ECharts 数
据产生联动。实现人员，单位的搜索匹配，并生成人员画像。实现选择部门与地图，图表的数据联动。通过输入参数动态生成各类问题的解决方案。
* __技术实现__
运用 jQuery+js 制作各级导航，使用 Vue 的各类 v-指令完成搜索，列表渲染等功能。使用大量 ECharts 图表开发可视化大屏页面。运用地图的各类事件，layer开发页面特效

### 数据运营平台

* __主要技术__
    Vue-cli + Vuex + Vue-router + Axios + Element-ui
* __项目描述__
由 Admin/Publisher 进行资源发布，User 进行订阅，使用。包括资源的发布，发布待审批，订阅，订阅待审批，资源的激活，评论等流程。管理员通过监控页面对资源的各类状态进行监控管理，通过系统设置功能实现对部门，人员的权限管理。
* __技术实现__
第⼀次单独负责的⼀个项⽬，采⽤成熟的Vue中后台技术栈，从Vue新⼿开始逐步完成相应的需求和⼯作，并研读学习Vue源码，理解其实现原理。
项目整体使用 Element-ui 作为样式框架，css 预编译语言为 less。通过 Axios拦截器与全局路由导航守卫进行登录验证，通过动态路由表对不同用户进行权限控制，使用minxis 抽离可复用方法及数据。解决了 Vue 项目打包后的样式冲突，刷新丢失页面，通过定义全局变量更改后台接口路径等问题。

### 个人博客

* __主要技术__  
    Vue2 + Node + Express + Mysql + pm2
* __项目描述__  
    该项目为方便个人工作学习记录笔记所开发，实现了文章的发布，分类，搜索，评论等功能。 从需求分析到数据库表设计，前后端开发，部署上线均为个人独立完成，博客功能不是很复杂，但是让我对前后端分离开发，Vue的组件化思想，Node对数据库的操控，项目的整个生命周期等方面都有了更好的认识。
* __技术实现__  
    使用Vue全家桶进行前端部分的开发，后端运用node及express框架实现对数据库的增删改查，后期使用koa重写了一次。前端使用nginx部署，后端使用pm2实现进程守护。

## 开源

<table>
  <thead align="center">
      <tr>
        <td><b>🎁 项目</b></td>
        <td><b>⏬ 下载量</b></td>
        <td><b>💬 备注</b></td>
     </tr>
  </thead>
  <tbody>
    <tr>
      <td style="width:180px"><a href="https://www.npmjs.com/package/paging-pdf"><b>paging-pdf</b></a></td>
      <td><img alt="Stars" src="https://img.shields.io/npm/dt/paging-pdf.svg"/></td>
      <td>企业邮箱年终报告沉淀下来的pdf分页下载工具</td>
    </tr>
    <tr>
      <td style="width:180px"><a href="https://www.npmjs.com/package/vue-year-picker"><b>vue-year-picker</b></a></td>
      <td><img alt="Stars" src="https://img.shields.io/npm/dt/vue-year-picker.svg"/></td>
      <td>基于vue2的仿ant风格年份选择组件</td>
    </tr>
    <tr>
      <td style="width:180px"><a href="https://www.npmjs.com/package/auto-size-echart"><b>auto-size-echart</b></a></td>
      <td><img alt="Stars" src="https://img.shields.io/npm/dt/auto-size-echart.svg"/></td>
      <td>响应式Echarts解决方案</td>
    </tr>
    <tr>
      <td style="width:180px"><a href="https://www.npmjs.com/package/watermark-pub"><b>watermark-pub</b></a></td>
      <td><img alt="Stars" src="https://img.shields.io/npm/dt/watermark-pub.svg"/></td>
      <td>前端明水印</td>
    </tr>
  </tbody>
</table>
