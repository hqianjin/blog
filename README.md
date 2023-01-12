## 2023-1-12
* 2 阮一峰es6 - 对象的新增方法
- `Object.assign()`
`Object.assign()`方法用于对象的合并，将源对象（source）的所有可枚举属性，复制到目标对象（target）。
```
const target = { a: 1 }
const source1 = { b: 2 }
const source2 = { c: 3 }
Object.assign(target,source1,source2)
console.log(target) //{a: 1, b: 2, c: 3}
```
`Object.assign()`方法的第一个参数是目标对象，后面的参数都是源对象。

## 2023-1-11
在Github上创建自己的项目：https://www.codenong.com/cs105823638/
在Github中如何删除如blog项目：https://blog.csdn.net/A994958/article/details/118054176
vscode如何上传项目:正常git上传

* 1 阮一峰es6 - 函数的扩展 https://juejin.cn/post/7187201890856222780 
- `arguments`
- `箭头函数`
- `rest参数(...变量名)`：不使用argument,搭配变量为数组，获取多余的参数；改写数组push方法
- `扩展运算符(...)`：替代apply()方法、push()函数、运用
- `Array.from()`：转数组
- `Array.of()`：转数组
- `copyWithin()`：将指定位置的成员复制到其他位置（会覆盖原有成员），然后返回当前数组
- `find()、findIndex()`：找到符合数组成员第一个返回值、返回第一个符合条件的数组成员的位置
- `fill()`：填充一个数组
- `includes()`：返回一个布尔值，表示某个数组是否包含给定的值
- `flat(),flatMap()`：用于将嵌套的数组“拉平”，变成一维的数组
- `at()`：接受一个整数作为参数，返回对应位置的成员，并支持负索引 