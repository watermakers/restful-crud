# restful-crud
springboot：国际化处理、restful风格、错误页面处理、thymeleaf语法、全注解配置<br>
1、点击页面上的按钮“中文”或“English”进行语言的切换<br>
2、当在地址栏中输入一个不存在的地址时（登陆后），将返回tmplates文件夹下error下的404.html页面。写了MessageException处理500类型的数据，程序内部抛出异常将返回5xx.html<br>
3、使用restful风格，请求看起来非常简洁易懂<br>
只在登录页实现了国际化，还有一些增删改查的功能，没有连接数据库，主要是为了练习springMVC的restful风格，仅当做springboot的一个练习<br>
国际化处理后的页面如下<br>
<img src="https://raw.githubusercontent.com/watermakers/images/master/restful-crud-img/12.PNG"/><br><br>
<img src="https://raw.githubusercontent.com/watermakers/images/master/restful-crud-img/13.PNG"/>
错误处理后的页面如下<br>
<img src="https://raw.githubusercontent.com/watermakers/images/master/restful-crud-img/3.PNG"/>
