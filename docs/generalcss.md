## Procedure for compilation CSS and generate bundlers
- npm i -g <>
- Use inside your command line Grunt
- step 3
- step 4
- step 5
- setp 6

## app.sass

Short description: This module I'm baby intelligentsia brooklyn hell of, taiyaki post-ironic VHS vape bushwick prism +1 tofu lomo cornhole. Biodiesel brunch franzen, master cleanse asymmetrical hoodie vegan tacos occupy. Chartreuse vinyl bicycle rights PBR&B marfa banh mi meditation farm-to-table VHS hashtag snackwave semiotics unicorn gluten-free yr. Pop-up biodiesel palo santo raclette. Vexillologist chia waistcoat lo-fi.

### Color mixins
- Short description. [Reference](https://devdocs.prestashop.com/1.7/webservice/tutorials/creating-access/)

```
/**

* [Mixin for apply colors]

* $property[Field to validate]

* $value[Errors for customize ]

* $prefixes[True or false if pass validation]

*/

@mixin prefix($property, $value, $prefixes) {
  @each $prefix in $prefixes {
    -#{$prefix}-#{$property}: $value;
  }
  #{$property}: $value;
}

.gray {
  @include prefix(filter, grayscale(50%), moz webkit);
}

//themes/child/assets/src/app.sass line:100

```

### Box mixins
- Short description. [Reference](https://devdocs.prestashop.com/1.7/webservice/tutorials/creating-access/)

```
/**

* [Mixin for apply colors]

* $property[Field to validate]

* $value[Errors for customize ]

* $prefixes[True or false if pass validation]

*/

@mixin prefix($property, $value, $prefixes) {
  @each $prefix in $prefixes {
    -#{$prefix}-#{$property}: $value;
  }
  #{$property}: $value;
}

.gray {
  @include prefix(filter, grayscale(50%), moz webkit);
}

//themes/child/assets/src/app.sass line:100

```












