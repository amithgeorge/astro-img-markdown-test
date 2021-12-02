---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
  import imgUrl from '../../images/astronaut.jpg'

title: Hello world!
publishDate: 12 Sep 2021
name: Nate Moore
value: 128
description: Just a Hello World Post!
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

This is so cool!

<img src={imgUrl} alt="astronaut floating in space" />

<!-- <p>{imgUrl}</p> -->
