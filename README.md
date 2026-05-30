# Underline-Hover-Animations

### ✨ About

***Underline Hover Animations*** is a collection of 6 link hover effects with pure HTML and CSS. Each variant uses `::after` to create an animated underline that grows, slides or fills on hover.

---

### 💡 What i learned

- `flex-wrap` — lets flex items wrap to the next line when they don't fit in one row, instead of overflowing or shrinking
- `transform-origin` — defines the point where a transformation starts. In this project, changing it from `left` to `center` or `right` is what makes the underline grow from different directions
- `:hover` — a CSS pseudo-class that applies styles only when the mouse is over the element. Combined with `::after`, it's what triggers the animation
- `::after` — a pseudo-element that creates an invisible child element after the content. Here it's used to draw the underline without adding extra HTML tags
- `content: ''` — required for `::after` to render at all. Even empty, it must be there, without it the element simply doesn't appear
- `z-index` — controls wich element appears on top when two overlap. In the highlight variant, setting `z-index: -1` on `::after` pushes the colored fill behind the next
- `calc()` — lets you do math directly in CSS, mixing different units. Used as `width: calc(100% + 8px)` to make the highlight a little wider than the text itself

---

### 🛠️ Built With

- HTML
- CSS

---

### 🎬 Preview

https://github.com/user-attachments/assets/fa163839-c5a3-420b-8bdf-0eaba4d9e941
