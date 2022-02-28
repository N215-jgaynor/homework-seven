# Homework Three

## Web 4 Link

https://in-info-web4.informatics.iupui.edu/~jgaynor/homework-four/#

## Summary

This assignment was an introduction to responsive and adaptive design. It took an existing project (the home page of a travel agent business) that was hard coded using pixels and introduced media queries with percentages to make it adaptive.

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

Another use for media queries in this project was to reformat the form so it stacked vertically to fit the browser. This was done through changing the flex direction of the container(s) and adding in additional styling (such as margins). I also targetted the form boxes for each size and set their widths to the variable $form-medium-box-width for easy modification later.

```css
@media screen and (max-width: 900px) {
  .form-content {
    h1 {
      text-align: center;
    }

    .top-boxesOne {
      flex-direction: column;

      .short-box {
        width: $form-medium-box-width;
        margin-bottom: 20px;
      }
    }
```

This project also gave me more practice with setting up a sass compiler in vscode as well as pushing to Github.
