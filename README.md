# hello-indigo

## Summary

The source repository for building the **hello-indigo** [demo site]. The **hello-indigo** site serves two purposes:

1. It demonstrates the latest stable version of the [Indigo] theme for [Hugo].
2. It acts as public site for news about the Indigo theme, including updates.

## Overview

### Site source

This repository contains all source files for building the **hello-indigo** site.

## Submodules

### The /public directory

`origin`: https://api.glitch.com/git/hello-indigo

The live site (currently hosted on [Glitch]). Running the `hugo` command builds the site in this directory; the changes are staged, committed, and pushed to Glitch. More on this in the **Deploying** section.

### The /themes/indigo directory

`origin`: https://github.com/AngeloStavrow/indigo/

The Indigo theme source. The live site is built from the latest release on the `master` branch; more on this in the **Deploying** section.

## Contributing

⚠️ If you've found a problem or have a suggestion **for the Indigo theme**, [please open an issue in the theme project][theme issues]. This project is for the Indigo demo site only.

If you've found a problem or have a suggestion for the demo site, then please open an issue [here] — be sure to check for duplicates first, though.

If you'd like to contribute a change, please keep reading.

### Pre-requisites

The live site is always built against:

- the latest stable release of Hugo; to upgrade Hugo, follow these [upgrade instructions].
- the latest stable release of Indigo; this repository maintains a submodule pointing to the latest release.

### Getting the source code

You'll need to clone the source code as well as a few git submodules to your local machine:

```bash
$ git clone https://github.com/AngeloStavrow/hello-indigo.git hello-indigo
$ git submodule init
$ git submodule update
```

Check that everything's working as expected by building the site and starting a local server:

```bash
$ cd hello-indigo
$ hugo server
```

You should then be able to visit http://localhost:1313 in your browser and see your own copy of the demo site.

## Site update process

There are two types of updates that are created; a _release_ update, and a _post_ update.

### Post updates

Post updates are what most think of as a blog post; an update to the site that adds a post related to the theme, like an explanation of a new feature, the announcement of a new process, and so on. These are longer-form updates which should include appropriate tags and categories.

### Release updates

Release updates are short updates that add information about a type of release:

- **Hugo release updates** are added when a new version of Hugo is released. The goal of these updates is simply to notify readers that the demo site has been tested, built, and deployed against the latest version of Hugo. They are categorized as `updates` and tagged `hugo`.
- **Indigo release updates** are added when a new version of Indigo is released. The goal of these updates is to let readers know what's changed in the new version, and to confirm that the demo site has been tested, built, and deployed against the latest version of Indigo. They are categorized as `updates` and tagged `indigo`.

## Deploying

⚠️ Only members of the [**hello-indigo** project on Glitch](https://glitch.com/~hello-indigo) are able to deploy to the live site.

<!-- links -->

[demo site]: https://hello-indigo.glitch.me/
[indigo]: https://github.com/AngeloStavrow/indigo/
[hugo]: https://gohugo.io/
[glitch]: https://glitch.com/
[theme issues]: https://github.com/AngeloStavrow/indigo/issues/
[here]: https://github.com/AngeloStavrow/hello-indigo/issues/
[upgrade instructions]: https://gohugo.io/getting-started/installing/#upgrade-hugo
