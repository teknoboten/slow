# SLOW

Random code bits for the AWG website

## Style Customizations

### Category Headers

```css
/*hide second level categories headers*/
.ec-size .ec-store .grid-category__wrap {
  display: none;
}
```

### Family Open Play

```css
/*Hide Add to Bag button for family open play*/
.ec-store**product-page--790180993 .details-product-purchase**controls {
  display: none;
}

/*Hide In stock text for family open play*/
.ec-store**product-page--790180993 .product-details-module**title {
  display: none;
}

.ec-store**product-page--790180993 .details-product-price**value {
  display: none;
}

.ec-size .ec-store .details-product-purchase\_\_qty {
  display: none;
}
```

### CSS from LS support

```css
/*Hide Add to Bag button for individual product*/
.ec-store__product-page--PRODUCTID .details-product-purchase__controls {
  display: none;
}

/*Hide price for individual product*/
.ec-store__product-page--PRODUCTID .product-details-module__title {
  display: none;
}
```

### Serra's janky tings

```css
/*Hide price for individual product*/
.ec-store__product-page--790180993 .details-product-price__value {
  display: none;
}

.ec-store__product-page--790180993 .details-product-purchase__qty {
  display: none;
}

.ec-size .ec-store .details-product-purchase__qty {
  display: none;
}

/* hide second level categories headers*/
.ec-size .ec-store .grid-category__wrap {
  display: none;
}
```
