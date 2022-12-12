# Welcome to My Talks

* Powered by [Sli.dev](https://sli.dev) + Github Actions + Github Pages
* Thanks to [fguisso](https://github.com/fguisso/talks) for building the repo setup
* Theme used is my iteration on [lightvue/slidev-theme-light-icons](https://github.com/lightvue/slidev-theme-light-icons)

## Outline <!-- omit in toc -->
<!-- markdownlint-disable MD007 -->
* [Running for development](#running-for-development)
* [Deploy in GitHub Pages](#deploy-in-github-pages)
  * [First Time](#first-time)
  * [Format Slide Deck](#format-slide-deck)
  * [Upload Slidev via GitHub Actions](#upload-slidev-via-github-actions)
* [Commands](#commands)
* [Resources on Creating Slides with Slidev](#resources-on-creating-slides-with-slidev)
* [Additional Notes](#additional-notes)
* [Past Talks](#past-talks)
<!-- markdownlint-enable MD007 -->

## Running for development

```shell
npm install
npm run dev Slides_my_slides.md
```

Visit: <http://localhost:3030>

## Deploy in GitHub Pages

### First Time

For the first deployment:

  1. GitHub Repo > Settings > GitHub Pages
  2. Set **Source** to `gh-pages` branch

### Format Slide Deck

```shell
npm run format Slides_my_slides.md

Example:
npm run format Slides_Book_ConnectingParagraphs.md
```

### Upload Slidev via GitHub Actions
Deploys are dispatched by commit messages:

```bash
git add SLIDES_NAME.md

git commit -m "Upload: SLIDES_NAME"

git push
```


## Commands

| Commands                        | Purpose                  |
| ------------------------------- | ------------------------ |
| `npm run format SLIDES_NAME.md` | Format the markdown file |
| `npm run build SLIDES_NAME.md`  | Build for production SPA |
| `npm run dev SLIDES_NAME.md`    | Start dev server         |
| `npm run export SLIDES_NAME.md` | Export slides to pdf     |

## Resources on Creating Slides with Slidev

* [Slidev documentations](https://sli.dev/)
* [fguisso/talks Repo](https://github.com/fguisso/talks)
* [antfu/talks Repo](https://github.com/antfu/talks)
* [ahandsel/debugging_log/SliDev_LightVue](https://github.com/ahandsel/debugging_log/tree/master/SliDev_LightVue)
* [npx slidev --help](https://github.com/ahandsel/debugging_log/blob/master/SliDev_LightVue/SliDev_Basic/SliDev_Help.md#npx-slidev---help)

## Additional Notes

Image Sizes

* Slide backgrounds: 1600 px by 900 px
* Vertical thin slots: 400 px by 900 px

## Past Talks

| Title                                                                   | Slides Link                                                          | Status    |
| ----------------------------------------------------------------------- | -------------------------------------------------------------------- | --------- |
| [Slides_lewagon_cybozu](Slides_lewagon_cybozu.md)                       | <https://ahandsel.github.io/Talks/Slides_lewagon_cybozu/>            | Done ✅    |
| [Slides_Kintone_Intro_Kids](Slides_Kintone_Intro_Kids.md)               | <https://ahandsel.github.io/Talks/Slides_Kintone_Intro_Kids/>        | Pending ✏️ |
| [Slides_Book_ConnectingParagraphs](Slides_Book_ConnectingParagraphs.md) | <https://ahandsel.github.io/Talks/Slides_Book_ConnectingParagraphs/> | Done ✅    |
| [Slides_KDP_Hiring_Jun_2022](Slides_KDP_Hiring_Jun_2022.md)             | <https://ahandsel.github.io/Talks/Slides_KDP_Hiring_Jun_2022/>       | Done ✅    |
