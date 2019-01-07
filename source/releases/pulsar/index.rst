XDC-1 (Pulsar)
==============

The `eXtreme-DataCloud <https://extreme-datacloud.eu/>`__
project is pleased to announce the general availability of its **first
public software release**, codenamed **Pulsar**

This release …

Included components
-------------------

.. toctree::
   :maxdepth: 1

   orchent
   paas-orchestrator
   ttt


Highlights
----------


Key technical highlights:

-  PaaS Orchestrator

   -  Hybrid deployments on multiple sites
   -  Support to specifying specialized computing hardware Improved
      support for deployment failures


Release Notes
-------------

The XDC-1/Pulsar release consists in X Products and guides:

-  X OS packages

   -  Y RPMS & SRPMS
   -  Z binary & source DEBS
   -  W binary & source tarballs

-  T Docker containers

The release is fully supported 
- on the following Operating Systems platforms: 
   - CentOS 7
   -  Ubuntu 18.04
   - Optionally PTs support also other OS platforms. You can find more information in the individual
products documentation.

You can find in the later sections the full list of products, with
detailed release notes and instructions for their
installation/configuration.

Installation Notes
------------------

All eXtreme-DataCloud products are distributed from standard
OperatingSystems (OS) repositories and DockerHub registry.

The packages repositories have the following structure:

-  XDC production (stable): xdc/production/{1,2}///{base|updates}

   -  stable and signed, well tested software components
   -  Third-party: xdc/production/{1,2}///third-party

      -  packages that are not part of XDC, or not part of the base
         OS or EPEL, but used as dependencies by other XDC components

-  XDC testing: xdc/testing/{1,2}//

   -  packages that will become part of the next stable distribution; in
      the certification and validation phase.

-  XDC preview: xdc/preview/{1,2}//

   -  signed packages that will become part of the next stable update,
      available for technical-previews

where \* is currently: x86_64, SRPMS (for CentOS7), and binary-amd64,
source (for Ubuntu) \* is currently: centos7, ubuntu/dists/bionic/main

All packages are signed with the INDIGO - DataCloud gpg key. The public
key can be downloaded from
`here <http://repo.indigo-datacloud.eu/repository/RPM-GPG-KEY-indigodc>`__,
and the fingerprint from
`here <http://repo.indigo-datacloud.eu/repository/INDIGODC_key_fingerprint.asc>`__.

It is strongly recommended the use of the lastest version of the
xdc-release packages containing the public key and the YUM and APT
repository files.

On the `DockerHub Registry <https://hub.docker.com/>`__, eXtreme-DataCloud uses the INDIGO - DataCloud and XDC Organizations:

-  `indigodatacloud <https://hub.docker.com/u/indigodatacloud/dashboard/>`__,
   for Core Services
-  `xdc <https://hub.docker.com/u/xdc/dashboard/>`__, for
   user applications modules

Containers present in those repositories and released in XDC-1 are
tagged with “XDC-1” tag and signed, leveraging the Docker’s trust
features so that users can pull trusted images.

To understand how to install and configure XDC-1/Pulsar services and
components either refer to the `Generic Installation and Configuration
Guide <https://add_generic>`__ chapter or to each individual product
documentation.

Software
--------

XDC-1 software can be downloaded from `eXtreme-DataCloud repositories <http://repo.indigo-datacloud.eu/repository/xdc/>`__.

Documentation
-------------

Please find XDC-1 documentation `here <https://releases.extreme-datacloud.eu/>`__.

Support
-------

Most complex software contains bugs, we are not an exception. One of the
features of free and open source software is the ability to report bugs,
helping to fix or improve the software you use.

eXtreme-DataCloud project uses …

More details regarding each product support channels are provided in the
respective products release pages.

Developers, researchers and IT enthusiasts: feel free to write to
info@project to ask for more information on how to use XDC solutions
for your work. For automatic notifications you can register to the eXtreme-DataCloud release RSS feed or subscribe to the 
eXtreme-DataCloud Announce Mailing list. You can also socialize with us
via Twitter, Facebook and join our LinkedIn group.