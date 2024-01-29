---
layout: single
title: "Search Engine"
---

I developed a search engine that can efficiently search through hundreds of pages. It uses a [parse tree](https://en.wikipedia.org/wiki/Parse_tree) to handle complex queries, such as
* (cats & dogs): Finds all pages with both "cats" and "dogs."
* (savanna \| (grass & giraffes)): Finds all pages with either "savanna" or both "grass" and "giraffes."

It can also handle phrase queries, like
* "To be or not to be": Finds all pages with the exact phrase "To be or not to be."

My program indexes webpages ahead of time, allowing it search through 600 pages in a few milliseconds. The indexing system uses a hashmap to link keywords to the pages they appear on, reducing the search time.

Here's a demo of the search engine. It's searching through an old campaign website stored on my hard drive.

{% include video id="IISVZl3iZos" provider="youtube" %}
