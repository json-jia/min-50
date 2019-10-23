<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
}

// $color: pink;
// sass 有两种语法
// 1. scss 使用起来和 less 类似, 也支持嵌套写法, 区别: 定义变量不同 $
// 2. sass 语法和 stylus 比较类似, 写起来比较简洁 特征: 必须省略 {} ;
/* 不加任何限制时, 组件与组件之间的样式, 是会互相影响的 */
// * {
//   margin: 0;
//   padding: 0;
// }
// body {
//   background-color: $color;
//   h1 {
//     background-color: skyblue;
//     font-size: 40px;
//     color: red;
//   }
// }

// *
//   margin: 0
//   padding: 0

// body
//   background: pink
//   h1
//     font-size: 40px
//     color: red
</style>
