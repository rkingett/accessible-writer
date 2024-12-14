# Accessible writer theme.

This is a theme designed to be accessible, and very minimalist. Not much will be added to this theme with regards to features, so feel free to fork this and add onto it. The goal is to have this theme be very accessible with less features. No tracking support, no comments support, no nothing!

Until I can get my own demo site to work, view the [Demo site](https://accessible-minimalism.netlify.app)

## Project aims

Some things from the original project will stay the same, such as,

- XHTML 1.0 Strict valid and HTML 5 friendly code
- minimal bloat in the generated markup
- focus on accessibilityy
- - semantic, minimal markup for screen readers
- minimal added CSS for partially sighted users
- easy to read source code
   - minimal config required to get started and use in Hugo
- RSS subscription support
- favors fully-blind users over partially or fully sighted users
- mobile-last development because there are other people better than me that can do this better.

## Who is this for?

This theme will be for bloggers and writers that want an accessible and easy to use theme, with large fonts, minimal CSS, and nothing else. If you want features like tracking and comments and similar,, this is not the theme for you.

You don't need Javascript for a blog. You just need an RSS feed, and big font size on a high contrast background.

## Getting started

After navigating to your site's root directory, run the below command.

```git submodule add https://github.com/rkingett/accessible-writer themes/accessible-writer```

Alternatively,

1. In your Hugo site's root, clone this repo to your `themes` dir:

```git clone --depth 1 [https://github.com/leonstafford/accessible-minimalism-hugo-theme](https://github.com/rkingett/accessible-writer) themes/accessible-minimalism```

*Using the https remote URI will make deployment of your website via some CI/CD,
 such as Netlify, easier.*

After doing the above,

Copy the `config.toml` file from the exampleSite directory inside this repository to your site root:

## Configuration

The main things you may want to adjust when using this theme are your content
 structure and main site menu. Copying the `content` directory from this theme's
 `exampleSite` directory will be a good place to start. You can compare this
 with the menu entries in the `config.toml` and it should make sense. Try making
 changes and see what happens. If it becomes a mess, reset both to initial 
 states.

## Development decisions

- skip redundancy such as anchor's `title` attributes
- Font is larger by default.
- - default browser colors are high contrast enough

## Roadmap.

There is none. I plan to edit the CSS and add things like RSS links for category pages and tag pages but nothing beyond that.

### License

[The Unlicense](https://unlicense.org) - do whatever you like with this code..
