---
title: "网站的更新日志"
description: 封面来源于Pixiv（插画ID：62620708），画师：ろけ（ID：946783），侵删。
date: 2024-02-05
lastmod: 2024-02-05T21:00:04+08:00
categories: []
draft: false
image: "banner.jpg"
slug: changelog
menu:
    main: 
        name: 更新日志
        weight: -1
        params:
            icon: clock
---


## 20240214
- 布局

    - 覆盖了主题给出的`layouts/partials/data/title.html`，修改了页面标题的格式。

        *主题给出的这一文件似乎工作不正确。显示分页页码的部分不起作用。*

        *我不确定[issue](https://github.com/CaiJimmy/hugo-theme-stack/issues/941)写得是否规范（逃*

    - 修改了`config`中`paginate`的数目为10。

    - 在`assets/scss/custom.scss`中修改了代码块的样式。

- 内容

    - 整理了「[关于](/about)」页面。

## 20240206

- 内容

    - midi文件从[https://blog.strmnl.top/midi](https://blog.strmnl.top/midi)迁移至[https://midi.strmnl.top](https://midi.strmnl.top)。

        - 现在midi文件不再是网站blog部分的静态内容。

    - 更新了midi的链接。


## 20240205b
- 内容

    - 新增了midi页面和对应的侧边栏图标。

        *midi存放在另一个仓库。*


## 20240205a
- 布局
    - 弃用[kagome](https://github.com/miiiku/hugo-theme-kagome)主题。移除了一些有关的自定义内容。
    - 启用[stack](https://github.com/CaiJimmy/hugo-theme-stack)主题。

- 构建
    - 更改Github Pages构建网页时使用的Hugo版本为v0.122.0。

- 内容
    - 新增了更新日志页面。*（就是这里:D）*
    - 修改了网站的标题。*（这是什么鬼名字啊喂）*
    - 移除了[不蒜子计数器](https://busuanzi.ibruce.info/)。

## 20240205前

- 没有进行任何记录。

    *这不是个好习惯。(＠_＠;)*