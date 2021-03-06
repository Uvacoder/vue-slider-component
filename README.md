![banner](https://raw.githubusercontent.com/NightCatSama/vue-slider-component/master/.github/banner.jpg)

[![downloads](https://img.shields.io/npm/dm/vue-slider-component.svg)](https://www.npmjs.com/package/vue-slider-component)
[![npm-version](https://img.shields.io/npm/v/vue-slider-component.svg)](https://www.npmjs.com/package/vue-slider-component)
[![license](https://img.shields.io/npm/l/express.svg)]()

> đ A highly customized slider component

English | [įŽäŊä¸­æ](https://github.com/NightCatSama/vue-slider-component/blob/master/README-CN.md)

## đ Vue3.x

This is still in beta and may contain unexpected bugs, please use with caution.

#### install

```bash
$ yarn add vue-slider-component@next
# npm install vue-slider-component@next --save
```

#### Caution
- Change `data` to `v-data` for now due to a type conflict. (Probably a temporary modification)

## â¨ Features
- đ More customizable
- đ Multiple style themes
- đŗ Support for more sliders
- đ Add marks
- đ Support SSR
- đ Support Typescript

## đ Documentation

Document: <https://nightcatsama.github.io/vue-slider-component>

Live Demo: <https://jsfiddle.net/NightCatSama/2xy72dod/10547/>


## đ¯ install
```bash
$ yarn add vue-slider-component
# npm install vue-slider-component --save
```


## đ Usage
```vue
<template>
  <vue-slider v-model="value" />
</template>

<script>
import VueSlider from 'vue-slider-component'
import 'vue-slider-component/theme/antd.css'

export default {
  components: {
    VueSlider
  },
  data () {
    return {
      value: 0
    }
  }
}
</script>
```

## Changelog

Detailed changes for each release are documented in the [release notes](https://github.com/NightCatSama/vue-slider-component/blob/master/CHANGELOG.md).

## Support

If my code has helped you, please consider [buy me a coffee](https://www.buymeacoffee.com/nightcat) âī¸.

## License

[MIT](https://github.com/NightCatSama/vue-slider-component/blob/master/LICENSE)
