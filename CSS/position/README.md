# CSS POSITIONS
The "position" property in CSS specifies the type of positioning method used for an element (tag).

There are five different position values:
- `static`
- `relative` 
- `absolute`
- `fixed`
- `sticky`

## 1. Static
HTML elements are positioned static by default.Static positioned elements are not affected by the top, bottom, left, and right properties.In most cases, you won't explicitly set an element's position to `static` unless you want to override a previously set position value or explicitly declare the default behavior.

## 2. Relative

Relative positioning allows an element to be shifted relative to its normal position in the document flow. This means the element remains within the document flow but can be shifted by specified values such as "left," "top," "right," and "bottom." It is useful for determining where the element should be placed without affecting the positions of other elements.

```css
.relative-example {
  position: relative;
  left: 20px;
  top: 10px;
}
```
## 3.Absolute
An element with the position: absolute; property positions itself relative to the nearest ancestor element that has a position: relative; (or position: absolute; or position: sticky;) property. If there is no ancestor with a position: relative; property, it positions itself relative to the document. This means the element can be positioned anywhere within the page, but this might affect the positions of other elements.

```css
.absolute-example {
  position: absolute;
  left: 50px;
  top: 50px;
}
```
## 4. Fixed
An element with the position: fixed; property is positioned relative to the viewport (the browser window or the device screen), regardless of scrolling. This means it stays fixed in its specified position relative to the viewport even as you scroll up or down the page. The positioning of a fixed element is determined by values set for left, top, right, and bottom, and it does not move when the page is scrolled.
```css
div.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 300px;
  border: 3px solid #73AD21;
}
```
## 5. Sticky
The position: sticky; property allows an element to follow scrolling until it reaches a defined threshold, at which point it becomes fixed in place. For example, you might want an element to stick at the top of the page once it reaches the top edge. This behavior combines aspects of both relative and fixed positioning, making it ideal for creating sticky elements such as navigation menus that remain visible as users scroll down the page.

```css
div.sticky {
  position: sticky;
  top: 0;
}
```
