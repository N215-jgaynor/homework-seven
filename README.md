# Homework Five

## Web 4 Link

https://in-info-web4.informatics.iupui.edu/~jgaynor/homework-five/#

## Summary

This assignment was the continuation of an introduction to responsive and adaptive design. It took an existing project (the home page of a travel agent business) and added an about page that was also responsive.

For example, I set the nav (shown below) and footer to fit to 80% of the browser from 1280px to 900px, at which point it becomes a set width of 720px for anything smaller than 900px. This styling fits the assignment description (responsive down to 800px) but it would need to be adjusted for smaller viewports.

```css
@media screen and (max-width: 1280px) {
  nav {
    max-width: 80%;
  }
}

@media screen and (max-width: 900px) {
  nav {
    max-width: 720px;
  }
}
```

This project also introduced the "app" ID, in which we will eventually use to dynamically load content onto our pages. For now though, it just serves as a container that centers the content of the about page and defines its width.
