---
layout: secondary
---
# Managing and visualizing Atlas images using OMERO

This guide aims to walk you through the process for managing and visualizing 

1. multiplexed whole-slide images (WSIs), such as image generated using CyCIF and CODEX, and 
1. bright-field WSIs such as H&E and IHC images

using OMERO and PathViewer.

## Generate compatible input images

To visualize WSIs, image pyramid is commonly used for efficiency. Refer to the [pyramid column in this table](https://docs.openmicroscopy.org/bio-formats/6.7.0/supported-formats.html) for file support status. For multiplex images, raw data usually need to be process before uploading to the OMERO server, we developed and utilized [MCMICRO](https://mcmicro.org) to process the CyCIF data for the Atlas.   

## OMERO (webapp and desktop application)

1. Basic setup, such as account request and client side desktop application (OMERO.insight) can be found under the OMERO section on this [HMS IT page](https://it.hms.harvard.edu/our-services/research-computing/services/research-applications-software/research-application)

1. [OMERO.insight HMS connecting instruction](https://harvardmed.service-now.com/kb_view.do?sysparm_article=KB0011694)
    - User must be within the HMS Network or on [HMS VPN](https://it.hms.harvard.edu/our-services/network-and-servers/vpn)
    - OMERO server address: `omero-app.hms.harvard.edu`

1. Follow the [setp-by-step guide (skip step 1 through 4)](https://omero-guides.readthedocs.io/en/latest/upload/docs/import-desktop-client.html#step-by-step) to upload (import) your data into OMERO server, note that one can ctrl/cmd click to selec multiple local files.

1. After upload is completed, go to [HMS OMERO.web](https://omero.hms.harvard.edu/webclient/) to confirm

1. [Guide for downloading images from OMERO server using OMERO.client](https://slack-files.com/T069QPDCJ-F011JPEN5FD-ae133b961a)

1. [Guides for managing dataset structure on OMERO.web](https://omero-guides.readthedocs.io/en/latest/introduction/docs/data-management.html)

1. Change channel names for multiplex images

1. Copy and apply rendering settings

## PathViewer

1. Group channels for multiplexed image

1. PathViewer Grid


## OMERO.figure
