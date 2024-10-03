# The anatomy of a CSS selector

![Anatomy of a CSS rule](https://pages.git.generalassemb.ly/modular-curriculum-all-courses/intro-to-css/fundamentals/assets/css-syntax.png)

**Selectors**: Used to target the element(s) to be styled and range from simple to incredibly complex.

## 1. Element Selector

```css
p {
  color: red;
}
```

To target a specific HTML element, such as `p`.

## 2. Class Selector

```css
.container {
  background-color: green;
}
```

To target all classes. It starts with a dot (`.`).

## 3. ID Selector

```css
#contact {
  font-weight: bold;
}
```

To target a specific id. It starts with a `#` symbol.

## 4. Descendant Selector

```css
div p {
  font-size: 20px;
}
```

To target element nested within another element, separated by a space (` `) in between.

## 5. Attribute Selector

```css
input[type="text"] {
  margin: 5px;
}
```

To target element based on their attributes.

## 6. Child Selector

```css
ul > li {
  border: 1px solid black;
}
```

To target element nested within another element, that are direct children, separated by a `>` in between.

## 7. Adjacent Sibling Selector

```css
div + p {
  padding: 10px;
}
```

To target element that is immediately after another, separated by a `+` in between.

### References

For more information on more sophisticated CSS selectors, refer to [CSS Tricks](https://css-tricks.com/almanac/selectors/).
