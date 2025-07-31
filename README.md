# Cat Painting Project – Responsive Web Design (freeCodeCamp)

Welcome to the **Cat Painting** project, part of the Responsive Web Design curriculum on [freeCodeCamp](https://www.freecodecamp.org/)! This project is a creative exercise where you use only HTML and CSS to "paint" a cat—without any images—by combining shapes, borders, and positioning.

## What I Learned

### 1. CSS Positioning
- **`position: relative` and `position: absolute`**: I learned how to use these properties to precisely place elements on the page. By setting a parent container to `position: relative`, I was able to use `position: absolute` on child elements to place the cat’s features (like eyes, ears, nose, etc.) exactly where I wanted them.
- **Layering with `z-index`**: To make sure certain parts of the cat appeared on top of others, I learned to use the `z-index` property.

### 2. Border Radius
- **Creating Shapes**: I used the `border-radius` property to turn squares and rectangles into circles and ovals. For example:
  - `border-radius: 50%` makes a perfect circle.
  - Asymmetrical values (like `border-radius: 50% 50% 30% 30%`) create unique, organic shapes, perfect for ears, cheeks, or the cat’s body.
- **Soft Edges**: Border radius helped give the cat a soft, friendly look by rounding off hard corners.

### 3. Creativity with Simple CSS
- I combined different CSS properties (background color, width, height, borders, shadows, etc.) to simulate the look of a cat.
- I realized how powerful CSS can be for creating art without using images.

## Example CSS Snippet

```css
.cat-head {
  position: relative;
  width: 200px;
  height: 180px;
  background: #f3cba5;
  border-radius: 50% 50% 45% 45%;
  margin: 0 auto;
}
.cat-ear-left {
  position: absolute;
  top: -40px;
  left: 20px;
  width: 60px;
  height: 80px;
  background: #f3cba5;
  border-radius: 70% 30% 100% 0% / 60% 60% 40% 40%;
  transform: rotate(-15deg);
}
```

## Why This Matters

This project helped me understand the fundamentals of layout in CSS, especially how to control the position and shape of elements. These skills are crucial for making responsive and visually appealing websites.

---

**Check out my cat painting below and try creating your own!**
