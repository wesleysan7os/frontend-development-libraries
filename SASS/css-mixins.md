```html
<style type='text/scss'>
  @mixin border-radius($radius) {
    -webkit-box-shadow: $radius;
    -moz-box-shadow: $radius;
    -ms-box-shadow: $radius;
    border-radius: $radius;
  }


  #awesome {
    width: 150px;
    height: 150px;
    background-color: green;
    @include border-radius(50px);
  }
</style>

<div id="awesome"></div>
```