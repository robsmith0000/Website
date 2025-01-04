# Personal Blog using Hugo

A personal blog built with Hugo using the MemE theme and additional functionality for PDF embedding.

## Features

- Clean, modern design using the [MemE theme](https://github.com/reuixiy/hugo-theme-meme)
- PDF embedding support via [hugo-embed-pdf-shortcode](https://github.com/anvithks/hugo-embed-pdf-shortcode)
- Emacs org mode and markdown support
- Responsive layout
- Dark mode support
- Code syntax highlighting
- Math equation support (MathJax/KaTeX)

## Prerequisites

- Hugo Extended version (required for SCSS processing)
- Git (for theme management)

## Installation

1. Clone this repository:
git clone https://github.com/robsmith0000/Website


2. Enter the repository: cd Website

2. Initialize and update the theme submodules:
git submodule update --init --recursive


## Local Development

To start the development server:

hugo server -D

This will serve the site at http://localhost:1313.

To add a new markdown post:

hugo new posts/my-new-post.md

To add a new org post:

hugo new posts/my-new-post.org

## License

This project is licensed under the MIT License - see the LICENSE file for details.

### Theme Licenses
- MemE Theme: [MIT License](https://github.com/reuixiy/hugo-theme-meme/blob/master/LICENSE)
- Hugo Embed PDF Shortcode: [MIT License](https://github.com/anvithks/hugo-embed-pdf-shortcode/blob/master/LICENSE)

## Acknowledgments

- [MemE Theme](https://github.com/reuixiy/hugo-theme-meme) by reuixiy
- [Hugo Embed PDF Shortcode](https://github.com/anvithks/hugo-embed-pdf-shortcode) by Anvith KS