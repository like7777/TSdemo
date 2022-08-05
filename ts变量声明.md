<!-- 变量不要使用name,否则会与window对象下的name属性重名 -->
1.  var [变量名] : [类型] = 值
    var uname : string = "小明"

2.  var [变量名] : [类型]
    var uname : string       <!-- 变量值会设置为undfined-->

3.  var [变量名] = 值
    var uname = "小明"        <!-- 设置了初始值不设置类型,该变量可以是任意类型-->

4.  var [变量名]
    var uname                <!-- 声明变量没有设置类型和初始值,类型可以是任意类型,初始值为undfined-->