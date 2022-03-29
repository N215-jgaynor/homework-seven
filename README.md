# Homework Seven

## Web 4 Link

https://in-info-web4.informatics.iupui.edu/~jgaynor/homework-seven/#

## Summary

In addition to the skills developed in prior homework assignments (such as the use of responsive/adaptive design and variables), this task involved the use of mixins. I found these to be super helpful for replicating styling in different pages while still being able to make small changes as necessary. An example of a mixin in displayed below.

```css
@mixin promo($bgImage) {
  height: 304px;
  width: 235px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url($bgImage);
}

.tour-desc-header {
  @include tourDescHeader("../images/tour-09.jpg");
}

.tour-desc-img-container {
  @include tourDescImgContainer;
}
```

This project simply continued the last one by finishing out the website with the special offers, blog and contact pages. In these pages I utilized both variables and mixins to optimize my code.
