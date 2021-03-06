---
title: 面试当中的非技术问题
tags:
  - 极客时间
  - 面试
categories:
  - 学习笔记
date: 2021-03-28 15:23:21
updated: 2021-03-28 15:23:21
---

这篇文章是关于极客时间 [面试现场](https://time.geekbang.org/column/intro/100023401) 的学习笔记，现结合自身经历，把课程内容总结归纳为两部分：一部分以“问与答”的形式应对面试当中可能遇到的非技术问题；另一部分则阐述相关策略，让面试官能够更好地了解自己。

## 问与答

Q<sub>0</sub>: **请自我介绍一下吧**
A<sub>0</sub>: 面试官你好！诶。我叫xxx，20年7月xxx大学硕士毕业，本硕都是学的计算机专业。硕士阶段研究的是计算机视觉，并且有一篇xxx区的期刊论文。硕士毕业后，我跟随我的实验室同学，来到xxx，作为一名前端工程师。入职后，我首先接到的任务是编写一个自动换xxx海报的Python脚本程序，...
Tips: 1) 个人信息、主要经历（即能力发展路径、成果）、经验和技能；
2) 产生好感（即内容充实可信，并根据面试官的反应来调整）；
3) 记住我（即有细节的亮点）。

Q<sub>1</sub>: **你为什么选择前端呢**
A<sub>1</sub>: 前端社区比较活跃，很多优秀的开源项目；喜欢JavaScript，横跨PC、移动设备、小程序的GUI平台；nodejs开发效率高并且性能不错。
Q<sub>1+</sub>: 为什么不做算法呢
A<sub>1+</sub>: 我想无论做什么，都需要扎实的基础知识和工程能力，而对于算法岗位，需针对特定的领域，收集大量的数据，优化算法模型，并最终落地，然而我在这方面的经验比较欠缺。相对而言，前端的适用面比较广，自己也有相关的经验。

Q<sub>2</sub>: **你离职的原因是什么**
A<sub>2</sub>: 由于一些客观条件的影响（例如无法继续开展业务），公司解除了xxx合同，和平解散。在老东家收获了技术成长和成就感，现在来到xxx面试，是为了寻求更大的发展空间，更是为了找一个优秀的团队一起工作。
Q<sub>2+</sub>: 从离职到现在做了啥
A<sub>2+</sub>: 系统复盘自己做过的项目，由于平常的工作主要是应用这些开源库，现在有时间深入学习源码，了解其实现细节，为以后应对更复杂的业务需求打好基础。

Q<sub>3</sub>: **你为什么选择我们公司**
A<sub>3</sub>: 这要从工作性价比来考量，即工作所得除以工作付出，工作所得包括薪酬福利、资源、经验和能力提升、成长、成就感等，工作付出包括工作强度、出差、压力等。

Q<sub>4</sub>: **如何体现你的学习能力**
A<sub>4</sub>: 在陌生的领域，比如这个自动换海报脚本，本质上是一个自动化UI测试任务，我利用xxx周时间，完成需求分析、技术选型、开发、测试，并且教会运营人员这款工具的使用方法，以及遇见错误如何恢复运行等故障的处理方法，还通过他们的反馈，不断改进代码，进一步减少人工干预的操作，使得运营人员从繁琐的人工换海报操作中解放出来。

Q<sub>5</sub>: **对于团队欠下的技术债如何解决**
A<sub>5</sub>: 首先，得先认可解决技术债的重要性和可行性，然后，把技术债和业务需求放在一起排优先级，放到迭代里面做，比例不超过20%。

Q<sub>6</sub>: **你希望呆在一个什么样的团队**
A<sub>6</sub>: 最重要的是在一个高效沟通的团队，大家目标一致、相互信任、持续改进。

Q<sub>7</sub>: **你有什么爱好**
A<sub>7</sub>: 看动漫、散步、爬山。比如遇到不懂的技术问题，这时候就比较心急，如果硬着头皮继续做，则是对意志力的消磨，长期如此则影响心态。此时，我会通过上述方式让大脑休息一会，让心态恢复平静，这样当时很棘手的问题就可能会变得有迹可循。

Q<sub>8</sub>: **你有什么优缺点**
A<sub>8</sub>: 优点是对前端比较感兴趣，愿意花大部分的时间用于前端方面的提升；缺点是前端工作经验还比较少，遇到的问题还比较少，但是我相信能够通过较快的学习能力来补足，虚心向前辈们学习。
Tips: 1) 优点能给公司带来价值；
2) 需真实、走心，考察自省自知的能力、匹配度，印证评价；
3) 清楚缺点，并且知道解决方法。

