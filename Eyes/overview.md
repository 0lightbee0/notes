# Eyes 呈现引擎

## 基础
### 布局
+ flex, grid, multi-column, flow

### 外观
+ background 背景
+ color 颜色
+ border 边框
+ cursor 光标

### 适应盒模型
空白和适应内容
+ margin, padding

### 文字排版
+ align(h:Align v:Align) 对齐方式
+ fl-tab(Distance) 首行缩进
+ space(Distance) 间隙
+ height(Distance) 行高
+ family(Font.Family) 字体
+ weight(Distance) 粗细度
+ decoration(Font.Decoration) 装饰

### 无障碍和硬件适应
+ outline
+ speak
+ key select

## 动画
+ 基于时间轴 全局模式 global mode
+ 基于对象属性 单独模式 singleton mode
+ 全覆盖状态和属性以及值
+ 从动态值过渡

## 选择器
集
+ `*` 通用
+ `a b` 范围
+ `a+b`
+ `a>b`
+ `a,b`
+ `.a.b` 状态

## 条件


## 组件
高内聚，强交互性以及粘合数据的元素集合
### 状态
+ 存储与恢复

### 行为 (函数，方法)

### 一致性与差异性 (继承与覆写)

### 残缺组件 (实例和组件的联系)
当组件被试图删除或因为其它情况导致组件不能使用时，组件会被标记为残缺状态而不会立刻删除，残缺组件具有以下特性
+ 无法与实例之间保持关联
+ 无法新建实例

    默认行为：  当组件处于残缺状态时，所有此组件的实例立刻执行扁平化的操作？
    理由：      实例不能删除，会破坏整体的结构

### 数据模型

## 数据一致 (分布式系统基础服务)
与服务器交流的途径

### 数据标志
提供数据地址
+ 组件实例地址编址

### 数据同步服务
应用的基础服务，使用订阅和发布消息模型的实时服务
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcyNjkxMzg1MiwxNzI2OTEzODUyLDgwNz
UzNjUwMSw1MjMzMjY3OSwtMzIxMTM1NjI4LC0xNTk0MjEwMzAy
LC0xNzkzNzgxNzM4LC0xMTM0NjY3OTIyXX0=
-->