# EVE Online Overview Generator

Based on [razor-x's work](https://github.com/razor-x/eve-overview).

## Installation

To install the pre-built overview, follow these steps:

1. Download the [overview](https://raw.githubusercontent.com/Nucanot/eve-overview/master/Overview/Nucanot-compact.yaml) ("Save As" locally).

2. Copy the `Nucanot-compact.yml` file to your `c:\users\USER\Documents\EVE\Overview` folder.

3. In EVE, open "Overview Settings", under "Misc" tab, first "Reset All Settings", then select "Import", select "Nucanot-compact" on the left, check "Check All" and press "Import".


# Building

## Requirements

Building the overview requires Ruby version 2 or later and [Bundler](http://bundler.io/).

## (First Time Only) Install Dependencies

```bash
% bundle
```

## Build the Overview

```bash
% bundle exec rake
```

The overview will be generated at `Overview/Nucanot-compact.yaml`
A ZIP file with the overview and accompanying documentation will be generated at `eve-overview-vX.Y.Z.zip` where `X.Y.Z` is the version, e.g. `1.2.3`.