# Changelog

## [3.4.0](https://www.github.com/jef/streetmerchant/compare/v3.3.0...v3.4.0) (2020-12-27)


### Features

* add redis ([#1390](https://www.github.com/jef/streetmerchant/issues/1390)) ([fb82526](https://www.github.com/jef/streetmerchant/commit/fb82526a427e503fff1f1cf56b091ff0c8a5a96e))
* **azerty:** add ryzen 5000 series  ([#878](https://www.github.com/jef/streetmerchant/issues/878)) ([ca59777](https://www.github.com/jef/streetmerchant/commit/ca59777917777401affc5b72a68238983f286237))
* **lookup:** add max price for xbox ([f34a808](https://www.github.com/jef/streetmerchant/commit/f34a808451b735c384f4b763cedd816c85ab7abc)), closes [#1436](https://www.github.com/jef/streetmerchant/issues/1436)
* **lookup:** add protection against infinite recursion for Cloudflare ([#1505](https://www.github.com/jef/streetmerchant/issues/1505)) ([1cf618c](https://www.github.com/jef/streetmerchant/commit/1cf618c1c12d3ab94688139a8410bed181af3eb2)), closes [#1459](https://www.github.com/jef/streetmerchant/issues/1459) [#1490](https://www.github.com/jef/streetmerchant/issues/1490)
* **lookup:** handle Cloudflare DDoS protection ([#1434](https://www.github.com/jef/streetmerchant/issues/1434)) ([f86a825](https://www.github.com/jef/streetmerchant/commit/f86a8259f37f0ed25b00e243b29aa28c3e68bdff)), closes [#1297](https://www.github.com/jef/streetmerchant/issues/1297)
* **proxy:** fallback to a global proxy list ([#1388](https://www.github.com/jef/streetmerchant/issues/1388)) ([be1953b](https://www.github.com/jef/streetmerchant/commit/be1953b2069fce72969904c1bc18055df73f4b6b))
* **store:** add `johnlewis` store, add `shopto` store ([#1481](https://www.github.com/jef/streetmerchant/issues/1481)) ([ec8d357](https://www.github.com/jef/streetmerchant/commit/ec8d3571cfbbd3a028aed9b5650eb8a52c9af587))
* **store:** add equippr & futurex for DE region ([#1501](https://www.github.com/jef/streetmerchant/issues/1501)) ([5b70ff1](https://www.github.com/jef/streetmerchant/commit/5b70ff14cb9ab5e0a72922624d54b40bb0642bcd))
* **store:** add pcking and acompc ([#1470](https://www.github.com/jef/streetmerchant/issues/1470)) ([beee355](https://www.github.com/jef/streetmerchant/commit/beee35556376056b31d6719fb090ce58b7ea985f))
* remove stale user agents, use top 50 ([6e2a162](https://www.github.com/jef/streetmerchant/commit/6e2a16238c54bc448f3ae5243ef8729f384ea59b))


### Bug Fixes

* disable redis if not configured ([6bc7737](https://www.github.com/jef/streetmerchant/commit/6bc7737ef04e5592e19b0b6a76e5fb0cd4b048df)), closes [#1516](https://www.github.com/jef/streetmerchant/issues/1516)
* **amazon-de-warehouse:** update wrong maxPrice selector ([#1514](https://www.github.com/jef/streetmerchant/issues/1514)) ([90fb430](https://www.github.com/jef/streetmerchant/commit/90fb430b712aa6a89227a17d37a83380326db21b))
* properly pass array entries as separate indices ([#1502](https://www.github.com/jef/streetmerchant/issues/1502)) ([0c6e2d5](https://www.github.com/jef/streetmerchant/commit/0c6e2d587d81041b07a561b3f53b8b1ebcb9f843))
* **galaxus:** maxPrice selector ([#1469](https://www.github.com/jef/streetmerchant/issues/1469)) ([7a5bc22](https://www.github.com/jef/streetmerchant/commit/7a5bc22ba8cede51311b80182c18fb0227532cd2))
* **lookup:** check out of stock before price ([#1422](https://www.github.com/jef/streetmerchant/issues/1422)) ([02d29c3](https://www.github.com/jef/streetmerchant/commit/02d29c3c64a7976622da6cbdf099b76b455082d0))
* **lookup:** remove mobile versions of user agent ([96ae818](https://www.github.com/jef/streetmerchant/commit/96ae818e84c99d0597e0ddd7b5ecfe1a0615d1ed))
* **proxy:** fix requests with proxies ([#1408](https://www.github.com/jef/streetmerchant/issues/1408)) ([f65df4c](https://www.github.com/jef/streetmerchant/commit/f65df4ce56891c368dab8dd6fe85a584cf9e6f49))
* **proxy:** update proxy module ([#1451](https://www.github.com/jef/streetmerchant/issues/1451)) ([ab03702](https://www.github.com/jef/streetmerchant/commit/ab037029b654f5e169a97c9e7a2c4dfa6cf1e768)), closes [#1437](https://www.github.com/jef/streetmerchant/issues/1437)
* **store:** link builder in UK stores ([#1486](https://www.github.com/jef/streetmerchant/issues/1486)) ([eb59dc3](https://www.github.com/jef/streetmerchant/commit/eb59dc3433c54027695fb68cfe69b1d90fce3fec))
* **webui:** handling of file serving ([#1383](https://www.github.com/jef/streetmerchant/issues/1383)) ([445689e](https://www.github.com/jef/streetmerchant/commit/445689efc49bf8edb0b5a027611f02ea0d0f126f))
