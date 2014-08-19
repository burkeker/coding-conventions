Coding conventions
==================

The style guides for GBIF developments in PHP, Java, HTML, etc.

###Principles for HTML Markup and CSS###

- These guidelines are encouraged as the default best practice.
- Developers can go outside these guidelines from time to time, but any significant deviation should be raised within the team, and the guidelines reviewed.
- All styles introduced should follow the naming convention for CSS rules below.
- All styling selectors will be class based only(!).

####Use of `<article>`, `<section>`, `<aside>` and `<div>`####

- We use `article` to define an independent entity of content. For example, a news item, a species page, a featured-data-use case or a consultation request.
- We use `section` in two scenarios:
    - Immediately under `<body>`, a `<section>` is used to define major functional blocks of the page, e.g., banner, navigation, or footer credits. For the functional section that contains the key content of the page, we use `<main>` instead.
    - Inside `<article>`, a `<section>` is used to define content blocks of an article. For example, in a species detail page, which should be an `<article>`, `<section>` is used to define classification, description or geography.
- Each article and each section within an article should have an “id” unique to the page and an inline page anchor to allow linking to the article / section.
- On a search results page (e.g. list of news items), the container for the result is `<main>`,  and `<article>` is used for each result;
- `<aside>` is used only when the content is considered supplementary, e.g. external links. The wrapping element of `<aside>` determines at which level the content is supplementary, i.e., if `<aside>` is nested within `<article>`, it is supplementary to the article. Or if it is placed outside `<article>`, it is supplementary to the page.
- For contents that have no suitable semantic element or in doubt, use `<div>` or ask.

####Naming convention for CSS rules####

####References####
1. [The article element](http://html5doctor.com/the-article-element/).
1. [W3C definition of article](http://www.w3.org/TR/html5/sections.html#the-article-element).
1. [W3C definition of section](http://www.w3.org/TR/html5/sections.html#the-section-element).
1. [You can still use div](http://html5doctor.com/you-can-still-use-div/).
1. [W3C definition of div](http://www.w3.org/TR/html5/grouping-content.html#the-div-element).
1. [The main element](http://html5doctor.com/the-main-element/).
1. [Aside revised](http://html5doctor.com/aside-revisited/).
1. [W3C definition of aside](http://www.w3.org/TR/html5/sections.html#the-aside-element).
1. [Bootstrap grid introduction](http://getbootstrap.com/css/#grid-intro).



