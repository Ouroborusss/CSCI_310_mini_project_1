```html
<div class="wrapper">
  <div>Image in here</div>
  <div class="header-text">text in here</div>
</div>

```

```css
.wrapper {
  display: grid;
  grid-template-columns: 200px 600px;
  height: 200px;
  padding: 10px;
}

* {
  box-sizing: border-box;
}

.wrapper {
  border: 2px solid #f76707;
  border-radius: 5px;
  background-color: #fff4e6;
}

.wrapper > div {
  border: 2px solid #ffa94d;
  border-radius: 5px;
  background-color: #ffd8a8;
  padding: 1em;
  color: #d9480f;
}

.header-text {
  align-self: end;
}
```
