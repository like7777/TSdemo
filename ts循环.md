<!-- for循环 -->

<!-- for...in -->
**for...in语句用于一组值的集合或列表进行迭代**
```ts
    for(var val in list){
        //  val需要为string或any类型 
    }
```
*实例:*
```ts
    var j:any
    var n:any = "a,b,c"
    for(j in n){
        console.log(n[j])
    }
    //输出结果 a b c
```

<!-- for...of-->
```ts
    let arr = [1,'str',false]
    for(let entry for arr){
        console.log(entry)
    }
    // 1,'str',false
```

<!-- forEach-->
```ts
    let list = [4,5,6]
    list.forEach((val,idx,array) => {
        //val 当前值
        //idx 当前index
        //array 数组
    })
```
