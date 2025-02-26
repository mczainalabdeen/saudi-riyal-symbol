# Saudi Riyal Symbol Font

This repository contains a custom icon font that provides a **Saudi Riyal (SAR) symbol** for use in web applications. The font is designed for seamless integration and supports multiple formats for cross-browser compatibility.

### Brand Symbol Guidelines
Refer to the **Saudi Central Bank's Brand Symbol Guidelines** for more information:  
[Saudi Central Bank Guidelines](https://www.sama.gov.sa/ar-sa/Currency/SRS/Documents/Guidelines.pdf)


## Installation

### 1. Use via CDN (Recommended)

You can quickly include the font using the CDN link:

```html
<link rel="stylesheet" href="https://unpkg.com/saudi-riyal-symbol@latest/dist/saudi-riyal-symbol.css">
<link rel="stylesheet" href="https://unpkg.com/saudi-riyal-symbol@latest/dist/saudi-riyal-symbol.min.css">
```

### 2. Self-Hosting Installation

#### Download the Font Files

Ensure you have the following font files in  `dist/fonts/` directory:

- `saudi-riyal-symbol.eot`
- `saudi-riyal-symbol.woff`
- `saudi-riyal-symbol.ttf`
- `saudi-riyal-symbol.svg`

You Can Download it from here: [Download](https://github.com/mczainalabdeen/saudi-riyal-symbol/releases/latest)

#### Include the CSS

Add the following CSS to your stylesheet:

```css
@charset "#";

@font-face {
  font-family: 'Saudi Riyal Symbol';
  src: url('fonts/saudi-riyal-symbol.eot?ldbsd8');
  src: url('fonts/saudi-riyal-symbol.eot?ldbsd8#iefix') format('embedded-opentype'),
       url('fonts/saudi-riyal-symbol.ttf?ldbsd8') format('truetype'),
       url('fonts/saudi-riyal-symbol.woff?ldbsd8') format('woff'),
       url('fonts/saudi-riyal-symbol.svg?ldbsd8#sar-symbol') format('svg');
  font-weight: normal;
  font-style: normal;
  font-display: block;
}

[class^="sr-symbol"], [class*="sr-symbol"], sr, i.sr {
  font-family: 'Saudi Riyal Symbol' !important;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
}

.icon-SR:before, sr::before, i.sr:before {
  content: "\23"; /* HTML Entity: &#x23; */
}
```

## Usage in HTML

You can use the font symbol in your HTML as follows:

#### Using a `<span>` or `<i>` tag:
```html
<i class="sr"></i>
```

#### Using a custom tag:
```html
<sr></sr>
```

#### Using a class:
```html
<span class="icon-SR"></span>
```
## Usage in any Text Editor Like MS Office

You can use the font symbol in your editor by select font name ( <span style="color: #2DAA9E;"> saudi-riyal-symbol </span> ) and type:
```html

#
```
## Compatibility

This font is supported on modern browsers, including:

✅ Google Chrome  
✅ Mozilla Firefox  
✅ Microsoft Edge  
✅ Safari  
✅ Opera  

## License

This font is provided under the **MIT**. Make sure to follow the usage guidelines accordingly.

---

For any questions or support, feel free to  visit: [**Zainalabdeen.io**](https://zainalabdeen.io)

