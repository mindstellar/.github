<a href="https://mindstellar.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mindstellar/.github/main/profile/banner-dark.svg">
    <img src="https://raw.githubusercontent.com/mindstellar/.github/main/profile/banner-light.svg" width="100%" alt="Mindstellar: open-source classifieds you run on your own hosting.">
  </picture>
</a>

<p align="center">
  <a href="https://mindstellar.com"><b>Website</b></a> &nbsp;·&nbsp;
  <a href="https://mindstellar.com/docs/"><b>Docs</b></a> &nbsp;·&nbsp;
  <a href="https://demo.mindstellar.com"><b>Live demo</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/mindstellar/shopclass/releases"><b>Download</b></a> &nbsp;·&nbsp;
  <a href="https://mindstellar.com/osclass/"><b>Coming from Osclass?</b></a>
</p>

## Our goal

Anyone should be able to run a classifieds marketplace they fully own: on ordinary hosting,
with no licence fees, no lock-in, and extensions that keep working after an upgrade.

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Self-hosted first</b><br>
      A zip you upload to shared hosting or a VPS. No build step, no required cloud service.
    </td>
    <td width="50%" valign="top">
      <b>Upgrades that don't break sites</b><br>
      The <code>osc_*</code> helpers, hooks and admin classes are treated as a public API.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>Open by default</b><br>
      Code under GPL-3.0. Location data under CC0. Plugin and theme catalogues are public repositories.
    </td>
    <td width="50%" valign="top">
      <b>Modern, not rewritten</b><br>
      PHP 8, jQuery-free core, a rebuilt admin. Your Osclass data and extensions come with you.
    </td>
  </tr>
</table>

## ShopClass

<p>
  <a href="https://github.com/mindstellar/shopclass/releases/latest"><img src="https://img.shields.io/github/v/release/mindstellar/shopclass?label=stable&color=0b7269&style=flat-square" alt="Stable release"></a>
  <a href="https://github.com/mindstellar/shopclass/releases"><img src="https://img.shields.io/github/v/release/mindstellar/shopclass?include_prereleases&label=beta&color=5f6b7a&style=flat-square" alt="Beta release"></a>
  <a href="https://github.com/mindstellar/shopclass/actions/workflows/test.yml"><img src="https://img.shields.io/github/actions/workflow/status/mindstellar/shopclass/test.yml?branch=develop&label=tests&style=flat-square" alt="Tests"></a>
  <img src="https://img.shields.io/badge/PHP-8.0%2B-777bb4?style=flat-square" alt="PHP 8.0+">
  <a href="https://github.com/mindstellar/shopclass/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-GPL--3.0-0f2742?style=flat-square" alt="GPL-3.0"></a>
  <a href="https://github.com/mindstellar/shopclass/stargazers"><img src="https://img.shields.io/github/stars/mindstellar/shopclass?color=0f2742&style=flat-square" alt="Stars"></a>
</p>

**[ShopClass](https://github.com/mindstellar/shopclass)** is a free, self-hosted classifieds CMS in PHP,
and the maintained successor to Osclass. Run a site for jobs, property, vehicles or anything else.

- Listings with photos, categories, custom fields and locations
- Search, filters and SEO-friendly URLs
- User accounts, moderation, spam and report handling
- Paid listings and packages
- A rebuilt, accessible admin panel
- A one-click updater, and plugins and themes you install from the admin

## The ecosystem

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mindstellar/.github/main/profile/ecosystem-dark.svg">
  <img src="https://raw.githubusercontent.com/mindstellar/.github/main/profile/ecosystem-light.svg" width="100%" alt="The ShopClass core with its themes, plugins, translations, location data and registries.">
</picture>

### Themes

| Repository | What it does | Version |
|---|---|---|
| [**theme-storefront**](https://github.com/mindstellar/theme-storefront) | The default theme. Vanilla JS, light and dark, three WCAG-AA palettes. | ![](https://img.shields.io/github/v/release/mindstellar/theme-storefront?label=&color=0b7269&style=flat-square) |
| [**theme-folio**](https://github.com/mindstellar/theme-folio) | A minimal theme on native HTML5. Logo, brand colour and footer settings. | ![](https://img.shields.io/github/v/release/mindstellar/theme-folio?label=&color=0b7269&style=flat-square) |

### Plugins

| Repository | What it does | Version |
|---|---|---|
| [**shopclass-plugin-cloudflare**](https://github.com/mindstellar/shopclass-plugin-cloudflare) | Purges the Cloudflare cache when content changes. Cache rules and analytics in the admin. | ![](https://img.shields.io/github/v/release/mindstellar/shopclass-plugin-cloudflare?label=&color=0b7269&style=flat-square) |
| [**shopclass-plugin-nginx-cache**](https://github.com/mindstellar/shopclass-plugin-nginx-cache) | Holds pages in the nginx cache, and purges them when a listing changes. | ![](https://img.shields.io/github/v/release/mindstellar/shopclass-plugin-nginx-cache?label=&color=0b7269&style=flat-square) |
| [**shopclass-plugin-digital-goods**](https://github.com/mindstellar/shopclass-plugin-digital-goods) | Attaches downloadable files to a listing, stored privately behind a gated link. | ![](https://img.shields.io/github/v/release/mindstellar/shopclass-plugin-digital-goods?label=&color=0b7269&style=flat-square) |

### Registries

| Repository | What it does |
|---|---|
| [**shopclass-plugins**](https://github.com/mindstellar/shopclass-plugins) | The plugin registry. Submit a plugin by pull request; it appears in every admin's catalogue. |
| [**shopclass-themes**](https://github.com/mindstellar/shopclass-themes) | The theme registry. Browse, install and update themes from the admin. |

### Translations and data

| Repository | What it does |
|---|---|
| [**shopclass-i18n**](https://github.com/mindstellar/shopclass-i18n) | Every language ShopClass ships in. A merged translation reaches sites without a new release. |
| [**location-data**](https://github.com/mindstellar/location-data) | Countries, regions and 1.6M+ places from Wikidata, published CC0, with the pipeline that builds it. |

## How it is built

- Code under GPL-3.0, in public repositories.
- Tests run on every push.
- Releases are built by CI from a tagged commit, each with a changelog.
- Security reports go through [private vulnerability reporting](https://github.com/mindstellar/shopclass/security/policy).
- Sites upgrade from Osclass 3.x and 5.x; see the [upgrade guide](https://mindstellar.com/osclass/).

## Get involved

- Try the [live demo](https://demo.mindstellar.com), or [install ShopClass](https://mindstellar.com/docs/) on your own hosting.
- Found a bug or want a feature? [Open an issue](https://github.com/mindstellar/shopclass/issues).
- Speak another language? [Help translate](https://github.com/mindstellar/shopclass-i18n).
- Built a plugin or theme? Add it to the [plugin](https://github.com/mindstellar/shopclass-plugins) or [theme](https://github.com/mindstellar/shopclass-themes) registry.
- Found a vulnerability? [Report it privately](https://github.com/mindstellar/shopclass/security/advisories/new).

---

<sub>Mindstellar is the open-source work of Navjot Tomer, with contributions from the people who run ShopClass.</sub>
