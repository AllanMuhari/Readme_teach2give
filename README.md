# CSS BOX MODEL

## Introduction

The CSS box model is a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. It is used to create space between elements and to control the element's dimensions and appearance.

## Content

1. [Box Model](#box-model)
2. [Margin](#margin)
3. [Border](#border)
4. [Padding](#padding)
5. [Content](#content)
6. [Conclusion](#conclusion)
7. [References](#references)

## Box Model

<a name="box-model"></a>

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

![Box model image ](Assets/box_model.png)

- Content - The content of the box, where text and images appear
- Padding - Clears an area around the content. The padding is transparent
- Border - A border that goes around the padding and content
- Margin - Clears an area outside the border. The margin is transparent

```css
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```

## Margin

<a name="margin"></a>

The margin clears an area outside the border. The margin does not have a background color, it is completely transparent.

```css
.content {
  margin: 20px;
}
```

## Border

<a name="border"></a>

The border goes around the padding and content. The border is the actual line that goes around the padding and content.

```css
.content {
  border: 15px solid green;
}
```

## Padding

<a name="padding"></a>

The padding clears an area around the content. The padding is affected by the background color of the box.

```css
.content {
  padding: 50px;
}
```

## Content

<a name="content"></a>

The content is where text and images appear.

```css
.content {
  content: "Content";
}
```

## Conclusion

<a name="conclusion"></a>

The CSS box model is a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. It is used to create space between elements and to control the element's dimensions and appearance.

## References

<a name="references"></a>

- [CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
- [CSS Box Model MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/-CSS_Box_Model/Introduction_to_the_CSS_box_model)
- [CSS Box Model - YouTube](https://www.youtube.com/watch?v=HNgdhp1_kEE)
- [CSS Box Model - CSS Tricks](https://css-tricks.com/the-css-box-model/)
