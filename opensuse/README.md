<!--

********************************************************************************

WARNING:

    DO NOT EDIT "opensuse/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "opensuse/" combined with a set of templates)

********************************************************************************

-->

# Supported tags and respective `Dockerfile` links

-	[`42.2`, `leap`, `latest` (*docker/Dockerfile*)](https://github.com/openSUSE/docker-containers-build/blob/93e7f9aedeed72db8a1ae0db549e64ad984103b5/docker/Dockerfile)
-	[`42.1` (*docker/Dockerfile*)](https://github.com/openSUSE/docker-containers-build/blob/658966689be7d4e9c9e073e6b782e2be9c5f909a/docker/Dockerfile)
-	[`13.2`, `harlequin` (*docker/Dockerfile*)](https://github.com/openSUSE/docker-containers-build/blob/81aea7039301342026ed4b2ce5644f4fa838a87a/docker/Dockerfile)
-	[`tumbleweed` (*docker/Dockerfile*)](https://github.com/openSUSE/docker-containers-build/blob/207eb3b9bc8fb20dd1ffc37e4993d6185d828ad2/docker/Dockerfile)

# Quick reference

-	**Where to get help**:  
	[the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](https://blog.docker.com/2016/11/introducing-docker-community-directory-docker-community-slack/), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

-	**Where to file issues**:  
	[https://github.com/openSUSE/docker-containers-build/issues](https://github.com/openSUSE/docker-containers-build/issues)

-	**Maintained by**:  
	[the SUSE containers team](https://github.com/openSUSE/docker-containers-build)

-	**Published image artifact details**:  
	[repo-info repo's `repos/opensuse/` directory](https://github.com/docker-library/repo-info/blob/master/repos/opensuse) ([history](https://github.com/docker-library/repo-info/commits/master/repos/opensuse))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images PRs with label `library/opensuse`](https://github.com/docker-library/official-images/pulls?q=label%3Alibrary%2Fopensuse)  
	[official-images repo's `library/opensuse` file](https://github.com/docker-library/official-images/blob/master/library/opensuse) ([history](https://github.com/docker-library/official-images/commits/master/library/opensuse))

-	**Source of this description**:  
	[docs repo's `opensuse/` directory](https://github.com/docker-library/docs/tree/master/opensuse) ([history](https://github.com/docker-library/docs/commits/master/opensuse))

-	**Supported Docker versions**:  
	[the latest release](https://github.com/docker/docker/releases/latest) (down to 1.6 on a best-effort basis)

# openSUSE

This project contains the stable releases of the openSUSE distribution.

# Naming conventions

Each image is tagged using both the release number (eg *"13.1"*) and the code name (eg *"Bottle"*). The latest stable release is always available using the "*latest*" tag.

# Building

These images are generated using [KIWI](https://github.com/openSUSE/kiwi). Their source file can be found on [this repository](https://github.com/openSUSE/docker-containers).

# Repositories and packages

The package selection is kept minimal to reduce the footprint of the image.

However the following repositories are already part of the image:

-	OSS
-	OSS Updates
-	Non-OSS
-	Non-OSS Updates
