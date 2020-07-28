# 1. vue_shop_record

## 1.1 vue概述
- 库和框架的区别：
  1. 库：主要是提供API接口
  2. 框架：主要提供基础性的服务
- Vue代码到原生javascript代码需要Vue框架的编译
- MVVM设计思想，M(model),V(view),VM(View-Model)
  1. VM使用DOM listeners监听DOM的变化，以此来改变Model，使用Data Buildings查看Model的变化，反应到DOM上。
## 1.2 vue常用特性
- 计算属性和方法的差别：
  1. 计算属性是基于它们的依赖(data中的数据)进行缓存的
  2. 方法不存在缓存
- 侦听器
  1. 数据一旦发生变化就会触发所绑定的方法
  2. 数据变化时执行异步或开销比较大的操作
## 1.3 vue生命周期

###  1.3.1 主要阶段
- https://cn.vuejs.org/v2/api/#beforeCreate
- 挂载（初始化相关属性）
   1. beforeCreate
   2. created
   3. beforeMount
   4. mounted
- 更新
   1. beforeUpdate
   2. updated
- 销毁（销毁相关属性）
   1. beforeDestroy
   2. destroyed