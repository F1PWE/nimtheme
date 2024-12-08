# nim

A minimal, privacy-focused Hugo theme with subtle neon effects.

## Features
- Privacy-first approach
- No JavaScript
- Dark theme with neon accents
- Monospace typography
- Responsive design
- Clean, minimal layout
- Terminal-style elements
- Subtle glitch effects

## Installation

### Git Submodule (recommended)
```bash
cd your-hugo-site
git submodule add https://github.com/F1PWE/nimtheme.git themes/nim
```

Then, add to your `hugo.toml`:
```toml
theme = "nim"
```

### Manual Installation
1. Download this theme from https://github.com/F1PWE/nimtheme.git
2. Put it in the `themes/nim` directory of your site
3. Add `theme = "nim"` to your `hugo.toml`

## Required Structure
Create these directories and files in your site:
```
content/
├── _index.md          # Home page
├── posts/             # Blog posts
├── contact/           # Contact info
│   └── _index.md     # Contact page
└── links/            # External links
    └── _index.md     # Links page
```

## Configuration
Example configuration in your site's `hugo.toml`:

```toml
baseURL = 'https://example.org/'
languageCode = 'en-US'
title = 'Your Site Title'
theme = 'nim'

# Main menu
[[menus.main]]
name = 'home'
pageRef = '/'
weight = 10

[[menus.main]]
name = 'posts'
pageRef = '/posts'
weight = 20

[[menus.main]]
name = 'contact'
pageRef = '/contact'
weight = 30

[[menus.main]]
name = 'links'
pageRef = '/links'
weight = 40

[[menus.main]]
name = 'tags'
pageRef = '/tags'
weight = 50
```

## Example Content
Check the `exampleSite` directory in this theme for reference content and structure:
- Home page introduction
- Contact page setup
- Links page format
- Example posts

## Customization
You can override any part of the theme by creating the same file structure in your site's directory. For example:
- Override CSS: Create `assets/css/main.css` in your site
- Override layouts: Create matching files in your site's `layouts` directory
- Override partials: Create matching files in your site's `layouts/partials` directory

## License
GNU General Public License v2.0
