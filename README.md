# PanOS Bootstrapper UI

This project will quickly spin up the PanOS bootstrapper service and a simple UI to consume the bootstrapper API. Using
this tool, an architect or designer can create and manage the templates necessary to configure a Palo Alto Networks
device upon first boot. A fully customized UI can then use those templates to allow an operator to input only those 
variables necessary to compile those templates into a bootstrap package. 

For details about the bootstrapping process, refer to the official 
[documentation](https://www.paloaltonetworks.com/documentation/71/pan-os/newfeaturesguide/management-features/bootstrapping-firewalls-for-rapid-deployment.html).

### Installation

1. Install docker

2. clone or download this repository

```bash
git clone git@github.com:PaloAltoNetworks/panos-bootstrapper-ui.git

```
3. Init the required submodules

```bash
cd panos-bootstrapper-ui
git submodule init
git submodule update
```
4. Build the docker containers

```bash
docker-compose build
```

4. Launch the docker containers

```bash
docker-compose up
```
6. Browse to http://localhost


