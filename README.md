# recipe-md

A simple, plaintext recipe database. I was looking for a simple way to digitize and standardize my recipes from different sources (e.g. print cookbooks, handwritten family recipes, other online sources). 

![Azure Static Web Apps CI/CD](https://github.com/noahrmal/recipe-md/workflows/Azure%20Static%20Web%20Apps%20CI/CD/badge.svg)

**Demo with recipes from [clarklab](https://github.com/clarklab/chowdown)**: https://recipe-md.faltis.me/

**Demo with my recipes (german):** https://rezepte.faltis.me  

In my research I came across the project [chowdown](https://github.com/clarklab/chowdown) by [clarklab](https://github.com/clarklab). For my purpose I lacked an optimized printing view because I prefer to use printed recipes in a uniform appearance while cooking. My knowledge regarding jekyll was rather limited and the project structure of chowdown was complex so I decided to rewrite it from scratch in a simpler way aligned with my inidividual requirements. 

The recipes from chowdown are compatible and I used them while developing this project. In addition they are included for demo purposes. This project includes only a small subset of features compared to chowdown and is work in progress. I will add more features if I have the time and need.


# Getting Started

This is a Jekyll build. Make sure you have Jekyll [installed](https://jekyllrb.com/). To install, run this command in the terminal (or iTerm, etc):

```gem install bundler jekyll```

or to check if you've got it installed already:

```jekyll -v```

Clone or download this repo. Navigate to the folder in terminal (or iTerm, etc), and then run:

```jekyll serve```

With default settings, you should be able to view the site locally at `http://127.0.0.1:4000/`


# Writing a Recipe

The recipes are stored in the collection "Recipes" (the folder /_recipes).

They are written in Markdown and contain a few special sections:

- The frontmatter, which contains:
 - Title, Image, and Layout (which is "recipe")
 - Ingredients (a list of things in the dish)
 - Directions (a list of steps for the dish)
- Body content (for intros, stories, written detail)

If you need help with Markdown, here's a [handy cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).


# Planned features

- [x] PWA: manifest, assets, service worker
- [ ] support recipe schema
- [ ] add categories
- [ ] add tags
- [ ] search
- [ ] dynamic scaling
- [ ] nutritional information (calories, carbs, protein, fat)