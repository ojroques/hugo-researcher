# Researcher

A simple monospaced resume theme for Hugo. It was ported from Jekyll theme
[ankitsultana/researcher](https://github.com/ankitsultana/researcher).

## Screenshot
![thumbnail](https://github.com/ojroques/hugo-researcher/blob/master/images/tn.png)

## Installation
This theme uses Sass to generate CSS files so make sure you have the
*extended* Hugo version installed.

Add the theme to your site's `themes` directory:
```bash
git submodule add https://github.com/ojroques/hugo-researcher.git themes/researcher
```

Update the theme option in `config.toml`:
```toml
theme = "researcher"
```

## Configuration
A self-explanatory configuration file is present in
[exampleSite/config.toml](https://github.com/ojroques/hugo-researcher/blob/master/exampleSite/config.toml),
along the files of a demo website.

You can enable [KaTeX](https://katex.org/) (math typesetting) by including
`math: true` in your content files. Or you can enable it globally by setting
`math` to `true` in your project config.

## License
[GPL-3.0 License](https://github.com/ojroques/hugo-researcher/blob/master/LICENSE)
