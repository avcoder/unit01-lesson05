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

# Bootstrap CSS Framework 
Software Development Bootcamp - Circuit Stream
- [ ] Assignment 1 FAQ, go over rubric
- [ ] Understand how frameworks and libraries are used in software dev
- [ ] Utilize Bootstrap to leverage frameworks in website development

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

# Assignment 1 & Upcoming Lab
(10 min)

- Can we use bootstrap? Yes (optional) but ONLY for responsive behaviour (vanilla CSS for everything else)
- Rubric Overview
- Due Date: Sun Mar. 9 midnight EST
- Lab: Wed Mar 5 
   - Labs exist so you get a chance to practice topics you've learned, extend your learning, dig deeper, etc.
   - Labs are completely free form
   - AMA - Ask me Anything
   - Enter your anonymous questions [here](https://docs.google.com/forms/d/e/1FAIpQLSevvGARdHQikso-uLqFCO481MABKE5HofuSrlzEPMNQ2ZLykw/viewform?usp=dialog)

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
HTML: w3c html validator, semantic (no text inside 1 di. ex: must next p tag )
CSS: w3c CSS validator, Does each of your CSS rules actually apply?
Complexity: CSS Grid/Flex or using Responsive Bootstrap grid, position absolute/relative
ProjOrg: Lighthouse, images in folders, internal comments/docs, 
-->

---
transition: slide-left
---

# Intro to Frameworks
(10 min) 

- HTML works together with CSS -- which is more important?
- In s/w dev, there are frameworks and libraries that will help you get faster results with already created solutions
- [State of CSS Survey 2024](https://2024.stateofcss.com/en-US/tools/#css_frameworks) 
- [State of JS Survey 2024](https://2024.stateofjs.com/en-US/libraries/front-end-frameworks/)
- How to decide on a framework?
   - Pre-built Components out of the box
   - Customization ability
   - Long-term Scalability
   - Learning Curve and Docs
   - Maintenance and Updates


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
- "Content is king" - without content, you got nothing.
- My web app didn't use CSS framework
- My website workplace used Bootstrap
- Show how to check if it's been maintained recently
-->


---
transition: slide-left
---

# Exercise: Installing Bootstrap
(30 min) What is Bootstrap and its purpose?  
Try resizing your browser for your portfolio site - does design break?

1. VS Code way using CDN link
2. VS Code way downloading
3. npm way (look for bootstrap.min.css/bootstrap.bundle.min.js files in node_modules)

- Read https://getbootstrap.com/docs/5.3/getting-started/introduction/
- Goto: https://codepen.io/codevilla/pen/MYWbRoO

<!-- 
- Bootstrap is a popular front-end framework used to create responsive web designs with ease.
- It includes predefined CSS classes, JavaScript components, and responsive grid layouts.
- show npmjs.com
- Goto URL and compare: https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css vs bootstrap.css
-->

---
transition: slide-left
---

# Exercise: Breakpoints and containers
(40 min) 

- Breakpoints allow us to define how our design should behave at various screen widths (e.g., mobile, tablet, desktop)
- Containers are used to center and constrain the layout width
- Grids and Columns allow us to create flexible and responsive layouts by dividing the page into rows and columns

- Goto: https://codepen.io/codevilla/pen/OPJbdzQ
- READ https://getbootstrap.com/docs/5.3/layout/breakpoints/

<!-- 
- show common breakpoints (sm, md, lg...)
- show how to use breakpoint-specific classes to control layout
- show actual css file to see where .col-sm-* comes from
-->

---
layout: image-right
transition: slide-left
image: /assets/valhead.png
backgroundSize: 500px 130px
class: text-left
---

# 10 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- 🔥 [Learn Bootstrap by Freecodecamp](https://www.youtube.com/watch?v=-qfEOE4vtxE)
- ❓ Enter your anonymous lab questions [here](https://docs.google.com/forms/d/e/1FAIpQLSevvGARdHQikso-uLqFCO481MABKE5HofuSrlzEPMNQ2ZLykw/viewform?usp=dialog)
- 🎠 (CSS animations](https://css-tricks.com/a-handy-little-system-for-animated-entrances-in-css/)
- 🎨 [Animated Gradients](https://codepen.io/cassie-codes/pen/YzZwyGa/9e06c3f5507b498214bf46dc2f56bd79)
- 🆎 [5 Keys to Accessible Web Typography](https://betterwebtype.com/5-keys-to-accessible-web-typography/)
<!-- 
- remember: take attendance
-->


---
transition: slide-left
---

# Exercise: Emulate stripe.com's hero page
(remainder of time)

- Goto: https://codepen.io/codevilla/pen/GgRNevw

<!-- 
-->

---
transition: slide-left
---

## For homework:

- "Personal Website" assignment (aka Portfolio assignment) due Sun. Mar. 9 midnight EST
- Reminder: try to complete class feedback survey every other week
- Enter your anonymous lab questions [here](https://docs.google.com/forms/d/e/1FAIpQLSevvGARdHQikso-uLqFCO481MABKE5HofuSrlzEPMNQ2ZLykw/viewform?usp=dialog)

<!--
- take attendance
-->
