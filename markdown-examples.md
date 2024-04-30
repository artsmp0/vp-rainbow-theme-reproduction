# Markdown Extension Examples

This page demonstrates some of the built-in markdown extensions provided by VitePress.

[Shiki](https://github.com/shikijs/shiki)

[Shiki](/index)

[Baidu](/index)

1. 如果使用 Svg Icon 请注意需要配置 [`vite-plugin-svg-icons`](https://github.com/vbenjs/vite-plugin-svg-icons) 这个插件，并且传递的 icon 需要以 `svg-` 开头。
2. 如果使用 Naive Icon，需要[文档](/icon)根据[文档](https://www.naiveui.com/zh-CN/os-theme/components/icon)安装[Shiki](https://github.com/shikijs/shiki)对应的图标包，传递的 icon 属性是对应的图标组件。
3. 如果使用 Unocss Icon，[Baidu](/index) 则需要安装 [Unocss](https://github.com/shikijs/shiki)，传递的 icon 字符串需要以 `i-` 开头。

## Syntax Highlighting

[Shiki](https://github.com/shikijs/shiki)

[Shiki](/index)

VitePress provides Syntax Highlighting powered by [Shiki](https://github.com/shikijs/shiki), with additional features like line-highlighting:

**Input**

````md
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**Output**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

## Custom Containers

**Input**

```md
::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::
```

**Output**

::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::

## More

Check out the documentation for the [full list of markdown extensions](https://vitepress.dev/guide/markdown).
