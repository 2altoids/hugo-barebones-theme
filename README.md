# hugo-barebones-theme
A skeletal theme for the Hugo static site generator, just so I don't have to figure out how to make one from scratch all over again.

## installation
```sh
hugo new site my-site
cd my-site
git clone https://github.com/2altoids/hugo-barebones-theme themes/hugo-barebones-theme
echo "theme = 'hugo-barebones-theme'" >> config.toml
```

## notes
- This theme has no CSS, RSS feeds, JavaScript, or tags.
- There is also no favicon or set robots behavior.
- There are no semantic tags in the template HTML.
- It is meant to be as simple as possible to illustrate the structure of a very basic theme.
- Front matter content can be added to a list page using a `_index.md` file in that page's directory.
