---
layout: page
title: Diagram
permalink: /diagram/
---

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)

<script type="text/javascript"

  src="https://unpkg.com/mermaid@8.0.0-rc.8/dist/mermaid.min.js">

</script>

<script>

$(document).ready(function() {

    mermaid.initialize({

        theme: 'forest'

    });

});

</script>

<div class="mermaid">

    graph TD

      B[peace]

      B-->C[fa:fa-ban forbidden]

      B-->D(fa:fa-spinner);

      B-->E(fa:fa-camera-retro perhaps?);

</div>

[jekyll-organization]: https://github.com/jekyll
