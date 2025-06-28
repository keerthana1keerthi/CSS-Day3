# CSS Box Sizing Demo

This is a simple HTML & CSS project to demonstrate the use of different `box-sizing` properties in CSS.

## 📁 Files Included

- `index.html`: Main HTML file that renders three styled boxes.
- `style.css`: Styles the boxes using `content-box`, `border-box`, and a placeholder for `margin-box`.

## 🎯 Purpose

To help learners visualize how different CSS `box-sizing` values affect the layout and dimensions of HTML elements.

## 🧱 Box Descriptions

### 🟪 Box 1 - Content Box
- Class: `.box1`
- `box-sizing: content-box`
- Padding and border **add** to the element's width and height.
- Demonstrates a variety of borders (top, left, right, bottom) with different styles and colors.
- ⚠️ Note: `border-bottom` has a typo (`doble` should be `double`).

### 🟥 Box 2 - Border Box
- Class: `.box2`
- `box-sizing: border-box`
- Padding and border are **included** in the total width and height.

### 🟦 Box 3 - Margin Box (⚠️ Incorrect)
- Class: `.box3`
- `box-sizing: margin-box` (⚠️ Not a valid CSS value — likely intended as an experiment).
- Uses `border-radius: 50%` to create a circle.

## ✅ How to Run

1. Open `index.html` in a web browser.
2. Observe the three different boxes and how padding/border affects their sizes.

## 🔧 Fix Suggestions

- Update `border-bottom: 3px doble hotpink;` to `border-bottom: 3px double hotpink;`.
- Replace `box-sizing: margin-box;` with a valid value or remove it, as it's not recognized by modern browsers.


