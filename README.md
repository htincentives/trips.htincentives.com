![Hodge Travel Incentives Logo](./_doc/img/htincentives-logo.png)

[![Broken Link Check](https://github.com/htincentives/trips.htincentives.com/actions/workflows/broken-link-checker.yaml/badge.svg)](https://github.com/htincentives/trips.htincentives.com/actions/workflows/broken-link-checker.yaml)

# trips.htincentives.com

Source of code and deployment configuration for the [https://trips.htincentives.com](https://trips.htincentives.com) website.

## Contributing

* [Uploading Files Using the Github UI](./_doc/UPLOADING_FILES.md)
* [Downloading Files Using the Github UI](./_doc/DOWNLOADING_FILES_FILES.md)

## Deployment & Hosting

The entire repository uses Github Pages to host the website.  The configuration for the trips.htincentive.com can be found in the [Settings page](https://github.com/htincentives/trips.htincentives.com/settings/pages).

### When is the site built?

Whenever a new commit is made, the site is rebuilt. This can take between

### What files show up?

Any file uploaded to the respository will show up to uses at `https://trips.htincentives.com/<filename>`. Exceptions include:

* Files that start with an underscore, like `_config.yml`
* Files inside the [`_config.yml`](./_config.yml) underneath the `exclude` key.

### What else does Github Pages offer?

For more info, see: [https://pages.github.com/](https://pages.github.com/)
