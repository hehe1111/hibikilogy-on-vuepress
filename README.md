# Hibikilogy on VuePress

A mirror of [hibikilogy](https://hibikilogy.github.io/).

Power by [VuePress 2](https://v2.vuepress.vuejs.org/) + [vuepress-theme-gungnir](https://github.com/Renovamen/vuepress-theme-gungnir).

## How to add a post

Add a .md file under the `docs/posts/` directory. Filename format is `YYYY-MM-DD-<your filename here>`

Post header format:

```
---
layout: Post
title: <Title of the post. Required.>
subtitle: <Subtitle of the post. Optional.>
author: <Author of the post. Required.>
date: <YYYY-MM-DD>
useHeaderImage: <true | false. Optional.>
headerImage: <Header image. Can be a absolute http url or a relative file path. Required.>
headerMask: <A CSS color value. e.g: rgba(40, 57, 101, .4). Optional.>
catalog: <Whether to set up a catalog on the post page. Default: false.>
original: <The origin address of the post. Optional.>
tags:
  - <tag1>
  - <tag2>
  - ...
---

A short description of the post ...

<!-- more -->

Here is the content of the post ...
```

Example:

```
---
layout: Post
title: Day 1
subtitle: Nothing to write about
author: Nobody
date: 9999-12-31
useHeaderImage: true
headerImage: https://this/is/a/image/path.png
headerMask: rgba(40, 57, 101, .4)
catalog: true
original: https://this/is/a/url/to/a/post
tags:
    - post101
    - Nothing
    - DONE
---

Nothing to write about.

<!-- more -->

## TODO

Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores, voluptate? Iste maiores similique optio voluptatum sunt modi mollitia labore repellat aspernatur, facere eius, officia culpa perspiciatis asperiores impedit reprehenderit non!
```

The value of the `headerImage` can be a local file path

```
headerImage: /img/header.jpg
```
