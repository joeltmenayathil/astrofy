---
title: "Introduction to Astro - Part 1"
description: "Understand the Why and How of Astro to see if it fits your needs."
pubDate: "Jan 05 2024"
heroImage: "/post_img.webp"
badge: "Latest"
tags: ["astro","css","javascript"]
---

In this article, we look into the WHY of Astro before diving into the HOW and WHAT of Astro. Astro is a web framework for building Content-driven sites, like the one you are viewing right now. It can also be used for e-commerce as well. 

But why Astro? Isn’t it wise to use other platforms like Wordpress or CMS systems to build out your website?

The answer is, it depends. Now, lets look at why you would want to use Astro over Wordpress:

1. Developer Focused - First and foremost, Astro is a web framework, which requires the content creator to have an interest in technology and software development. If you are not tech savvy, Astro might not  be the right fit for you.
2. UI Agnostic - If you are a web developer, you can create interactive features and build out complex applications through integrations with frameworks like React, Vue and many more.
3. Fast by Default - This is one of the core principles of Astro. One would not be able to build a slow website with Astro.

To understand why people use Astro, we need to look at its core architecture called **Islands**. You can read about its history over [here](https://docs.astro.build/en/concepts/islands/). In short, an Island is any interactive UI component on the page. Everything on the UI is rendered as static HTML, while only the components that are specified as an Island can be interactive. With islands, client-side JavaScript is only loaded for the explicit interactive components that you mark using `client:*` directives.