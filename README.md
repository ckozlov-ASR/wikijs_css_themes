# Wiki.js Custom Theme Template

A custom CSS theme for Wiki.js focused on improving the default visual experience without modifying core application files.

## Why this project exists

Wiki.js is a strong platform. It is fast, flexible, and easy to deploy. The default theme, however, can feel inconsistent in places, especially when it comes to color usage, navigation states, mobile behavior, and some Vuetify-driven UI elements.

This project is an attempt to improve that experience through a single CSS override file.

The goal is not to redesign Wiki.js from scratch. The goal is to make it feel cleaner, more coherent, and more usable while staying lightweight and easy to maintain.

## Current focus

This theme currently works on improving:

- header and sidebar styling
- navigation readability
- removal of default color leaks from Vuetify utility classes
- dropdown menu readability
- responsive/mobile search bar styling
- page heading presentation
- optional layout cleanup for a more focused interface

## Project status

**Work in progress.**

This is an active CSS theming project. New selectors and UI edge cases are still being discovered and refined as they appear in real use.

Because Wiki.js relies on Vue and Vuetify components, some styling requires targeted overrides for component states, utility classes, and responsive layouts. That means this project will continue to evolve.

## Philosophy

This project tries to stay true to a few principles:

- use CSS overrides only
- avoid editing Wiki.js core files
- keep deployment simple
- keep the theme understandable and maintainable
- support iterative refinement instead of one large rewrite

## Installation

Copy the contents of the theme CSS file into the Wiki.js CSS override area:

```text
Administration → Theme → CSS Override
```

Then save and refresh the browser.

## What this theme addresses

Some of the main issues this theme works around include:

- default blue or purple utility colors appearing in unexpected places
- inconsistent text contrast in navigation elements
- mobile search bar color mismatches
- menu text visibility problems
- default layout elements that add clutter in some deployments

## Compatibility notes

Wiki.js uses Vuetify under the hood, which means some visual behavior is driven by framework classes such as:

```css
.blue
.deep-purple
.theme--dark
.v-list-item
.v-menu__content
```

A number of overrides in this project are intentionally specific. In some cases, rules may look slightly redundant, but they exist because different parts of the UI are rendered through different component layers.

## Roadmap

Planned and possible future improvements include:

- broader heading hierarchy styling
- improved typography and spacing
- additional color themes
- more consistent button treatment
- refined mobile behavior
- optional variants for different use cases

## Contributing

Suggestions, cleanup ideas, and UI refinement ideas are welcome.

This project is still being shaped, so practical feedback is especially useful:

- places where default Wiki.js colors still leak through
- mobile/responsive issues
- selectors that can be simplified without breaking behavior
- cleaner theme variants

## Acknowledgments

Thanks to the Wiki.js community for shared ideas and inspiration, especially discussions like this one:

https://github.com/requarks/wiki/discussions/6584

## Final note

Wiki.js deserves a better default visual experience than it currently gets out of the box.

This project is a small attempt to help with that.