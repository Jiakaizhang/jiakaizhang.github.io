---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is jiakai Zhang and ...

Personal Lab
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.



<h2>Sponsored by:</h2>

<div class="sponsor-grid">
  <img src="{{ '/images/sponsors/nm_epscor.png' | relative_url }}" alt="EPSCoR">
  <img src="{{ '/images/sponsors/nsf.jpg' | relative_url }}" alt="NSF">
  <img src="{{ '/images/sponsors/NIH.png' | relative_url }}" alt="NIH">
  <img src="{{ '/images/sponsors/emnrd.png' | relative_url }}" alt="EMNRD">
</div>


<style>
.sponsor-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  align-items: center;
  justify-items: center;
  column-gap: 15px;
  row-gap: 20px;
  margin: 25px 0;
}

.sponsor-grid img {
  width: 100%;
  max-width: 220px;
  height: 200px;
  object-fit: contain;
}

@media (max-width: 600px) {
  .sponsor-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
</style>



