# gNMI Map
[![map](https://gitlab.com/rdodin/pics/-/wikis/uploads/6a9d18f9cb2240656aad5d224aa757df/rsz_image.png)](https://gitlab.com/rdodin/pics/-/wikis/uploads/485da1057531a4844b464708acf35dce/gnmi_0.7.0_map.pdf)

gNMI Map provides a visual representation of the [gNMI](https://github.com/openconfig/reference/blob/master/rpc/gnmi/gnmi-specification.md) service.

It contains all the RPCs, messages and custom types defined in the [gnmi.proto](https://github.com/openconfig/gnmi/blob/master/proto/gnmi/gnmi.proto) file mapped as a block diagram with inter-message relationship.

gNMI Map makes it easy to understand the composition of the gNMI service as well as it provides the relevant links to the documentation and proto references.

<p align=center><img src="https://gitlab.com/rdodin/pics/-/wikis/uploads/61e7fa143e5898653c1edb9b42b936f3/image.png" width="600" /></p>

## Usage
The map can be downloaded from this repository or viewed right in a browser. The maps for the following gNMI service versions have been created so far:

* **gNMI 0.7.0** - [view](https://gitlab.com/rdodin/pics/-/wikis/uploads/485da1057531a4844b464708acf35dce/gnmi_0.7.0_map.pdf) / [download](https://github.com/hellt/gnmi-map/raw/master/gnmi_0.7.0_map.pdf)

## OS X Preview app issue
Mac OS X default PDF reader app - Preview - messes with the link fragments (`http://url.com/page#fragment`), therefore the links won't work in this app (see [1](https://discussions.apple.com/thread/251041261), [2](https://discussions.apple.com/thread/250919338)).