总体来说, 该中间件返回一个dispatch generator中间件, 通过该中间件查找所有路径匹配的中间件, 最后将这些匹配的中间件串起来后通过yield *next执行!

See test & lib/*.js