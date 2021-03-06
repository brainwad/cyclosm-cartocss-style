CyclOSM
=======

CyclOSM is a [CartoCSS](https://carto.com/developers/styling/cartocss/) map style
designed with cycling in mind. It leverages
[OpenStreetMap](https://www.openstreetmap.org/) data to create a beautiful and
practical cycling map!

[![Build Status](https://api.travis-ci.org/cyclosm/cyclosm-cartocss-style.svg?branch=master)](https://travis-ci.org/cyclosm/cyclosm-cartocss-style)

[![CyclOSM](https://www.cyclosm.org/images/social_media.png)](https://www.cyclosm.org/)


## Demonstration

A demonstration of this style is available at [https://cyclosm.org](https://cyclosm.org).

The tile server url is
`https://{s}.tile-cyclosm.openstreetmap.fr/cyclosm/{z}/{x}/{y}.png`. Tiles can
be reused under the general OpenStreetMap [tile usage
policy](https://operations.osmfoundation.org/policies/tiles/).

The map is available by default in the following smartphone applications:
- [OSMAnd](https://osmand.net/)
- [OpenMultiMaps](https://framagit.org/tom79/openmaps)
- [All-In-One Offline Maps](https://www.offline-maps.net) and [AlpineQuest Rando GPS](https://alpinequest.net)

The tile server is provided by
[OpenStreetMap-France](https://www.openstreetmap.fr), many thanks to them for
the support!

## Philosophy

CyclOSM is a new cycle-oriented render. Contrary to
[OpenCycleMap](http://opencyclemap.org/), this render is free and open-source
software and aims at being more complete to take into account a wider
diversity of cycling habits.

In urban areas, it renders the main different types of cycle tracks and lanes,
on each side of the road, for helping you draw your bike to work route. It also
features essential POIs as well as bicycle parking spots or spots shared with
motorbikes, specific infrastructure (elevators / ramps), road speeds or
surfaces to avoid streets with pavings, bumpers and bike boxes, etc.

The same render also lets you visualize main bicycle touring routes as well as
essential POIs when touring (emergency services, shelters, tourism, shops).


## Features

Render:

* Cycleways track, lanes, cycle-bus lanes
* Motor oneway - two way for bicycle
* Cycle routes (local, regional, national, international)
* Parking for bicycle (or motorcycle parking open to bicycle)
* Steps with bicycle friendly ramp
* Bicycle shop and repair stations
* First aid amenities : shelter, hospital, pharmacy, police station, water, food store
* Travel amenities : camping, hotel, train station, museum, picnic table, peaks...
* Emphasis on low speed roads (<= 30km/h)
* Elevation curves and shading
* Smoothness of the roads
* Traffic calming
* …

A full list of rendered features is available in [the
legend](https://www.cyclosm.org/legend.html).

A list of the tags considered by this render is available in [Taginfo JSON
format](https://wiki.openstreetmap.org/wiki/Taginfo/Projects) in [`taginfo.json`](taginfo.json).


## Getting started

Getting started instructions are available in the [`docs/INSTALL.md`](docs/INSTALL.md) file.


## Printing

Instructions for printing maps with a CyclOSM render are available in
the [`docs/PRINT.md`](docs/PRINT.md) file.


## Contributing

Some getting started information for contributing is available in
[`CONTRIBUTING.md`](CONTRIBUTING.md) file.


## Changelog

Changes to this theme are listed in the [`CHANGELOG.md`](CHANGELOG.md) file.
Versions are tagged with Git tags and are available through Github releases
feature.


## MapCSS validators

We also offer some MapCSS checkers for bicycle tags which can be used with
[JOSM](https://josm.openstreetmap.de/wiki/Help/Preferences/Validator) for
instance in the [`validator`](validator) folder of this repository.


## Licenses

This style is based on the [Mapbox
OSM-Bright](https://github.com/mapbox/osm-bright/commit/f1c8780cd7fe9d707fca693a82fdca38b7a98936)
style, which is licensed under BSD-3-Clause license. Everything (be it icons
or code) not listed explicitly below should be consider as available under
this license.

The contours and elevation lines render is based on the very good work and
code available from [OpenTopoMap](https://github.com/der-stefan/OpenTopoMap).

The colors used in the `palette.mss` file are based on the
[Hydda](https://github.com/karlwettin/tilemill-style-hydda/tree/bb27f0a9cad1920e19ae8febd39f6f9328369e6f)
style, licensed under Apache License 2.0.

The icons in `symbols/osm-bright-gl-style` are taken from the [OSM Bright GL
style](https://github.com/openmaptiles/osm-bright-gl-style/tree/327e1b41987893b958e3aae06abc2cc7363dc5aa/icons)
and are licensed under Creative Commons BY 4.0.

The icons in `symbols/openstreetmap-carto` are taken from the
[OpenStreetMap-carto](https://github.com/gravitystorm/openstreetmap-carto)
style and are licensed under CC0 public domain.

The icons in `symbols/osmandapp` are taken from the
[OsmAnd app resources](https://github.com/osmandapp/OsmAnd-resources).

The inner tube bicycle icon is based on
https://www.flaticon.com/free-icon/inner-tube_1575936.


## Links

* http://www.cyclosm.org, official website.
* http://www.cyclosm.org/legend.html, full detailed key.
* https://wiki.openstreetmap.org/wiki/CyclOSM, wiki page on the OSM wiki.
* A list of the tags considered by CyclOSM is available in [Taginfo JSON format](https://wiki.openstreetmap.org/wiki/Taginfo/Projects) in [`taginfo.json`](https://github.com/cyclosm/cyclosm-cartocss-style/blob/master/taginfo.json).


## Related projects

* An unofficial Docker image to deploy a CyclOSM tile server is available at https://github.com/mhajder/openstreetmap-tile-server-cyclosm.
