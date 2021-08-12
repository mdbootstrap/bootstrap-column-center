# How to center Bootstrap column? 

To center the column horizontally or vertically use [Flexbox](https://mdbootstrap.com/docs/standard/layout/flexbox/) utilities. Add `.d-flex .justify-content-center` classes to the parent element of the column (it should be `.row` element ) to center it horizontally.

Useful resources:

* [Flexbox Docs](https://mdbootstrap.com/docs/standard/layout/flexbox/)
* [Flexbox Generator](https://mdbootstrap.com/docs/standard/tools/builders/flexbox/)
* [Horizontal Alignment Docs](https://mdbootstrap.com/docs/standard/layout/horizontal-alignment/)

## Basic example

```html
<!--Grid row-->
<div class="row d-flex justify-content-center">
  <!--Grid column-->
  <div class="col-md-6">This column is centered</div>
  <!--Grid column-->
</div>
<!--Grid row-->
```

#### Much more examples and a detailed description can be found at [📄 Documentation page](https://mdbootstrap.com/how-to/bootstrap/column-center/)
