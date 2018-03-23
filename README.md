# 微信小程序Loading加载动画组件`wepy-com-loadings`
基于Wepy开发的微信小程序loading加载动画组件

# 说明
## 安装
```
npm i wepy-com-loadings
```
## 引用
```
import Loadings from "wepy-com-loadings"

components = {
  Loadings1:Loadings,
  Loadings2:Loadings
}
```

## 使用
```
<Loadings1 type="1"/>
<Loadings2 type="2"/>
```

## 属性值
属性 | 默认值 | 类型 | 必填 | 说明
---|---|---|---|---
type | 1 | String | 否 | 1-10个loading动画ID依次类推

## 展示
![https://github.com/Licoy/wepy-com-loadings/blob/master/example/show.gif?raw=true]