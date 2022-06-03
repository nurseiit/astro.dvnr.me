---
layout: '../../layouts/BlogPost.astro'
setup: |
  import Cool from '../../components/Author.astro'
title: '#quitFacebookEcosystem'
publishDate: 25 Jun 2020
name: Nate Moore
value: 128
description: Why leave social media backed by Big Brother - Facebook?
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

This is so cool!

Let's check `inline styles;`!

Do variables work {frontmatter.value \* 2}?

```javascript
// Example JavaScript

const x = 7;
function returnSeven() {
  return x;
}
```
