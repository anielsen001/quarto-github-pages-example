# Quarto GitHub Pages Example

This is an example repo to publish a quarto document to the web. 

- GitHub repo: <https://github.com/anielsen001/quarto-github-pages-example>
- GitHib.io pages: <https://anielsen001.github.io/quarto-github-pages-example>

## Set up

Create quarto project
```bash
quarto create-project
git add _quarto.yml quarto-github-pages-example.qmd README.md .gitignore
```

Create empty `.nojekyll` file
```bash
touch .nojekyll
git add .nojekyll
```

Render the project
```bash
quarto render
```

Add the `docs` directory to git
```bash
git add docs
git commit -m"files"
```

Push to github
```bas
git push
```

## References

- <https://quarto.org/docs/publishing/github-pages.html>