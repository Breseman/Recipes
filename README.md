# Recipes

**Access the recipes:** This book can be accessed as a website [here](https://breseman.gitbooks.io/recipes/content/) or downloaded as an [epub](https://www.gitbook.com/download/epub/book/breseman/recipes), [mobi](https://www.gitbook.com/download/mobi/book/breseman/recipes) or [pdf](https://www.gitbook.com/download/pdf/book/breseman/recipes).

---

# Editing the recipe book

## Editing online
If you are a member of the "Breseman" Github organization, you can edit the book [here](https://www.gitbook.com/book/breseman/recipes/edit).

## Running the book locally

Get this book locally by running `git clone https://github.com/Breseman/Recipes.git` in your command line. This downloads the whole folder to your computer.

Install [Node](https://nodejs.org/en/), then run `npm install gitbook` in your command line.

From inside the folder where this file is (in your command line– `cd recipes`), run `gitbook serve`. It will say "Serving book on http://localhost:4000" or similar.

[Go to that URL](http://localhost:4000).

## Adding a recipe

Follow the format of an existing recipe, making a new markdown (`.md`) file.

With Node installed, run `npm install gitbook-summary` to install the summary generator.

Run `book sm` to regenerate the summary file which defines the book's structure.
