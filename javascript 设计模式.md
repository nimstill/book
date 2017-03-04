###函数式编程
####函数式编程有两个最基本的运算：合成和柯里化。


**"范畴"（category）**

const compose = function (f, g) {
    return function (x) {
        return f(g(x));
    }
}

所谓"柯里化"，就是把一个多参数的函数，转化为单参数函数。

maybe

class Maybe extems Functor {
    map(f) {
    return this.val ? Maybe.of(f(this.val)) : Maybe.of(null);
}
}

考虑整体

-------------------------------------------------------------------------



