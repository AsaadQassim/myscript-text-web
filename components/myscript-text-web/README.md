# myscript-text-web

The easy way to integrate text handwriting recognition in your web app.

![myscript-text-web preview](./preview.gif)

```html
<html>
<head>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="bower_components/myscript-text-web/myscript-text-web.html">
</head>
<body>
    <myscript-text-web 
        applicationkey="#PUT YOUR MYSCRIPT CDK APPLICATION KEY HERE#" 
        hmackey="#PUT YOUR MYSCRIPT CDK HMAC KEY HERE#" 
        language="en_US">
    </myscript-text-web>
</body>
</html>
```

## Examples

* [Simple text demo](./demo/index.html)
* [Superimposed demo](./demo/superimposed.html)
* [Programmatic init](./demo/programmatic-init.html)
* [Customize style](./demo/customstyle.html)
* [Customize candidates output](./demo/customcandidates.html)
* [Error handling](./demo/init-error.html)
* [Get statistics](./demo/stats.html)

[Test it live](https://myscript.github.io/myscript-text-web/components/myscript-text-web/demo/)!

## What is it about?

myscript-text-web is a web component that can be used in every web application (whatever the JavaScript library you are using) to bring handwriting recognition. It integrates all you need:  
* Signal capture,
* Nice digital ink rendering,
* Plug with MyScript CDK to bring handwriting recognition.

## Installation

**Bower**: `bower install myscript-text-web`

## Start using myscript-text-web

1. Create an account on the [Developer portal](https://dev.myscript.com/), which will allow you to generate an application key and HMAC key.  

2. Import Web Components' polyfill

    `<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>`

3. Import Custom Element

    `<link rel="import" href="bower_components/myscript-text-web/myscript-text-web.html">`

3. Use it

    `<myscript-text-web applicationkey="#PUT YOUR MYSCRIPT CDK APPLICATION KEY HERE#" hmackey="#PUT YOUR MYSCRIPT CDK HMAC KEY HERE#" language="ja_JP"></myscript-text-web>`
    
## Documentation 

The API Reference is available here: [https://myscript.github.io/myscript-text-web/](https://myscript.github.io/myscript-text-web/) 

## Contribute

If you wish to contribute to myscript-text-web, feel free to fork it!
Please sign our [Contributor License Agreement](CONTRIBUTING.md) before submitting your pull request.

## Share your feedback

Made a cool app with myscript-text-web? We would love to hear about you!
We’re planning to showcase apps using it so let us know by sending a quick mail to [myapp@myscript.com](mailto://myapp@myscript.com)

## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)