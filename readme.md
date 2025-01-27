# @vueframe/lite-vimeo-embed

## Basic usage

To use the custom embed you will need to:

1. Include the script
1. Use the element `lite-vimeo` markup and scripting
1. Be happy that you're providing a better user experience to your visitors

```html
<!-- Include the custom element script -->
<script type="module" src="https://cdn.jsdelivr.net/npm/@vueframe/lite-vimeo-embed/+esm"></script>

<!-- Use the element. You may define uses before the scripts are parsed and executed. -->
<lite-vimeo videoid="357274789"></lite-vimeo>
```

## Pro-usage

Use this as your HTML, load the script asynchronously, and let the JS progressively enhance it.

```html
<lite-vimeo videoid="357274789" style="background-image: url('https://i.vimeocdn.com/video/810965406.webp?mw=1600&mh=900&q=70');">
  <div class="ltv-playbtn"></div>
</lite-vimeo>
```
