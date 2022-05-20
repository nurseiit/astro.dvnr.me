---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Ruined expectations from UNIST
publishDate: 26 May 2020
name: Nate Moore
value: 128
description: Rants about what I like and (mostly) dislike about my university.
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

This is so cool!

Do variables work {frontmatter.value \* 2}?

```javascript
// Example JavaScript

const x = 7;
function returnSeven() {
  return x;
}
```
