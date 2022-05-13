# Welcome to My Talks

* Powered by [Sli.dev](https://sli.dev) + Github Actions + Github Pages
* Thanks to [fguisso](https://github.com/fguisso/talks) for building the repo setup

## Outline <!-- omit in toc -->
<!-- markdownlint-disable MD007 -->
* [Running for development](#running-for-development)
* [Deploy in Github Pages](#deploy-in-github-pages)
* [Commands](#commands)
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

git commit -m "Upload: <slide-name>"

git push
```

For the first deployment:

  1. GitHub Repo > Settings > GitHub Pages
  2. Set **Source** to `gh-pages` branch

## Commands

| Commands                         | Purpose                  |
| -------------------------------- | ------------------------ |
| `npm run format <slide-name>.md` | Format the markdown file |
| `npm run build <slide-name>.md`  | Build for production SPA |
| `npm run dev <slide-name>.md`    | Start dev server         |
| `npm run export <slide-name>.md` | Export slides to pdf     |

## Resources on Creating Slides with Slidev

* [Slidev documentations](https://sli.dev/)
* [fguisso/talks Repo](https://github.com/fguisso/talks)
* [antfu/talks Repo](https://github.com/antfu/talks)
* [ahandsel/debugging_log/SliDev_LightVue](https://github.com/ahandsel/debugging_log/tree/master/SliDev_LightVue)
* [npx slidev --help](https://github.com/ahandsel/debugging_log/blob/master/SliDev_LightVue/SliDev_Basic/SliDev_Help.md#npx-slidev---help)

## Past talks

| Title                                             | Slides Link                                               |
| ------------------------------------------------- | --------------------------------------------------------- |
| [Slides_lewagon_cybozu](Slides_lewagon_cybozu.md) | <https://ahandsel.github.io/Talks/Slides_lewagon_cybozu/> |
