---

marp: true
theme: custom-default
footer: 'https://github.com/SirSplat/dvdrental-db-design-intro'

---

<!--
Let's go on a little journey through the wormhole that is the DVD Rental database, one of PostgreSQL's sample databases
    We'll take it as is and try to bring it up to date.
    It's been years since the DVDRental company was established in the USA,
-->
# Introduction
![bg right](https://picsum.photos/800/600)

---

<!-- Why can I not see my "Speaker Notes" !!!!!! -->

## Slide 1

- Item 1
- Item 2
- Item 3
<!-- Can have multiple on a slide -->

---

## Slide 2
<!-- Can also do a multiline
comment that will show in notes -->

![Image](https://picsum.photos/800/600)

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
