## this
**运行时** 决定的，
书写的时候

```js
function foo(){
    this.a;
}
foo();
```

- 默认 this 指向 window
- call/apply 调用 ，指向我们的第一个参数
- apply 和 call 的区别在于 apply 后面调用的新参得用数组包起来
  foo.apply(obj , ['a var','b var'])
  foo.call(obj , 'a var','b var')