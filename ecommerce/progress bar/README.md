# Progress Bar Checkout

The Progress Bar Checkout is a lightweight library that allows you to easily add a progress bar at different stages of the checkout process on your e-commerce site. Simply integrate the appropriate classes to highlight the current payment step.

## Use

### HTML integration

Add the progress bar HTML structure to the appropriate location in your page.

```html
<div class="progress__bar">
  <div class="progress__bar--element cart">Panier</div>
  <div class="progress__bar--element checkout">Validation</div>
  <div class="progress__bar--element confirmation">Confirmation</div>
</div>
```

### Enabling Items

Add the disabled class to the items you want to disable in the progress bar.

````html
<div class="progress__bar--elements-container">
  <div class="progress__bar--element">Panier</div>
  <div class="progress__bar--element ">Validation</div>
  <div class="progress__bar--element disabled">Confirmation</div>
</div>
````

### customize

You can customize the appearance of the progress bar by modifying the CSS file as needed.