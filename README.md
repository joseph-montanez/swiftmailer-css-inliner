# Swiftmailer Css Inliner Plugin

A swiftmailer plugin that inlines the css (in style tags) into the specific html tags. Uses [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles). Works for both html body or html parts.

## Usage

```php
$mailer = Swift_Mailer::newInstance();

$mailer->registerPLugin(new CssInlinerPlugin());
```

## License

Copyright (c) 2013, OpenBuildings Ltd. Developed by Ivan Kerin as part of [clippings.com](http://clippings.com)

Under BSD-3-Clause license, read LICENSE file.