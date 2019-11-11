# Recettes and recipes

A handful of recipes tested by us, for you!

## Stack

Website generated and managed with [Hugo](https://github.com/gohugoio/hugo). It's a prerequisite to install it if you want to add a recipe.

Auto deploy to [recettes-recipes.github.io/blog](https://recettes-recipes.github.io/blog) is provided by Github Actions, credits to [peaceiris/actions-hugo](https://github.com/peaceiris/actions-hugo).

## Add a recipe

Generate a Markdown recipe file by typing the command:

```bash
hugo new --kind recipe-bundle recipes/name-of-your-new-recipe-here
```

Then, simply edit the recipe and its image (`content/recipes/name-of-your-new-recipe-here` folder).

## Run local server

Thanks to [Hugo](https://github.com/gohugoio/hugo) CLI, simply run this command:

```bash
hugo server -D
```

## Production build

Run this command:

```bash
hugo --minify
```
