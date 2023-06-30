# The Plano Campus AV Guide
A guide to AV at Village Bible Church - Plano Campus

# Getting Started

## SiteJS / Hugo
This repository is meant to be run as a [Hugo](https://gohugo.io/) site via [SiteJS](https://sitejs.org/) for ease of use and simplicity.

**SiteJS must already be installed prior to using this!**

To start running the AV Guide, simply clone this repo into a folder `/.hugo`.
Then create a new Hugo site with SiteJS:

```sh
site hugo new --force
```

## Techdoc Theme

Before running your site, you need a **theme**. We use the `techdoc` theme, which needs to be cloned separately.

```sh
cd .hugo/themes
git clone https://github.com/thingsym/hugo-theme-techdoc.git
```

## Running the Site
Now just call `site` in the main directory. You're up and running!

# Editing Site Contents
The entire site is written in **Markdown**. Folders within the `.hugo` directory will be converted to a page structure automatically.
