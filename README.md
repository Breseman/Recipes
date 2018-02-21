# Recipes

## Running the book locally

Get this book locally by running `git clone https://github.com/Breseman/Recipes.git` in your command line. This downloads the whole folder to your computer.

Install [Node](https://nodejs.org/en/), then run `npm install gitbook` in your command line.

From inside the folder where this file is (in your command line– `cd recipes`), run `gitbook serve`. It will say "Serving book on http://localhost:4000" or similar.

[Go to that URL](http://localhost:4000).

## Adding a recipe

Follow the format of an existing recipe, making a new markdown (`.md`) file.

With Node installed, run `npm install gitbook-summary` to install the summary generator.

Run `book sm` to regenerate the summary file which defines the book's structure.
