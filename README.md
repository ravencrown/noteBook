## 公司面经

### *[虾皮](https://github.com/ravencrown/noteBook/issues/2)*
### *[头条](https://github.com/ravencrown/noteBook/issues/3)*
### *[微众](https://github.com/ravencrown/noteBook/issues/5)*
### *[vivo](https://github.com/ravencrown/noteBook/issues/1)*
### *[华为](https://github.com/ravencrown/noteBook/issues/6)*
### *[腾讯yoo视频](https://github.com/ravencrown/noteBook/issues/4)*

## 题型面经

### *[Node](https://github.com/ravencrown/noteBook/issues/13)*
### *[vue 源码原理](https://github.com/ravencrown/noteBook/issues/9)*
### *[性能优化](https://github.com/ravencrown/noteBook/issues/8)*
### *[HTTP 相关](https://github.com/ravencrown/noteBook/issues/7)*
### *[项目相关](https://github.com/ravencrown/noteBook/issues/12)*
### *[JavaScript](https://github.com/ravencrown/noteBook/issues/11)*
### *[Webpack相关](https://github.com/ravencrown/noteBook/issues/10)*
### *[小程序原理相关](https://github.com/ravencrown/noteBook/issues/14)*
### *[个人简历分析](https://github.com/ravencrown/noteBook/issues/15)*


## 前端100问

### *[前端100问 - 壹题](https://github.com/Advanced-Frontend/Daily-Interview-Question/blob/master/datum/summary.md)*


## Event-Loop

- [这一次，彻底弄懂 JavaScript 执行机制](https://juejin.im/post/59e85eebf265da430d571f89)
- [Event Loop的规范和实现](https://zhuanlan.zhihu.com/p/33087629)
- [带你彻底弄懂Event Loop](https://juejin.im/post/5b8f76675188255c7c653811)

```js
// 头条的经典面试题
async function async1() {
    console.log('async1 start');
    await async2();
    console.log('async1 end');
}

async function async2() {
    console.log('async2');
}

console.log('script start');

setTimeout(function() {
    console.log('setTimeout');
}, 0)

async1();

new Promise(function(resolve) {
    console.log('promise1');
    resolve();
}).then(function() {
    console.log('promise2');
});
console.log('script end');
```




