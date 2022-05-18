# TechWS Theme

The **TechWS Theme** is for [Grav CMS](http://github.com/getgrav/grav).  This README.md file should be modified to describe the features, installation, configuration, and general usage of this theme.

## Description

Theme for [Grav CMS](http://github.com/getgrav/grav), using [Bulma Framework](https://bulma.io/).

This theme is used on https://techws.net.

## Features

- Blog with pagination
- Children pages
- Taxonomy (categories,tags)
- Languages supported : fr / en

## Dependencies and Plugins support

[Twig Extensions](https://github.com/Perlkonig/grav-plugin-twig-extensions) is needed for date translations.

[Pagination](https://github.com/getgrav/grav-plugin-pagination) is highly recommended for paginate Blog page.

[JSComments](https://github.com/sommerregen/grav-plugin-jscomments) is optional, and configured to add a comments on blog articles.

## Styles

This theme use Sass to customize Bulma.

```
# go to sass directory
cd bulma-custom/sass

# compile to css and watch for updates
npm run start
```