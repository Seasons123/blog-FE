论文编辑器 [ctext](http://blog.sina.com.cn/s/blog_6647de110102uw3a.html)   

Markdown——[入门指南](http://www.jianshu.com/p/1e402922ee32/) 

汇总了一部分前端相关基础知识 :watermelon:

##  一、《Object-Oriented JavaScript》       

       其余部分的笔记见我的笔记《blue cat , I am so hungry》
     
4.2.2 [Array](https://github.com/Seasons123/blog/issues/11)  

4.2.3 [Function](https://github.com/Seasons123/blog/issues/14)  

4.2.6 [String](https://github.com/Seasons123/blog/issues/15)

            注意：
            （1）String对象的方法，返回的都是一个新的基本字符串，它们所做的任何修改都不会改动源字符串。
            （2）通常情况下，我们会用indexOf()和lastIndexOf()方法进行字符串内搜索，但除此之外还有一些功能更为
            强大的方法（如search()、match()、replace() 等），它们可以以正则表达式为参数来执行搜索任务。
            （3）以正则表达式为参数的字符串方法：split、search、match、replace        


## 二、《es6》

1、第8章 函数的扩展

（1）[rest函数](https://github.com/Seasons123/blog/issues/12) 

（2）[扩展运算符](https://github.com/Seasons123/blog/issues/12) 

（3）[箭头函数](https://github.com/Seasons123/blog/issues/41) 

（4）[Promise](https://github.com/Seasons123/blog/issues/52) 

（5）[你必须了解的 ES8 新特性](https://github.com/Seasons123/blog/issues/27)


http://www.cnblogs.com/huansky/tag/ES6/ 



## 三、mst

           另一部分见笔记《blue cat , I am so hungry》
       
1、CSS相关

（1）[CSS九宫格布局](https://github.com/Seasons123/blog/issues/19) 

（2）
 > 1.[左侧固定宽右侧自适应](https://github.com/Seasons123/blog/issues/38)

 > 2.[八种创建等高列布局](http://www.w3cplus.com/css/creaet-equal-height-columns)

 > 3.[实现最小高度的设置](https://github.com/Seasons123/blog/issues/39)

 > 4.[综合上面三条的一道CSS布局的面试题](https://github.com/Seasons123/blog/issues/40)
 
（3）[圣杯布局和双飞翼布局](http://www.jianshu.com/p/f9bcddb0e8b4)

（4）[stick footer布局](https://github.com/Seasons123/blog/issues/46)

（5）[最小高度满一屏的自适应布局](https://github.com/Seasons123/blog/issues/47)

（6）[如何实现并排的三个DIV框都自适应](https://github.com/Seasons123/blog/issues/65)


2、JS相关

（1）[闭包问题](https://github.com/Seasons123/blog/issues/18) 

（2）[原型上定义的方法和静态方法有什么区别 ](https://github.com/Seasons123/blog/issues/21)

（3）[JS事件中如何拿到父节点](https://github.com/Seasons123/blog/issues/37) 

（4）[promise，async await，generator 之间的关系 ](https://github.com/Seasons123/blog/issues/17) 

（5）[Javascript异步编程的4种方法](http://www.ruanyifeng.com/blog/2012/12/asynchronous%EF%BC%BFjavascript.html) 

（6）[javascript如何检测一个数据是不是数组](https://github.com/Seasons123/blog/issues/42) 

（7）[密圈中一个js问题](https://github.com/Seasons123/blog/issues/43) 

（8）[jquery的监听事件的方式有哪几种，它们的区别是什么](https://github.com/Seasons123/blog/issues/51)

（9）[严格模式](https://github.com/Seasons123/blog/issues/57)

（10）[JS实现各种排序算法](https://github.com/Seasons123/blog/issues/63)

（11）[javascript中对象的深度克隆](http://www.cnblogs.com/jq-melody/p/4499333.html) 这篇博文递归的部分还有另外两种写法，另见js面向编程指南6.8深拷贝和[该链接13题](https://yq.aliyun.com/articles/138985)

              改成常见递归形式
              for(key in obj){
                          var copy=obj[key];
                          if(isClass(copy)=="Object"){
                              result[key]=deepClone(copy);//递归调用
                          }else if(isClass(copy)=="Array"){
                              result[key]=deepClone(copy);
                          }else{
                              result[key]=obj[key];
                          }
                      }

（12）[js实现自定义contextmenu](http://www.jianshu.com/p/8c358b38734f)

3、前端性能

（1）[reflow(回流)和repaint(重绘)](https://github.com/Seasons123/blog/issues/28)

（2）[做动画时使用setInterval和setTimeOut这样的延时函数为什么会出现掉帧现象，用requestAnimationFrame不会掉帧](https://github.com/Seasons123/blog/issues/29)
   
（3）[网页性能管理详解](http://www.ruanyifeng.com/blog/2015/09/web-page-performance-in-depth.html) 

（4）[JavaScript 函数节流和函数去抖应用场景辨析](https://github.com/Seasons123/blog/issues/55) 

（5）[浏览器的缓存机制](https://github.com/Seasons123/blog/issues/20)

5、模块化

（1）[关于js模块化](https://github.com/Seasons123/ADReact/issues/32) 

（2）[webpack中require和import的区别](https://github.com/Seasons123/blog/issues/45) 

（1）[webpack优秀中文文章](https://github.com/webpack-china/awesome-webpack-cn)

4、其他

（1）[综合编程：用原生语言实现实现有遮罩效果的弹窗居中（alibaba）]( https://github.com/Seasons123/popup)  

（2）[Web访问原理-从输入URL到页面加载完成的过程中都发生了什么事情？](https://github.com/Seasons123/blog/issues/30) 

（3）[MVVM思想的理解](https://github.com/Seasons123/blog/issues/50)

（4）[jsonp的原理](https://github.com/Seasons123/blog/issues/49)

（5）[网络：UDP和TCP](https://github.com/Seasons123/blog/issues/56)

（6）[操作系统：进程/线程同步的方式](https://github.com/Seasons123/blog/issues/58) :question:

（5）[正则表达式](https://github.com/Seasons123/blog/issues/8)

5、不错的博文

（1）[阮老师的网络日志](http://www.ruanyifeng.com/blog/archives.html)

（2）[大漠老师的w3cplus和相关的CSS书](http://www.w3cplus.com/)

       CSS的书籍《CSS权威指南》--双鱼书、《JavaScript DOM 编程艺术》                

（3）[月影老师的博客](https://www.h5jun.com/)

（4）[张鑫旭老师的博客](http://www.zhangxinxu.com/)

（5）[leehey's blog](https://github.com/lcxfs1991/blog)

（6）[web前端笔面试汇总](https://github.com/Seasons123/blog/issues/53)

（5）[各种前端资源汇总「备忘、常逛」【持续更新...】](http://www.cnblogs.com/skylar/p/front-end-resource-javascript.html)

（6）[FEX技术周刊](http://fex.baidu.com/articles/)


## 四、《JavaScript高程3》

       另外一本《JavaScript权威指南》               

1、[第一讲：第1~3章](http://www.cnblogs.com/bling/p/5554067.html)  

## 五、《JavaScript语言精粹》

[读书总结](http://www.cnblogs.com/xing901022/p/4872910.html) 

## 六、《深入浅出nodejs》-朴灵
