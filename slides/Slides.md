---

marp: true
footer: 'https://github.com/SirSplat/dvdrental-db-design-intro'

---

# Introduction
<!-- ![bg right:60%](img/spiralstairs.png) -->
![bg opacity](img/spiralstairs.png)

<!-- ![](img/Screenshot%202024-07-31%20at%2015.14.58.png) -->

<!--
Let's go on a little journey "down the rabbit hole" - or up in this case :) that is one of PostgreSQL's sample databases, The DVD Rental database.

Here we will cover
* Business requirements -> Problem Statement
* Requirements gathering
* conceptual design
* logical design
* physical design
* write pgTAP tests
* write sqitch migration scripts
-->

---

# Introduction
![bg opacity](img/spiralstairs-requirements.png)
## Problem Statement

<!-- Not sure if I should give it here !!! -->

---

# Introduction
![bg opacity](img/spiralstairs-conceptual.png)
## Problem Statement
## Conceptual Design

---

# Introduction
![bg opacity](img/spiralstairs-logical.png)
## Problem Statement
## Conceptual Design
## Logical Design

---

# Introduction
![bg opacity](img/spiralstairs-physical.png)
## Problem Statement
## Conceptual Design
## Logical Design
## Physical Design

---

## The cold hard truth
![bg opacity](img/coldhardtruth.png)

- Item 1
- Item 2
- Item 3
<!-- Can have multiple on a slide -->

---

## Slide 2
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
