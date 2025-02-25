---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /assets/intro.jpg
# some information about your slides (markdown enabled)
title: Software Development | Foundations
info: |
  ## Software Development | Foundations
# apply unocss classes to the current slide
class: text-left
drawings:
  persist: false
transition: slide-left
mdc: true
---

# CSS - part 3/3
Software Development Bootcamp - Circuit Stream
- [ ] Create a responsive website layout using CSS
- [ ] Discuss different ways of creating website layouts: 
   - [ ] flexbox, grid, float, position

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
TODO: fill in anchor href above to point to github repo for these slides
- take attendance
- verify previous zoom video uploaded
- I updated my menu repo https://github.com/avcoder/css-temp2
-->

---
transition: slide-left
---

# Summary from Last Class
(5 min)

- What parts of the box model affects the total width an element?
- What's the diffference between `box-sizing: content-box` and `box-sizing: border-box`
- Name all CSS properties involved in making this?
- Where would you place the `<div>` tags?

<img src="/assets/stripe.png" style="height: 350px">


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
-->

---
layout: image-right
transition: slide-left
image: /assets/stripe.gif
backgroundSize: 500px 450px
class: text-left
---

# Summary from Last Class
(5 min) 

- How pseudo-class is used to make this?
- Goto https://codepen.io/codevilla/pen/zxYKWjp 

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
-->


---
transition: slide-left
---

# Exercise: Layouts | box model and position
(30 min) Goto: https://codepen.io/codevilla/pen/MYWjYVz
|                                                     |                             |
| --------------------------------------------------- | --------------------------- |
| `display: block` | vertical layout, margins may collapse between other block elements |
| `display: inline` | horizontal layout |
| `display: inline-block` | hybrid of block and inline |
| `position` | manipulate the location of an element |
| `float` | designed to be used for positioning images |
| `display: flex` | CSS Flexbox Layout  |
| `display: grid` | CSS Grid Layout |

<!-- 
- READ: https://css-tricks.com/almanac/properties/p/position/
-->

---
transition: slide-left
---

# Exercise: Floats
(15 min) Originally designed for wrappping text around images

- Goto: https://codepen.io/codevilla/pen/wBvzxWV 

<!-- 
- READ: https://developer.mozilla.org/en-US/docs/Web/CSS/float
-->

---
layout: image-right
transition: slide-left
image: /assets/sarahdrasner.png
backgroundSize: 500px 450px
class: text-left
---

# 10 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- ⊞ [CSS Grid Course](https://www.youtube.com/watch?v=T-slCsOrLcc&list=PLu8EoSxDXHP5CIFvt9-ze3IngcdAc2xKG)
- ⊿ [Trianglify.io](https://trianglify.io/)
- 📏 [Centering in CSS](https://css-tricks.com/centering-css-complete-guide/)
- ⏳ [CSS Filters](https://css-tricks.com/almanac/properties/f/filter/)
- ⚙️ [CSS Grid Generator](https://cssgrid-generator.netlify.app/)
- 🫥 [The Great Divide](https://css-tricks.com/the-great-divide/)
- 🥤 [Making CSS Animations Feel Natural](https://css-tricks.com/making-css-animations-feel-natural/)
- 🦑 [Responsive Designs](https://css-tricks.com/beyond-media-queries-using-newer-html-css-features-for-responsive-designs/)
- ◘ [Centering a Div](https://www.joshwcomeau.com/css/center-a-div/)
- 🎚️ [CSS Gradient Generator](https://cssgradient.io)

<!-- 
- remember: take attendance
-->


---
transition: slide-left
---

# Exercise: Flexbox
(20 min) Recognize how flexbox can be applied in website development

- Goto: https://codepen.io/codevilla/pen/pvoEZLN and experiment with https://css-tricks.com/snippets/css/a-guide-to-flexbox/

<!-- 
READ: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
-->

---
transition: slide-left
---

# Exercise: Grid
(20 min) Recreate the following using CSS Grid

- Goto: https://codepen.io/codevilla/pen/dPypjEr and experiment with https://css-tricks.com/snippets/css/complete-guide-grid/
<img src="/assets/golden.jpg" alt="" style="height: 400px">

<!-- 
- How do you inspect an element with :hover?
-->

---
transition: slide-left
---

# Exercise: Layout
(remainder of time) 
- Goto: https://codepen.io/codevilla/pen/WbNGarg
- Recreate [this section](https://sharon-yi.com/) following using any combination of layout techniques we covered
<img src="/assets/portfoliosample.png" alt="" style="height: 400px">

<!-- 
- How do you inspect an element with :hover?
-->

---
transition: slide-left
---

## For homework:

- Apply what you've learned so far to your "Personal Website" assignment (aka Portfolio assignment)
   - Validate HTML https://validator.w3.org/
   - Validate CSS https://jigsaw.w3.org/css-validator/

<!--
- take attendance
-->
