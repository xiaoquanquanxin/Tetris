#   1.activeObj 是一个对象,里面存放的是4个数组,每个数组里面都是x和y,
#   2.每一秒一次循环,循环后,activeObj里面的y会++,
#   3.每次按键,activeObj里面的x都会改变
#   4.落地之后的一次循环,activeObj才会叠加到deathObj里面
#   5.当切仅当没有activeObj里面最大的y值也<0时,判断deathObj里面是否可以消除一行
