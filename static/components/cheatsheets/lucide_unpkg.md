# Lucide for Vanilla JavaScript

This is the cheatsheet for using the CDN version of Lucide. 

## HTML Tag

Inside the ```<body>``` tag, use this as a placeholder for the icons:
```<i data-lucide="icon-name"></i>```.

## JavaScript Postload

At the end of the ```<body>``` tag, include two lines of code:
* For development, use ```<script src="https://unpkg.com/lucide@latest/dist/umd/lucide.js"></script>```;
* For production, use ```<script src="https://unpkg.com/lucide@latest"></script>```;
* ```<script>lucide.createIcons()</script>```.

## Advanced Usage

For more advanced usage, visit [Lucide's instruction page](https://lucide.dev/guide/packages/lucide#advanced-usage).
