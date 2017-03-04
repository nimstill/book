####函数式编程
#####函数式编程有两个最基本的运算：合成和柯里化。

const compose = function (f, g) {
    return function (x) {
        return f(g(x));
    }
}

