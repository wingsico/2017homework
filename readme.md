# 2017 Front End Homework
前端提交作业统一仓库
## 代码规范
采用团队代码风格。务必遵守规范，以便与以后的团队合作：[NCU Code Guide](http://ncuhome.github.io/frontend-guide/)

### git 提交

1. 先fork到自己的github仓库
2. 新建一个分支，以自己的名字命名，格式：homework/your_name, 并新建一个文件夹，以自己的名字命名
3. 每次将修改push到自己的github上，每次commit都要有意义，禁止'aaaa, bbb, fuck...' 等无意义的commit
4. 在规定时间之前提pull request，超时2小时之内则算迟交，否则算未交
5. 代码务必遵守代码规范，代码最好能带上注释

## 工具与资料

* 代码编辑器：推荐使用VSCode，其次为Atom，Sublime Text等
* 浏览器：谷歌浏览器、火狐浏览器等
* 思维导图：Xmind 或其他
* 命令行工具：PowerCMD 、CMDer 或其他(win10)
* 版本控制工具：git
* 切图：photoshop
* 学习资料：
    * 网站
        * freecodecamp
        * 慕课网
        * w3c
        * MDN
        * https://www.gitbook.com/book/leohxj/front-end-database/details 前端工程师手册
        * http://www.htmldog.com/guides 
        * https://learn.shayhowe.com HTML&CSS
        * http://web.jobbole.com/89943/ 听说2017你想学前端
    * 书籍
        * 精通CSS高级Web标准解决方案第二版
        * Javascript面向对象编程指南
        * CSS权威指南
        * Javascript DOM编程艺术（有点老，不过仍挺不错）
        * Javascript高级程序设计第三版
        * CSS揭秘
        * https://www.zhihu.com/question/22591993 前端工程师必读书籍

## 其他
我会将每次作业的内容记录在这个readme里面，同时会给每个人的代码进行审阅并指出问题，同时会在每次作业中选出1～2个写的好的和1一个写的不太好的标注在每次作业的下面，请大家认真完成作业。

如果在学习、完成作业中遇到问题，学会先自己寻找答案，解决流程大致如下：

```
百度 -> 重审关键字再次百度 -> 谷歌 -> 与同级前端交流 -> 问学长 
```
> 若对上面任何一点有疑问或者建议，欢迎提出。

## 作业
作业的内容会在每次例会之后更新
### 第一次作业
时间： _**2017年11月18日星期六**_ 起， _**2017年11月24日星期五晚24：00**_

内容：仿百度首页 [百度首页](http://www.baidu.com)

要求：

1. 不要把css写在html内，用外联样式表
2. 首页为非登录状态的页面
3. 不需要实现页面的跳转
4. “更多产品”处的显示隐藏不要求完成（有能力可以完成）
5. 布局基本合格，且拉伸缩小浏览器窗口布局不会变形
6. 请勿抄袭
7. 按时完成作业

其他：
完成此次作业大致需要：

* 盒模型
* position定位
* 居中
* hover等伪类选择器
* html和css基础
* 小图标的使用
* 浮动（float）
* ...

#### 作业完成情况

**基本完成，部分细节未注意：**

1.  **代码规范！！！详情见顶部《代码规范》**
2. title icon 
    
    ```html
    <link rel="shortcut icon" href="https://www.baidu.com/favicon.ico"  type="image/x-icon">
    ```
3. 部分人的水平居中还存在问题
4. 部分`hover`效果未实现
5. 对某些行内与块级元素之间的关系有一些模糊
6. `position: absolute` 与 `position: relative` 的定位关系有些模糊

拓展知识：(动态效果均可由css实现)

1. 更多应用的显示与隐藏（利用`position: fixed` + `transform` + `opacity` + `transition` + `hover` + `层叠性问题`）
2. 三角形的实现
3. 设置处的列表显隐与小三角位移
4. `iconfont` 字体图标
5. `::after` + `::before`
6. 点击搜索框实现边框变蓝色（兄弟选择器）

**收作业情况：**

6位17级有1位未交，希望下次能够加快学习进度，认真完成作业。其他人的作业存在部分应付式的完成，希望端正态度，不会的不能放在那里不管，积极主动地去查找相关资料或者与他人讨论。

---

### 第二次作业

时间： _**2017年11月27日星期一**_ 起， _**2017年12月1日星期五晚24：00**_

内容：js与css补充

要求：
    
1. 完成第一次作业的补充内容
    1. 使用css
    2. 使用js

2. 完成百度搜索功能
    1. 输入关键字 -> 出现下拉框，内部为相关词条列表
    2. 点击百度一下 -> 进入百度的搜索结果页面（使用百度自己的）
    3. 点击出现的相关词条 -> 进入百度的搜索结果页面
    4. 若关键字为空或者无相关词条结果 -> 下拉框消失

3. 使用原生js

提示：

1. 数据接口使用百度的api
2. api寻找方法：通过Chrome debugger Network 或 搜索时百度网址变化 或 api强求
3. jsonp
4. 动态插入html元素
5. 不需要输入的时候页面结构的变化

效果展示：

![百度拓展-示例图片](https://raw.githubusercontent.com/wingsico/2017homework/master/homework_review/2-baidu-extension/example.png)

### 作业完成情况
基本ok

---
### 第三次作业
时间： _**2017年12月5日星期二**_ 起，为期**2周**

内容：**js小练习**:


    1. 文字替换
    2. 文字搬运

要求：
    
1. 文字替换
    1. 查找一段话中的某个字或某几个字，改变其样式
    2. 替换所查找到的文字
    3. 改变原句，即替换之后，原来的词将不再能被查找到
    4. 弹出相关提示，即替换成功或没有找到该词
    
2. 文字搬运
    1. 将一段文字从一处逐字搬运至另一处
    2. 通过按钮点击开始搬运
    3. 显示搬运的进度，开始搬运时开始显示进度，搬运完毕隐藏进度
    4. 搬运完毕后按钮不可点击

3. 使用原生js

提示：

1. splice、slice
2. 定时器
3. js 控制dom样式
4. split、join
5. window.alert

效果展示：
1. 文字查找替换
 ![](https://github.com/wingsico/2017homework/blob/master/homework_review/3-words-carry-replace/word-replace.gif?raw=true)
2. 文字搬运
    ![](https://github.com/wingsico/2017homework/blob/master/homework_review/3-words-carry-replace/word-carry.gif?raw=true)
### 作业完成情况
待跟进
---

1. requestAnimationFrame
2. 为什么不用setInterval
3. 尾递归优化
4. caniuse
5. vw/vh
6. rem
7. 张鑫旭
8. 移动端适配方案
9. bootstrap
10. 

