
# Prissnurran - Mitti

Embeddable price estimator tool.

## Usage

Embed the widget on your website using the following code snippet:

```html
<div id="dpx-widget">
</div>

<script>

  (function () {
      var s = document.createElement('script');
      s.type = 'text/javascript';
      s.async = true;
      s.src = 'https://s3-eu-west-1.amazonaws.com/direktpress/widget.js';
      var x = document.getElementsByTagName('script')[0];
      x.parentNode.insertBefore(s, x);
  })();

</script>
```

The widget will be rendered inside the `#dpx-widget` element. The widget will
use the full width of it's parent container.

### Customizable

To generate a widget with **discounts**, **minimum insertions** and **expire date** set the `data-customizable` attribute to `true`.

```html
<div data-customizable="true" id="dpx-widget">
</div>
```

## Demo

See working example at https://mitti-demo.surge.sh/ and https://mitti-demo.surge.sh/custom.html
