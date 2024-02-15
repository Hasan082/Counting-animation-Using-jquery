# Counter Animation Plugin

The Counter Animation Plugin is a lightweight jQuery plugin that allows you to animate counting from a start value to an end value. It provides a simple and customizable way to create counter animations for various purposes.

## Features

- Animates counting from a start value to an end value.
- Customizable increment value, hold time, and animation duration.
- Smooth fade-in effect when the counter comes into view.

## Usage

### Prerequisites

Make sure you have jQuery included in your HTML document. You can include it from a CDN or host it locally.

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
```

### Installation

Download the `countinganimation.min.js` file and include it in your HTML document.

```html
<script src="countinganimation.min.js"></script>
```

### HTML Structure

Add HTML markup for the counter element within your document.

```html
<div class="counter-container">
    <div class="counter">1997</div>
</div>
```

### JavaScript Initialization

Initialize the Counter Animation Plugin on the counter element.

```javascript
$(document).ready(function () {
    $('.counter').counterAnimation({
        startValue: 1997,
        endValue: 2022,
        increment: 1,
        holdTime: 5000,
        duration: 100
    });
});
```

### CSS Styling

You can customize the appearance of the counter element using CSS. Here's a sample styling:

```css
.counter {
    font-size: 120px;
    line-height: 0.8;
    text-align: center;
    transition: opacity 1s ease-in-out;
    opacity: 1;
}

.counter-container {
    text-align: center;
    margin: 0 auto;
}
```

## License

This plugin is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit/) file for details.

## Contributing

Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests.

