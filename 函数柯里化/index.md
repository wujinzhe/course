# 函数柯里化

什么是函数的柯里化呢，先给大家用代码举一个例子就可以很明显的看出来了
```JS
// 普通函数调用
add(1, 3)

// 柯里化后
add(1)(3)
```
那从这个例子中我们可以看出来原本一个函数调用传了两个参数，现在改为了一个每次传一个参数，并且该函数的返回值也变成了一个函数，并且可以继续传参数