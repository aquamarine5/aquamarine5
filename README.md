### Hi there 👋

### 目前是一名在校初三学生，~~3月后我就14岁了呜呜呜~~ 即将中考:-<

***好了，我是fw***  
![](https://github-readme-stats.vercel.app/api?username=awesomehhhhh&show_icons=true&icon_color=CE1D2D&text_color=718096&bg_color=ffffff)  
![](https://visitor-badge.glitch.me/badge?page_id=awesomehhhhh)  

### Top Language:

- 本人最喜欢的是Python，无理由（doge
- C#我最喜欢用在Unity里面，实际上我有个游戏的库是私有的（
- 其次是Kotlin和C#，Kotlin的语法糖成了日常调侃的对象，比如：
<details>
<summary>Show the code</summary>

```kotlin
var i: Int? = 44
var result: Type? = null
enum class Type{A,B,C,OTHER}
fun KOTLIN(): Type? {
     fun Type.toInt():Int? = when(this){Type.A->1;Type.B->2;Type.C->3;else->null}
     fun Int.toType():Type = if (i?.toString()?.startsWith("4")!!) Type.A else Type.OTHER
     fun resultToType(i:Int?, ex:Boolean, func: (Int?) -> Type?) { if(ex)result=func(i) }
     return try{
        val t=Type.A.toInt()
        do i = i?.plus(2)while(i!! >=50)
        for(fori in 1..10 step 5) i = i?.plus(fori)
        for(forj in 10 downTo 1 step 5) i = i?.minus((forj*0.5).toInt())
        if(i!! >=100)TODO("?")
        resultToType(i,i.toString().drop(i?.toString()?.length!!-1).startsWith('1')) {
            return@resultToType if(i?:Int.MAX_VALUE == Int.MAX_VALUE ) null else i?.toType()
        }
        t?.plus(i!!)?.toType()
    }
    catch (e:NotImplementedError) {null}
}
fun main(){print("RESULT: ${KOTLIN()} is result")}
```

</details>

你知道结果是什么吗？（前提：能看懂）
#### 好耶——

