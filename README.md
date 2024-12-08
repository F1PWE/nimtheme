# nim

A minimal, privacy-focused Hugo theme with subtle neon effects.

## Features
- Privacy-first approach
- No JavaScript
- Dark theme with neon accents
- Monospace typography
- Responsive design
- Clean, minimal layout

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
1. Download this theme
2. Put it in the `themes/nim` directory of your site
3. Add `theme = "nim"` to your `hugo.toml`

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

## Content Structure
```
content/
├── _index.md          # Home page
├── posts/             # Blog posts
├── contact/           # Contact page
└── links/             # Links page
```

## License
MIT License
