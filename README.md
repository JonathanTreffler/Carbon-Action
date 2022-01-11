# Carbon Action [Unofficial]
---
<p align="center">
    <a href="https://github.com/carbon-app/carbon">
        <img src="resources/carbon.png" alt="Carbon">
    </a>
    <br>
    <b>Unofficial Github Action</b>
    <br>
</p>

### Show some :heart: and :star: the repo

[![GitHub stars](https://img.shields.io/github/stars/JonathanTreffler/Carbon-Action.svg?style=social&label=Star)](https://github.com/JonathanTreffler/JioSaavnAPI)
![GitHub followers](https://img.shields.io/github/followers/JonathanTreffler.svg?style=social&label=Follow)

## Carbon Github Action written in Python using Flask and Pyppeteer based on [Carbon API](https://github.com/cyberboysumanjay/Carbon-API) by @cyberboysumanjay
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

> **Carbon**  makes it easy to create and share beautiful images of your source code

#### Usage
Add this to your workflow and configure the with parameters:
```
- uses: JonathanTreffler/Carbon-Action@master
  with:
      code: $(cat code.js)
      language: JavaScript
```

#### Action parameters

| parameter              | default                    | type    | description                                      |
| ---------------------- | -------------------------- | ------- | ------------------------------------------------ |
| `code` (required)      |                            | string  | Code snippet                                     |
| `backgroundColor`      | `"rgba(171, 184, 195, 1)"` | string  | Hex or rgba color                                |
| `dropShadow`           | `true`                     | boolean | Turn on/off shadow                               |
| `dropShadowBlurRadius` | `"68px"`                   | string  | shadow blur radius                               |
| `dropShadowOffsetY`    | `"20px"`                   | string  | shadow offset y                                  |
| `exportSize`           | `"2x"`                     | string  | resolution of exported image, e.g. `1x`, `3x`    |
| `fontSize`             | `"14px"`                   | string  | font size                                        |
| `fontFamily`           | `"Hack"`                   | string  | font family, e.g. `JetBrains Mono`, `Fira Code`. |
| `firstLineNumber`      | `1`                        | number  | first line number                                |
| `language`             | `"auto"`                   | string  | programing language for properly highlighting    |
| `lineNumbers`          | `false`                    | boolean | turn on/off line number                          |
| `paddingHorizontal`    | `"56px"`                   | string  | horizontal padding                               |
| `paddingVertical`      | `"56px"`                   | string  | vertical padding                                 |
| `theme`                | `"seti"`                   | string  | code theme                                       |
| `watermark`            | `false`                    | boolean | turn on/off watermark                            |
| `widthAdjustment`      | `true`                     | boolean | turn on/off width adjustment                     |
| `windowControls`       | `true`                     | boolean | turn on/off window controls                      |
| `windowTheme`          | `"none"`                   | string  | window theme                                     |

### Output
An image like this one will be saved into the working directory as code.png.
<p align="center">
    <img src="resources/response.png" alt="Response">
</p>

### Copyright & License

* Copyright (C) 2020 by [Sumanjay](https://github.com/cyberboysumanjay) (Original Author)
* Copyright (C) 2021 by [Jonathantreffler](https://github.com/JonathanTreffler) (Modified to be a Githubb Action)
* Licensed under the terms of the [GNU GPL Version 3](https://github.com/JonathanTreffler/Carbon-Action/blob/master/LICENSE)
