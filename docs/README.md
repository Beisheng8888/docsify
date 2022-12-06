## 🎁readme

<p align="center">
	<a href="https://hutool.cn/"><img src="http://www.anqi520.com/upload/2022/12/beishengtouxiang-6b4a369e86184cb190bc7d46aca0633f.jpg" width="20%"></a>
</p>
<p align="center">
	<strong>🍬甜品级Java开发文档.</strong>
</p>
<p align="center">
	👉 <a href="http://anqi520.com:3000">http://anqi520.com:3000</a> 👈
</p>

<p align="center">
	<a target="_blank" href="https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html">
		<img src="https://img.shields.io/badge/JDK-8+-green.svg" />
	</a>
	<a target="_blank" href='https://github.com/Beisheng8888/docsify'>
		<img src="https://img.shields.io/github/stars/Beisheng8888/docsify.svg?style=social" alt="github star"/>
	</a>
</p>
<br/>

-------------------------------------------------------------------------------

## 💖简介

> 💯 书到用时方恨少。使用docsify框架，把之前的笔记整理了一下，没事的时候看看，不要成文温水中的青蛙，对初学者来说非常友好，希望也能帮助到其他人。

### 💥如何改变我们的coding方式

以Nacos为例：

- 👴【以前】打开搜索引擎 -> 搜“Nacos” -> 打开某篇博客-> 复制粘贴 -> 改改好用
- 👦【现在】打开北省的文档 ->搜“Nacos”-> 复制粘贴-> 改改好用(好像也很鸡肋😂)

北省的Java开发文档存在就是为了减少代码搜索成本，避免网络上参差不齐的代码出现导致的bug。

-------------------------------------------------------------------------------

## 🥗包含目录

| 模块           | 介绍                                                                |
|--------------|-------------------------------------------------------------------|
| JavaSE       | 继承、内部类和Lambda表达式、常用API、集合、红黑树、可变参数、IO流、多线程.....                   |
| JavaWeb      | Mysql、JDBC、Maven、MyBatis、HTML、CSS、JS、HTTP、Tomcat、Servlet、JSP..... |
| 基础框架         | Maven高级、Spring、SpringMVC、SpringBoot、MyBatisPlus                   |
| 基础微服务        | SpringCloud、Docker、RabbitMQ                                       |
| 高级微服务        | 微服务保护、分布式事务、分布式缓存、RabbitMQ-高级篇                                    |
| 扩展           | Git、Nacos、Linux、Redis、MongoDB、Kafka、Xx-Job、ES                     |
| 面试专题    | 基础篇、并发篇、虚拟机篇、框架篇                                                     |

-------------------------------------------------------------------------------

## 📝文档

[📘中文文档](http://anqi520.com:3000/#/)

[📘中文备用文档](http://anqi520.com:3000/#/)

[📙参考API](http://anqi520.com:3000/#/)

-------------------------------------------------------------------------------

## 🚁安装

本地运行
> npm run bootstrap && npm run dev

Linux部署
> npm run bootstrap

> nohup npm run dev </dev/null > scriptresults.log 2> scripterror.log & exit


-------------------------------------------------------------------------------

## 🪙支持北省

### 💳捐赠

如果你觉得文档不错，可以捐赠请维护者吃包辣条~，在此表示感谢^_^。

<div align="center">
<img src="http://www.anqi520.com/upload/2022/12/weiPlay-e8a94018c94e458c8c13a59a606d6997.jpg" height="300">
<img src="http://www.anqi520.com/upload/2022/12/ZFBPlay-ff899b238bda4b508adbb1c3d4af4724.jpg" height="300">
</div>


-------------------------------------------------------------------------------

## 🏗️添砖加瓦

### 🎋分支说明

文档的源码分为两个分支，功能如下：

| 分支      | 作用                                                          |
|---------|---------------------------------------------------------------|
| V1.0    | 主分支，release版本使用的分支，与中央库提交的jar一致，不接收任何pr或修改 |
| develop | 开发分支，默认为下个版本的SNAPSHOT版本，接受修改或pr                 |

### 🐞提供bug反馈或建议

提交问题反馈请说明正在使用的JDK版本呢、文档版本和相关依赖库版本。

[//]: # (- [Gitee issue]&#40;https://gitee.com/dromara/hutool/issues&#41;)

- [Github issue](https://github.com/Beisheng8888/docsify/issues)

### 🧬贡献代码的步骤

欢迎任何人为文档添砖加瓦，贡献代码

1. 在Gitee或者Github上fork项目到自己的repo
2. 把fork过去的项目也就是你的项目clone到你的本地
3. 修改代码（记得一定要修改develop分支）
4. commit后push到自己的库（develop分支）
5. 登录Gitee或Github在你首页可以看到一个 pull request 按钮，点击它，填写一些说明信息，然后提交即可。
6. 等待维护者合并

-------------------------------------------------------------------------------

## ⭐Star

[![Stargazers over time](https://starchart.cc/Beisheng8888/docsify.svg)](https://starchart.cc/Beisheng8888/docsify)

## 📌 联系我

<div align="center">
<img src="http://www.anqi520.com/upload/2022/12/wecat-a2ea8a9a4f804d63807bd94afe8b85ba.jpg" height="350">
</div>

## 🌈 主题选择

<div class="demo-theme-preview" >
  <a data-theme="theme-simple">simple</a>
  <a data-theme="theme-simple-dark">simple-dark</a>
  <a data-theme="vue">vue</a>
  <a data-theme="buble">buble</a>
  <a data-theme="dark">dark</a>
  <a data-theme="pure">pure</a>
</div>


<style>
  .demo-theme-preview a {
    padding-right: 10px;
  }

  .demo-theme-preview a:hover {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
  var preview = Docsify.dom.find('.demo-theme-preview');
  var themes = Docsify.dom.findAll('[rel="stylesheet"]');

  preview.onclick = function (e) {
    var title = e.target.getAttribute('data-theme');

    themes.forEach(function (theme) {
      theme.disabled = theme.title !== title;
    });
  };
</script>
