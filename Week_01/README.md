week1
学习笔记
1. inline-block默认对齐方式是vertical,改为middle
2. text-align: center 水平居中
   line-height帮助垂直居中（使用iconfont或emoji）
3. 使用花括号让代码变为局部
4. 胜负剪枝:判断要赢就不判断了
5. Object.create相比JSON.parse(JSON.stringify()):
   常规方式创建对象，会执行构造函数（new或字面量{}）
   Object.create不执行构造函数。而是使用现有的对象提供给新对象的_proto_，创建了一个空数组，而原型链指向了原有的对象。如果在新的对象中找不到某一个数据。就去原型链找，然后返回原型链的值。
   如果赋值给新对象，那么搜索就会在新对象中找，而不去原型链了。
