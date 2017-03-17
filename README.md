<h1>常用的shields图标详解</h1>


<p align="center" style='font-size: 26px; border-bottom: 1px solid #ccc; padding-bottom: 6px;'>WHAT</p>


什么是shields？ 不知道大家在github、npm上肆意的浏览代码、使用工具的时候，有没有注意到这样的小图标： <br />
![npm][npm] ![node][node] ![travis][travis]<br />
这些小图标都是用来做什么的呢？ 简单的来说，这些小图标，更像是一枚徽章（Badge），显而易见的标明了该项目当前的某些状态，以下统称为badge。

<p align="center" style='font-size: 26px; border-bottom: 1px solid #ccc; padding-bottom: 6px;'>DETAILS</p>

### Make
每个badge都有一个制作的标准，如下图所示，他基本遵循了去除不必要的文本、减少水平长度（如果可以）的基本原则，使他们看起来一目了然。

![proportions][proportions]

同时安利一个在线制作badge的[网址](http://shields.io/)，亲测好用到不行~

### Status
一个标准的badge通常主要包含了两部分，左侧的状态文字（通常以较深色系的灰色、黑色作为背景色）以及右侧的状态信息（通常以除灰色、黑色等深色系作为背景色），同时无论状态文字或者状态信息都应尽量保持简洁，可以达到一目了然的目的。

以下举例作为参考：
- test build status: build | failing
- code coverage percentage: coverage | 80%
- status of third-party dependencies: dependencies | out-of-date

### Color
标准badge同样的状态会有不用的颜色，不同的颜色会反馈出不同的信息，比如：<br />
① ![npm][npm]    ②![npm][npm1]<br />
badge ①和②均表示该项目在npm的版本，而不同的颜色使人一眼就能区分出，哪个是正式版（badge①）哪个是非正式版（badge②）；通常以计算机三基色（RGB）作为背景色的状态表示确定的、严谨的，反之表示有缺陷的、不能完全确定的。

### Examples
以下举例常用的badges

<table>
  <tr>
    <td>
        <a href="https://www.npmjs.com/" target="_blank"><img src="https://img.shields.io/badge/npm-1.0.0-blue.svg" alt="npm"></a>
    </td>
    <td>项目所在npm的版本</td>
  </tr>
  <tr>
    <td><a href="https://www.npmjs.com/" target="_blank"><img src="https://img.shields.io/badge/npm-0.3.3-orange.svg" alt="npm"></a></td>
    <td> 以除计算机基色（RBG）颜色作为背景颜色（通常为orange）表示该项目目前还不是正式版</td>
  </tr>
  <tr>
    <td>
        <a href="https://www.npmjs.com/" target="_blank"><img src="https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg" alt="dependencies-up-to-date"></a>
    </td>
    <td>项目的依赖情况</td>
  </tr>
  <tr>
    <td><a href="https://david-dm.org/" target="_blank"><img src="https://img.shields.io/badge/dependencies-up%20to%20date-yellow.svg" alt="dependencies-up-to-date"></a></td>
    <td> 少部分依赖不是最新版本</td>
  </tr>
  <tr>
    <td><a href="https://david-dm.org/" target="_blank"><img src="https://img.shields.io/badge/dependencies-out%20of%20date-red.svg" alt="dependencies-up-to-date"></a></td>
    <td> 至少有一半或者一半以上不是最新的依赖</td>
  </tr>
  <tr>
    <td><a href="https://david-dm.org/" target="_blank"><img src="https://img.shields.io/badge/build-passing-brightgreen.svg" alt="dependencies-up-to-date"></a></td>
    <td> 可持续集成</td>
  </tr>
  <tr>
    <td><a href="https://david-dm.org/" target="_blank"><img src="https://img.shields.io/badge/coverage-94%25-green.svg" alt="dependencies-up-to-date"></a></td>
    <td> 代码覆盖率</td>
  </tr>
  <tr>
    <td><a href="https://david-dm.org/" target="_blank"><img src="https://img.shields.io/badge/chat-on%20gitter-50ba9b.svg" alt="dependencies-up-to-date"></a></td>
    <td> 交流社区</td>
  </tr>
</table>

<p align="center" style='font-size: 26px; border-bottom: 1px solid #ccc; padding-bottom: 6px;'>OTHERS</p>

### Analysis
- 持续集成
    > 持续集指的是，频繁的（一天多次）将代码继承到主干。他的目的就是让产品可以快速迭代，同时还能保持高质量<br />一个自动化的可持续集成网站：[https://travis-ci.org](https://travis-ci.org/)<br />更多关于可持续集成的介绍你可以 [点击这里](http://www.ruanyifeng.com/blog/2015/09/continuous-integration.html)

- 项目依赖检测
    > [在这里](https://david-dm.org/) 你可以检测项目依赖情况

- 代码覆盖率
    > 通常指在运行测试用例后，一共走过了多少句代码，用走过的这个代码除以测试对象的代码行数，就是这次测试的代码覆盖率了。<br />更多关于代码覆盖率的解释你可以参考这里：[http://www.cnblogs.com](http://www.cnblogs.com/coderzh/archive/2009/03/29/1424344.html) ; [http://baike.baidu.com](http://baike.baidu.com/link?url=PjlIgIEA_Sl4FmxkKvDQ7_2C_1Wc2uaUZqDL7RCee8PIB4TMNZV085WY1fCjYvJTnEH3z7Ci0IEFdf00DW7sLAPx5YBmfjeP2y-DBbQIORKrDy9-N6_nziETkzDDLRN2TDyl8C_DGUQMOcKmW03ar_)

### Warn
- 本例中所有的badge均为展示作用，并无实际意义。
- 更多关于shields的介绍你可以 [访问这里](https://github.com/badges/shields)




[npm]: https://img.shields.io/badge/npm-1.0.0-blue.svg
[npm1]: https://img.shields.io/badge/npm-0.3.3-orange.svg
[node]: https://img.shields.io/badge/node-4.0.0-brightgreen.svg
[travis]: https://img.shields.io/badge/build-passing-brightgreen.svg
[proportions]: https://raw.githubusercontent.com/badges/shields/master/spec/proportions.png
