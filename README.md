# Wiki.js Custom Theme Templates

A custom CSS theme project for Wiki.js focused on improving the default visual experience without modifying core application files.

## Why this project exists

Wiki.js is a strong platform. It is fast, flexible, and easy to deploy. The default theme, can feel inconsistent in places, especially when it comes to color usage, navigation states, mobile behavior, and some Vuetify-driven UI elements.

This project is an attempt to improve that experience through a single CSS override file.

The goal is not to redesign Wiki.js from scratch. The goal is to make it feel cleaner, more coherent, and more usable while staying lightweight and easy to maintain.

## Project status

**Work in progress.**

This is an active project.  New colors, selectors, and UI change are still being discovered and refined.

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

Thanks to the Wiki.js community for the shared ideas and inspiration, especially discussions like this one:

https://github.com/requarks/wiki/discussions/6584

## Final note

Wiki.js deserves a better default visual experience than it currently gets out of the box. This project is a small attempt to help with that.