# exa snippets

## html snippets

**Basic HTML Page**

`exa-page`

```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <title>${1:page}</title>
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link href="https://dizwlgtu4iq45.cloudfront.net/common/css/common.css" media="all" rel="stylesheet" type="text/css">
    <link rel="stylesheet" type="text/css" href="https://dizwlgtu4iq45.cloudfront.net/elements/elements.css">
  </head>
  <body>
    <main>
      ${2}
    </main>
    <script title="web components polyfill for custom elements" src="https://cdnjs.cloudflare.com/ajax/libs/custom-elements/1.2.0/custom-elements.min.js"></script>
    <script type="text/javascript" src="https://dizwlgtu4iq45.cloudfront.net/common/js/common.js"></script>
  </body>
</html>
```