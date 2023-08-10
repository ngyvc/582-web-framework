# SCSS

## Top Tips

MOBILE FIRST!!!!!! (For all time. Always.)

## Style Rules

[SCSS Style Rules](https://sass-lang.com/documentation/style-rules/)

## Hierarchy

```scss
.course-list {
  border: 10px solid grey;
  .course {
    &:nth-child(odd) {
      background-color: lightgrey;
    }
    &:hover {
      background-color: yellow;
    }
    border: 1px solid black;
    margin: 1em;
  }
  > h2 {
    color: green;
  }
}

@media screen and (min-width: 768px) {
  .course-list {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    .course {
      background-color: lightsalmon;
    }
  }
}

@media screen and (min-width: 1080px) {
  #app {
    background-color: red;
  }
}
```