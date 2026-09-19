# Pretty Calendar

Your calendar, but pretty. A week (or two) at a glance with today highlighted, plus your next appointments. Works on black & white, grayscale and color screens.

<a href="https://trmnl.com/recipes/210616"><img width="150" alt="Works with TRMNL" src="https://trmnl.com/images/brand/badges/light/works-with-trmnl/trmnl-badge-works-with-light.svg" /></a>

## Requirements
The [CalDAV](https://trmnl.com/plugin_settings/new?keyname=caldav) plugin must be active (it can be hidden from your playlist). Pretty Calendar reads its data.

## Settings
- **Calendar source:** which CalDAV plugin to use
- **Language:** auto or one of 12 languages (EN, NL, DE, FR, ES, IT, PT, SV, DA, NO, FI, PL)
- **Accent color:** color for today on color screens
- **Show calendar items:** next 3 days or only today
- **Weeks in view:** 1 or 2
- **Event descriptions** and **font** (TRMNL or Google Sans Flex)

### Develop locally

Templates and settings live in [`src/`](src/), ready for [trmnlp](https://github.com/usetrmnl/trmnlp):

```sh
gem install trmnl_preview
trmnlp serve
```

Questions or ideas? trmnl@achtnegen.nl or @Bastronautica on Discord.
