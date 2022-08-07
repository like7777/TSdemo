any     : 任意类型   <!-- 可以赋予任意类型的值 -->
number  : 数字类型   
string  : 字符串类型 
boolean : 布尔类型
|       : 字面量    <!-- 限制变量的值就是该字面量的值-->
unknown : 未知类型  <!-- unknown不能直接赋值给其他变量-->
array   : 数组类型
void    : 表示该方法没有返回值
null    : 空
never   : 其他类型的字类型,表示从不会出现的值 <!-- 可以用来抛出异常-->
undefined : 未定义

元组   <!-- 用来表示已知元素数量跟类型的数组,类型不必相同,对应位置的类型必须相同-->
    例:
        let x : [string, number]
        x = ['aa',1] //正常
        x = [1,'aa'] //报错

enum : 枚举  <!-- 用来定义数值集合-->
    enum color {red, green, blue}
    let c : color = color.blue
    console.log(c)   // 2