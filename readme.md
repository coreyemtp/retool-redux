# Retool-Redux

> [!IMPORTANT]
> This repository is meant as a continuation of unexpectedpanda's amazing Retool application.
> The original Retool is no longer maintained. [Read the thread](https://github.com/unexpectedpanda/retool/issues/337) for more information.

> [!TIP]
> **This is the source repository for Retool-Redux. For installation instructions and documentation, see the original Retool [website](https://unexpectedpanda.github.io/retool/).**

Retool-Redux is a filter utility for [Redump](http://www.redump.org/) and [No-Intro](https://datomatic.no-intro.org/index.php?page=download)
DAT files. By customizing the DAT files before you load them into a ROM manager, you can more
effectively trim, consolidate, and deduplicate your ROM sets. A fully customizable 1G1R set can also be created.

![A screenshot of the main Retool-Redux screen](https://unexpectedpanda.github.io/retool/images/main-app.png)

Retool-Redux offers the following features:

* Superior One Game, One ROM (1G1R) functionality compared to other tools.

* Priority-based region and language filtering.

* Exclusions of unwanted titles like demos, applications, and more.

* Custom regular expression, partial string, and complete string filters for including or excluding titles.
*   Clones may also be included when filtering titles.

* Optional regional filenames for titles, such as <code>シャイニング●フォースⅡ 『古の封印』</code>
  instead of <code>Shining Force II - Inishie no Fuuin</code>.

* CLI and GUI versions.

You add your DAT files to Retool-Redux, and it creates new DAT files with all your preferences,
leaving the originals intact (if desired). You can then load the new DAT files in a ROM manager like
[RomVault](https://www.romvault.com/), [CLRMamePro](https://mamedev.emulab.it/clrmamepro/),
or [IGIR](https://www.igir.io) to do your file management &mdash; you just don't need to
use their less capable 1G1R modes, as Retool-Redux has already done the work for you.

Retool-Redux is supported on Windows 10+, Ubuntu 20+, and macOS 10+. Non-compiled versions
require Python 3.10 or higher.

The original author unexpectedpanda and any contributors to the Retool application should in no way be inferred as endorsing this project. All changes to this fork will continue under a BSD 3 license.

## Contribute to Retool-Redux

If you've found something Retool-Redux has missed, like a clone or a local name for a title, you
can contribute to Retool Redux's clone lists at the [dedicated repository](https://github.com/coreyemtp/retool-redux-clonelists).
