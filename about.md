---
layout: page
title: About
dateModified: 2021-05-18 21:42:38 -0700
---
# Rubik: A minimal Jekyll theme template.

[![Netlify Status](https://api.netlify.com/api/v1/badges/121e1d01-ba6c-419d-b20e-fe26a6615620/deploy-status)](https://app.netlify.com/sites/discoform-rubik/deploys)

[VIEW THE DEMO](https://discoform-rubik.netlify.app)


- Simple to use
- Free to use
- Semantic Markup
- Minimal use of Javascript and CSS
- High lighthouse scores
- High Web Vitals scores

Issues and enhancements are welcome. [You can find the project board here](https://github.com/discoform/rubik-for-jekyll/projects/1).

_❗ NOTE: This theme is not recommended recommended for GitHub Pages hosting due to the use of [Jekyll Picture Tag](https://github.com/rbuchberger/jekyll_picture_tag).  (use the [__Starter__ plan from Netlify instead](https://www.netlify.com/pricing/))_



---


## Plugins

### [Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag)

A Jekyll plugin to add metadata tags for search engines and social networks to better index and display your site's content.

This plugin is set up to do the following:

- Adds Page title meta tag, with site title or description appended
- Adds Page description meta tags
- Adds the canonical URL meta tags
- JSON-LD Site and post metadata
- Open Graph title metadata
- Twitter Summary Card metadata

### [Jekyll Feed](https://github.com/jekyll/jekyll-feed)

A Jekyll plugin to generate an Atom (RSS-like) feed of your Jekyll posts. This is a pretty stock inclusion for any Jekyll build. It allows readers to add your site to their RSS feed reader.

### [Jekyll Sitemap](https://github.com/jekyll/jekyll-sitemap)
Jekyll plugin to silently generate a sitemaps.org compliant sitemap for your Jekyll site.

### [Jekyll Picture Tag](https://github.com/rbuchberger/jekyll_picture_tag)

The current configuration automatically builds resized `.webp` images for most of your image library. The settings can be found in `_data/picture.yml` if you're feeling adventurous...

_❗ NOTE: Jekyll Picture Tag can be a little fussy (at least, it has been for me). If you see build errors in Netlify you should ensure that your Build Image Selection is set to __Ubuntu Trusty 14.04__ or __Ubuntu Focal 20.04 (beta)__._

![netlify-build-image-selection](../netlify-build-image-selection.png)

---

## Data files

In the `_data` directory you'll find files to handle the following site components and features:

- `siteNavigation.yml` (header navigation, footer navigation, and aside navigation)
- `siteSocial.yml` (links added here will be added to a widget in the footer)
- `picture.yml` (settings for the Jekyll Picture Tag plugin)

---

## Contact Form

The Rubik theme has a simple HTML contact form with the [Netlify data attribution](https://docs.netlify.com/forms/setup/). This should work out of the box if you're using Netlify for hosting, otherwise you can replace this with your own solution.

---

## Search functionality

We've implemented the solution suggested by [WebJeda](https://blog.webjeda.com/instant-jekyll-search/). The solution works well and is lightweight, but not very feature-rich.

