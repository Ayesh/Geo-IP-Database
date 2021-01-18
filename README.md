# Geo IP Database

This is an automated repository that downloads and processes GeoLite database from [Maxmind GeoLite database](#source), and processes it to be consumed by [`ayesh/geo-ip`](https://github.com/Ayesh/Geo-IP) composer package. 


This repository only contains the JSON files that other packages (mainly [`ayesh/geo-ip`](https://github.com/Ayesh/Geo-IP)) consumes. 

This repository is automatically updated on every Monday, and if there are new changes, a new minor version will be tagged and published automatically. 

See [`Ayesh/Geo-IP-Tree-Builder`](https://github.com/Ayesh/Geo-IP-Tree-Builder) for the actual parser.

## Usage

[`ayesh/geo-ip`](https://github.com/Ayesh/Geo-IP) package is the main target use case, and that package `require`s this repository. If you use `ayesh/geo-ip` package, no further action is necessary.

### Composer

```bash
composer require ayesh/geo-ip-database ^1.0.0
```

### NPM/Yarn

```bash
npm i @ayesh/geo-ip-database
```

## Updates

This repository will be updated and tagged automatically. Make sure to require the `ayesh/geo-ip-database` without pinning a specific version (e.g `^1.0.0`), and running `npm up` or `composer update` should automatically use the newest database version.


## Source

This product includes GeoLite2 data created by MaxMind, available from [https://www.maxmind.com](https://www.maxmind.com).
