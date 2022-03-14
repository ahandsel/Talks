# Welcome to My Slides

  * Powered by [Sli.dev](https://sli.dev) + Github Actions + Github Pages
  * Thanks to [fguisso](https://github.com/fguisso/talks) for building the repo setup

## Outline <!-- omit in toc -->
<!-- markdownlint-disable MD007 -->
* [Running for development](#running-for-development)
* [Deploy in Github Pages](#deploy-in-github-pages)
* [Resources on Creating Slides with Slidev](#resources-on-creating-slides-with-slidev)
* [Past talks](#past-talks)
<!-- markdownlint-enable MD007 -->

## Running for development

```shell
npm install
npm run dev -- slides/my-slide.md
```

Visit: <http://localhost:3030>

## Deploy in Github Pages

Deploys are dispatched by commit messages:

```bash
git add <slide-name>.md

git commit -m "deploy: <slide-name>"

git push
```

For the first deployment:
  1. GitHub Repo > Settings > GitHub Pages
  2. Set **Source** to `gh-pages` branch

## Resources on Creating Slides with Slidev

  * [Slidev documentations](https://sli.dev/)
  * [fguisso/talks Repo](https://github.com/fguisso/talks)
  * [antfu/talks Repo](https://github.com/antfu/talks)

## Past talks

| Title | Slides Link |
| ----- | ----------- |
| cat | <https://ahandsel.github.io/Talks/cat/> |
