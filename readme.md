学习react  
***光看没用  还是得动手做***    
let't go

1. 胡子大哈笔记:
关于事件中的this
react调用你定义的方法的时候,并不是通过对象方法的方式来调用的,而是直接通过函数调用,
所以函数的this是指向其自身,
如果你需要在事件函数当中使用当前的实例,你需要手动的将实例方法bind到当前的实例上再传给React.js
this.foo.bind(this, 'arg');

2. 思考 
- Link与NavLink的区别
- React.createdRef()的作用
