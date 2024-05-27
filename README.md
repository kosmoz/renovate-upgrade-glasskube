This repository demonstrates what a dependency upgrade bot such as [renovate](https://github.com/renovatebot/renovate) upgrading a Glasskube installation could look like.
The file `glasskube-system.yaml` contains a Glasskube installation in version v0.4.1. 
There is an open PR that upgrades this Glasskube installation to v0.6.0. 

To create this demonstration, I downloaded the prebuilt manifests from the Glasskube [releases](https://github.com/glasskube/glasskube/releases) page on GitHub.
A real installation might look slightly different, because the glasskube CLI does some preprocessing on the resources, but for the most part it should be the same.
