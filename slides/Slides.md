---

marp: true
footer: 'https://github.com/SirSplat/dvdrental-db-design-intro'

---

# Introduction
![bg opacity](img/spiralstairs.png)

<!--
Let's go on a little journey "down the rabbit hole" that is the DVD Rental database (one of PostgreSQL's sample databases)

We'll take it as is and attempt
-->

---

# Introduction
![bg opacity](img/spiralstairs-requirements.jpeg)

<!-- Not sure WTF is going on here !!! -->

---

## The cold hard truth
![bg opacity](img/coldhardtruth.png)

-
- Item 2
- Item 3
<!-- Can have multiple on a slide -->

---

## Slide 2

![Image](https://picsum.photos/800/600)

<!-- Can also do a multiline
comment that will show in notes -->

---

## Slide 3

> This is a quote.

---

## Slide 4

| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | Item 2   |
| Item 3   | Item 4   |

---

![bg opacity](https://picsum.photos/800/600?image=53)
## Slide 5

<div class="columns">
<div>

## Left

- 1
- 2

</div>
<div>

## Right

- 3
- 4

</div>
</div>

---

## Slide 6

<i class="fa-brands fa-twitter"></i> Twitter:
<i class="fa-brands fa-mastodon"></i> Mastodon:
<i class="fa-brands fa-linkedin"></i> LinkedIn:
<i class="fa fa-window-maximize"></i> Blog:
<i class="fa-brands fa-github"></i> GitHub:

---

# <!--fit--> Large Text

---

<!-- Needed for mermaid, can be anywhere in file except frontmatter -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# Mermaid

<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
</div>

---

<section id="1">
  <h1>Bullet list</h1>
  <ul>
    <li>One</li>
    <li>Two</li>
    <li>Three</li>
  </ul>
</section>
<section id="2" data-marpit-fragments="3">
  <h1>Fragmented list</h1>
  <ul>
    <li data-marpit-fragment="1">One</li>
    <li data-marpit-fragment="2">Two</li>
    <li data-marpit-fragment="3">Three</li>
  </ul>
</section>
