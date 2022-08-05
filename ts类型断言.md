类型断言可以用来手动指定一个值的类型,即允许变量从一种类型更改为另一种类型
格式:   <类型>值    or    值 as 类型
例如:   var str = '1'
        var str2:number = <number> <any> str
        console.log(str2)

<!-- 类型推断 -->
var num = 2;    <!-- 类型推断为number-->
num = "12"      <!-- 编译错误-->
<!-- 第一次声明了变量num并设置初始值为2且没有设置类型,typescript推断类型为number,当我们再次为变量设置字符串的值的时候,会报错。  -->