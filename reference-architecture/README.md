# Reference Architecture for OpenShift
This repository contains a series of directories containing code used to deploy an OpenShift environment on different cloud providers. The code in this repository supplements the Reference Architecture Guides for OpenShift 3.2. Different guides and documentation exists depending on the different providers.

## Overview
The repository contains different directories with the same goal depending on the provider. Regardless of the provider, the envionment will deploy 3 Masters, 2 infrastructure nodes and 2 applcation nodes. The code also deploys a Docker registry and scales the router to the number of Infrastruture nodes.
