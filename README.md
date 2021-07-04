# KsfSwap Finance Uikit
It's Based on [pancakeswap's uikit](https://www.npmjs.com/package/ksfswapuikit).
 
KsfSwap UIkit is a set of React components and hooks used to build pages on KsfSwap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add ksfswapuikit`

## Setup

### Theme

Before using KsfSwap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'ksfswapuikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'ksfswapuikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)
