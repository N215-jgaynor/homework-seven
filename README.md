# Homework Six

## Web 4 Link

https://in-info-web4.informatics.iupui.edu/~jgaynor/homework-six/#

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

This project also introduced the "app" ID, in which we will eventually use to dynamically load content onto our pages. For now though, it just serves as a container that centers the content of the about page and defines its width.
