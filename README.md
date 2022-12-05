# ct-ui

## 介绍

>

 [github](https://github.com/ffangzhu/ct-ui) 预览

## npm 方式安装使用

```js
// 先安装
npm i @zhufang/ct-ui
// 在main.js中按下引入
import Ctui from '@zhufang/ct-ui'
Vue.use(Ctui)
```

## 直接在项目中全局使用（前提是已全局安装了 Element-ui 并已引入其样式）

```js
// 1、把packages文件夹复制，放在自己项目中
// 2、假设 packages 与 src是同级，那么src下 main.js 如下操作即可全局使用t-ui
import Ctui from '../packages'
Vue.use(Ctui)
```

## 安装依赖 **如果总报错就用 cnpm install**

```shell
npm install

```

## 本地运行 src 中组件示例

```shell
npm run serve
```

## 本地运行 vuepress 中组件文档

```shell
npm run docs:dev

```