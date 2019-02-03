# Owl Carousel 2.3.4

The built assets for Drupal 8 composer install

To use in your theme, add this into your libraries yml

```yaml
owlcarousel:
  version: 2.3.4
  css:
    component:
      ../../../libraries/owlcarousel/assets/owl.carousel.css: {}
      ../../../libraries/owlcarousel/assets/owl.theme.default.min.css: {}
  js:
    ../../../libraries/owlcarousel/owl.carousel.min.js: {}
  dependencies:
    - core/jquery
    - core/drupal
    - core/drupalSettings
    - core/jquery.once
```
