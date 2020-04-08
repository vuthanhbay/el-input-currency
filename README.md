> A Vue.js library input mask is built on <a href="https://element.eleme.io/#/en-US">element-ui</a> and <a href="https://github.com/vuejs-tips/v-money">v-money</a>

## Install
```shell
npm install @vt7/el-input-currency
```
```shell
yarn add @vt7/el-input-currency
```

## Quick Start
``` javascript
import Vue from 'vue'
import ElInputCurrency from '@vt7/el-input-currency'

// import css element-ui input
// If you have element-ui installed, you can skip it
import '@vt7/el-input-currency/dist/el-input-currency.css'

Vue.use(Element)
```


## Use
``` javascript
<el-input-currency v-model="price"></el-input-currency>

...

data () {
  return {
    price: 1000
  }
}
```