Q<sub>9</sub>: **如何体现你的精益能力**
A<sub>9</sub>: 前端对业务需求的完成度，“能不能用”是最低的层次，而是要追求“好不好用”。比如前端路由这一块，由于我们之前只做了二级菜单的路由，但是随着业务变得复杂，衍生出三级、四级、甚至五级菜单。之前我们告诉运营人员上新了一个新功能，通常需要当面告诉他在哪个地方操作，比较麻烦。为此，我从前端路由这一块下手，...

Q<sub>10</sub>: **这个项目还有什么可以改进的地方**
A<sub>10</sub>: 我认为这个项目还可以引入前端监控系统。我们的运营人员在使用这套系统的时候，有时会出现各种各样的问题，比如接口报错、无返回数据、配置不正确、数据加载缓慢、js报错、抛出异常、静态资源异常等。当出现这些异常和错误时，运营人员就会时不时打断我们的工作，影响开发效率。当引入这一套监控系统后，我们能尽早发现错误，并通过日志复现问题，及早修复。为此，我需要了解所有可能会发生错误和抛出异常的地方，并在合适的地方做好埋点，做好上报工作。

Q<sub>11</sub>: **前端为什么需要CI/CD**
A<sub>11</sub>: 业务开发人员只要push自己的代码，就会触发一系列的流程，免去人工操作不小心出错的风险，同时也统一了线上的环境。首先会进行npm包的安装，并且将node_modules缓存，用于后续的操作，让后会进行一些lint检查操作，看代码是否符合规范，然后运行测试，测试通过后进行编译打包，会保存一份打包后的文件，方便以后回滚，最后会把除index.html以外的静态文件复制到cdn，index.html文件复制到nginx配置的目录下。

Q<sub>12</sub>: **这个项目为什么选择Ant Design Pro**
A<sub>12</sub>: Ant Design的生态比较丰富，有完善的组件图和图表库，提升开发效率。同时，社区比较活跃，项目一直在保持更新。

Q<sub>13</sub>: **工作中有什么难忘的事情，或者挑战、难点**
A<sub>13</sub>: 初次使用gitlab里面的CI/CD功能，由于原公司只有一台服务器，我就把gitlab runner放在了这台服务器上，...
Tips: 体现工作量、难度、技术、沟通，或从新项目、领域等角度，做了啥有啥结果。

Q<sub>14</sub>: **你的职业规划是什么**
A<sub>14</sub>: 其实我也不知道三年后、五年后能做到什么程度，不过在现在，我想专注于前端，探索前端的边界，有更多的产出。

Q<sub>15</sub>: **你有什么要问面试官的吗**
A<sub>15</sub>: 请问公司目前团队的现状如何，发展前景怎么样，要解决什么样的业务问题；我所应聘的这个职位的成长路线是怎样，公司对此职位有什么期望。

## 策略类

1. 面试考察的几种能力
    - 学习能力: 把不会的事情做出来，由于前端变化快，需要保持十足的热情；
    - 精益能力: 把事情越做越好；
    - 协作能力: 如何与大家配合；
    - 领导能力: 带领大家推动事情的发展，把事情做好；
    - 解决问题的能力: 主动发现项目中的优化点，并解决它；
    - 时间管理能力: 区分任务的轻重缓急。
2. 如何讲好一个故事
    1) 开头，讲清问题背景；
    2) 发展，讲清问题的复杂性和挑战；
    3) 高潮，讲清解决方案的形成过程；
    4) 结局，讲清结果、影响、意义。
3. 如何描述项目经历
    0) STAR法则，即情景（Situation）、任务（Task）、行动（Action）和结果（Result）；
    1) 为了某某问题或目标（要突出复杂性）；
    2) 我采用了某某方法、技能、流程（要突出创新性），或如何组建团队，如何管理过程；
    3) 达成了什么样的成功、意义。
4. 动机（做事的内因）-> 潜力（技能提升的能力）-> 技能（先讲广度后讲深度，沟通，协作）-> 经验；技术、业务和管理三方面的能力
5. 面试心态调整
    - 面试是一个双向选择的过程，总有适合自己的位置；
    - 面试的紧张程度由期待除以自信（能力+准备）决定，要把关注点从不确定的期待转移到确定的能力和准备当中；
    - 面试是为了考察应聘者的优点，对公司、客户、团队的价值，匹配度；
    - 真诚，表达自己的能力和价值，建立相互信任，自我暗示自信，挺直腰板，友好。
6. 谈薪资的注意点：简历写面议，现场强调可谈
