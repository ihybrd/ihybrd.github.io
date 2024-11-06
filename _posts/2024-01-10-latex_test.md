---
layout: post
title: "MathJax Example"
---

<!-- Include the MathJax script for LaTeX rendering -->
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]},
        "HTML-CSS": { scale: 90 }
    });
</script>

# MathJax on GitHub Pages

This is an example of using MathJax to render LaTeX on a GitHub Pages site.

Here’s an inline equation: $E = mc^2$

And here’s a display equation:
$$
\int_{a}^{b} f(x) \,dx
$$

You can include as many equations as you need. MathJax will render these expressions when the page loads.
