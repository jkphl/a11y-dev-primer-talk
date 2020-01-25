---
title: "6.a Visually hide content"
css: html css
theme: tertiary
---
## 6.a Visually hide content

<figure class="side-by-side">
<figcaption>

- Hide for all users: `hidden` attribute / `display: none`
- Hide from display, but keep for assistive technology («**visually hidden**»)
- Example: `<span class="hide-element">Toggle </span>Menu`

</figcaption>

    .hide-content {
        white-space: nowrap !important;
        overflow: hidden !important;
        text-indent: 300% !important;
    }
    
    .hide-element {
        position: absolute !important;
        overflow: hidden !important;
        clip: rect(0 0 0 0) !important;
        height: 1px !important;
        width: 1px !important;
        margin: -1px !important;
        padding: 0 !important;
        border: 0 !important;
    }

</figure>
