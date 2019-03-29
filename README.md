# Organism Explorer
_This project comes from the split of the original [exploreAT-collectionexplorer](https://github.com/acdh-oeaw/exploreAT-collectionexplorer) of [Alex Benito](https://github.com/ale0xb)_

Scientific and Common Plant name explorer based on RDF data and connected to Europeana.

With organism explorer the user can select a scientific plant name from a pre-set list. Corresponding common names (phonetic, written) are displayed in addition, as well as possible related Europeana entries (video,audio, pictures) on a map.

![Prototye screenshot](img/prototype.png "Prototype screenshot")

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

Dependencies are been migrated from [Bower](https://bower.io/) with [bower-away](https://github.com/sheerun/bower-away). Therefore yarn or npm may be used for installing
the dependencies.

As indicated in **Bower** official site, it is recommended not to use it to manage the dependencies.

```
yarn
```
or
```
npm install
```

You can use any static server of your choice to serve the files for the webpage.
Additionally, [webpack](http://www.dropwizard.io/1.0.2/docs/) may be used for compiling the source code
and package it into a few files (friendlier with download speed for the webpage).

**This prototype needs for an ElasticSearch database, and an [API](https://github.com/acdh-oeaw/exploreAT-collectionexplorer-api) for retrieving data from Europeana and Flickr.**

## Authors

* [Antonio Losada](https://github.com/notsomes) - *Implementation of the prototype* 
* [Alex Benito](https://github.com/ale0xb) - *Implementation of the prototype* 
* [Alejandro Rodríguez](https://github.com/Janchorizo) - *Project split and migration to newer package managers* 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

