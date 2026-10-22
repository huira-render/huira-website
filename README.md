# Huira Website Repository

This website uses the jekyll static site generator, with the `minimal-mistakes-jekyll` theme.

## Development

### Testing
To test the website locally before deploying on github pages, run:

```
bundle exec jekyll serve
```

## Content

- Links to the other huira.space sites (docs, quick start, validation, media) are set in
  `_config.yml`. The masthead's links are in `_data/navigation.yml`, which can't use those
  variables, so update both together.
- The images on the home page are listed in `_data/gallery.yml`.
- Images and other media live in the media bucket ([media.huira.space](https://media.huira.space)),
  not in this repository: the site's own images go under `site/` there. Only the logos are kept
  here, in `assets/huira-logos/`.
- Custom styles are at the end of `assets/css/main.scss`.
