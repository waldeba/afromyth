# Afromyth Hugo Theme

A modern Pinterest-style Hugo theme designed for showcasing African cultural artifacts and products.

## Features

- **Pinterest-style Masonry Grid**: Responsive 4-column grid layout that adapts to different screen sizes
- **E-commerce Ready**: Built-in shopping cart functionality with "Add to cart" buttons
- **Cultural Focus**: Optimized for displaying African cultural artifacts, art, and products
- **Load More Functionality**: Pagination system showing 60 items initially with load more capability
- **Clean Design**: Transparent backgrounds, no card styling for a modern, clean appearance
- **Mobile Responsive**: Optimized for all device sizes
- **Fast Performance**: Optimized images (800x800px) and efficient CSS Grid layout

## Demo Content

The theme includes 120+ sample African cultural artifacts including:
- Ethiopian Orthodox crosses
- Masks, statues, and carvings
- Traditional textiles and jewelry
- Historical manuscripts and books
- Ceremonial items and regalia

## Installation

1. Clone this repository into your Hugo site's `themes` directory:
```bash
git clone https://github.com/yourusername/afromyth.git themes/afromyth
```

2. Add the theme to your `config.toml`:
```toml
theme = "afromyth"
```

3. Copy the example content and configure your site.

## Configuration

The theme works with standard Hugo configuration. Key content types supported:
- `masks-statues-carvings`
- `ethiopian-orthodox-crosses` 
- `apparel-textiles-jewelry`
- `books-icons-manuscripts`
- `tokens-medals-pins`

## Customization

The theme includes customizable:
- Grid layout (4-column responsive)
- Color schemes
- Product categories
- Image dimensions (currently 800x800px)
- Load more pagination settings

## Layout Structure

```
layouts/
├── index.html          # Homepage with Pinterest-style grid
├── _default/
│   ├── baseof.html     # Base template
│   └── list.html       # List page template
├── products/
│   ├── single.html     # Individual product page
│   └── list.html       # Product listing page
└── partials/
    ├── header.html     # Site header
    └── footer.html     # Site footer
```

## License

This theme is open source and available under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
