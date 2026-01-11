# jim-works.github.io
Wisphaven's Website

Wisphaven is a small video game company. It's creator is named Jim, and the website should feel very personal and indie.
It's hosted as a static site on GitHub pages, with cname `wisphaven.com`. Do not use react or any web frameworks. This should be done in plain html/css. Do not use javascript unless absolutely necessary.
We also want the webstie to be entirely self-contained. Do not depend on any packages or external CDNs. Respect our user's privacy and bandwidth as much as possible.

The structure of the website will be:
- /index.html - home page. 
  - Header: Contains large text "Wisphaven" that gets smaller as you scroll down. Becomes a sticky header with links to other pages. This sticky header will be present on all pages.
  - Body: Should contain sections, separated by horizontal lines, for each item we want to shoutout. Create one for the blog, and one temporary one. Each section should have a title, some body text, and an image on the left.
- /about.html - about page. Contains sticky header, title, and some body text that I will fill out later.
- /blog.html - Contains sticky header, title text "Blog", and a list of all block posts. These should be individual sections with date, title, and summary.
  - /blog/<post>.html - Contains sticky header, post title, and post content. Post content will be html written by me.

To maintain consistency, please use `../wisphaven-blog-generator` to write a script to generate blank blog posts.

Styling:
- Generally, I want the site to feel like a less-professional newspaper. We want to feel welcoming and genuine, not corporate.
  - use a slightly yellowed offwhite background color for the main page. Should look like aged paper
  - use Times New Roman for the font
  - use horizontal and veritcal lines to separate sections, similar to newspapers
  - it should still have some personality
- The blog should feel more personal. I have a background piece of art in `images/background.png` that I'd like to use for the blog
  - the background image should not scroll with the page. Think of it like the surface of a table, and the user scrolls blog posts that are on pieces of paper over it.
