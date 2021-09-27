# Personal VimWiki

Personal wiki as a knowledge base. The wiki language is either in English or in Chinese.

The web version is generated by pandoc and published to [GitHub Pages](https://crispgm.github.io/wiki-base/).

## Dev

### Bootstrap

Clone, and then set vimwiki path to it.

### Publish

```shell
make init
make all
make clean
```

### Templates

[Crisp Wiki Template](/_build/template.html)

### Filters

- [breadcrumb-menu](/_build/filters/breadcrumb-menu.lua): generate breadcrumb menu
- [links-to-html](/_build/filters/links-to-html.lua): convert inner links from `.md` to `.html`
- [promote-headers](/_build/filters/promote-headers.lua): promote header as title

## License

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)