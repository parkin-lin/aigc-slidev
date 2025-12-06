---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# Welcome to Slidev

Presentation slides for developers

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
src: ./pages/what-is-slidev.md
---

---
src: ./pages/navigation.md
---

---
src: ./pages/table-of-contents.md
---

---
src: ./pages/code.md
---

---
src: ./pages/shiki-magic-move.md
---

---
src: ./pages/components.md
---

---
src: ./pages/themes.md
---

---
src: ./pages/clicks-animations.md
---

---
src: ./pages/motions.md
---

---
src: ./pages/latex.md
---

---
src: ./pages/diagrams.md
---

---
src: ./pages/draggable-elements.md
---

---
src: ./pages/imported-slides.md
hide: false
---

---
src: ./pages/monaco-editor.md
---

---
src: ./pages/learn-more.md
---
