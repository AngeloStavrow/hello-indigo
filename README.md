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

The live site is always built against the latest version of Hugo, so please be sure to [upgrade] before continuing.

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

### New Indigo release

### New Hugo release

### Announcements

## Deploying

⚠️ Only members of the [**hello-indigo** project on Glitch](https://glitch.com/~hello-indigo) are able to deploy to the live site.






<!-- links -->

[demo site]: https://hello-indigo.glitch.me/
[indigo]: https://github.com/AngeloStavrow/indigo/
[hugo]: https://gohugo.io/
[Glitch]: https://glitch.com/
[theme issues]: https://github.com/AngeloStavrow/indigo/issues/
[here]: https://github.com/AngeloStavrow/hello-indigo/issues/
[ugprade]: https://gohugo.io/getting-started/installing/#upgrade-hugo