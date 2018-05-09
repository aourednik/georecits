# GéoRécits: mapping journeys and lived spaces

Spatial mobility always involves at least two types of distances:

- the _topographical distance_ traveled on the surface of the Earth and
- the _time distance_ taken to do so.

GéoRécits allows you to map both in your web browser. It is written using HTML5, SVG and JavaScript. It uses the visualisation framework [D3js](https://github.com/d3/d3), version 5. Maps can be exported to SVG, editable in _Illustrator_ (CC and above) or _Inkscape_.

[Full documentation is available HERE](https://ourednik.info/georecits/)

## Online version

In the newest, experimental, version, you can __drag and drop__ files to see instantly rendered maps.
This version also gives you advice on repairing misconfigured innput data files. It is [available for oline use HERE](https://ourednik.info/georecits/v02/).

You can also test the stable 01 version online [HERE (lived spaces)](https://ourednik.info/georecits/v01_livedspaces/) and [HERE (journeys)](https://ourednik.info/georecits/v01_journeys/).

![GéoRécits spatial portrait](/img/georecits02.gif)

## Offline use

For offline use, the version 01 and 02 both works best in _Firefox_ (v. > 54) or _MS Edge_. (_Chrome_ and _Safari_ block FetchAPI in D3 from accessing local csv and json files).

## Examples

Example data are available in folders _/data_ (default), _/data2_ and _/data3_.

### Journeys

See [running example here](https://ourednik.info/georecits/v02_journeys/).

![GéoRécits journeys](/img/georecits1.png)

### Lived spaces

See [running example here](https://ourednik.info/georecits/v02/).

![GéoRécits spatial portrait](/img/georecits3.png)