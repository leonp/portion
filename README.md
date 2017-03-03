# Portion

A very simple Jekyll theme for publishing short updates or images.

Demo at [This day’s portion](https://www.thisdaysportion.xyz).

## Pagination

Includes `Gemfile` and `_config.yml` entries to enable pagination. Does mean you won't be able to use this theme on Github Pages. Try [Netlify](https://netlify.com) instead and you'll get free SSL too.

Set the number of posts per page with the `paginate` variable in `_config.yml`.

## Styles

Hot links to [Tachyons](https://tachyons.io). No SASS required (unless you add it manually).

## Config

Set the following in `_config.yml`:

- `lang` e.g `en-gb` for use in `html` and `link` elements in header
- `title`
- `tagline` (displayed under the site title)
- `baseurl`

## Posts

Use the `post` layout.

Add `image` amd `alt` YAML to specify an image that sits in the `/images/` folder. So if you add `image: happy.jpg` to a post the theme will output `/images/happy.jpg`. When you specify an image the theme won't display any other content.
