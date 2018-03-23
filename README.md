# 微信小程序Loading加载动画组件`wepy-com-loadings`
基于Wepy开发的微信小程序loading加载动画组件

# 说明
## 安装
```
npm i wepy-com-loadings
```
## 使用
```
<template>
  <view>
    <Loadings1 type="1"/>
    <Loadings2 type="2"/>
  </view>
</template>
import wepy from 'wepy'
import Loadings from "wepy-com-loadings"
export default class Index extends wepy.page {
  components = {
    Loadings1:Loadings,
    Loadings2:Loadings
  }
}
```

## 属性值
属性 | 默认值 | 类型 | 必填 | 说明
---|---|---|---|---
type | 1 | String | 否 | 1-10个loading动画ID依次类推

## 展示
![image](https://github.com/Licoy/wepy-com-loadings/blob/master/example/show.gif?raw=true)