+++
title = 'Internationalization'
date = '2025-03-24T23:00:00-03:00'
+++

Rusty Typewriter supports internationalization (i18n) files for localizing its sentences. By default it falls back to english, but you may use the values from an existing translations file or add your own translations in the `i18n/<lang>.yaml` dir of your site.

```yaml
# Root
theme_light: Light Theme
theme_dark: Dark Theme

# Footer
scroll_top: Scroll to Top
footer: Made with ❤️ and powered by {{ .ThemeAnchor }} theme for {{ .HugoAnchor }}

# Home
featured_posts: Featured Posts
recent_posts: Recent Posts

# SidePane for home
search: Search...
see_all: See all...

# Page
breadcrumb_home: Home

# SidePane for single pages
details_words: words
details_read_time: minutes read
side_table_of_contents: Table Of Contents
side_attachments: Attachments
side_related: Related
```

> **Note:** Didn't find a value you're looking for? Check the [repository](https://github.com/math-queiroz/rusty-typewriter) for the given file (which may be updated with it), or create a new feature request!
