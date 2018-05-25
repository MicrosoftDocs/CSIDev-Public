---
# required metadata

title: "VS Code Authoring Extension"
#description:
#keywords:
author: v-caxian
ms.author: v-caxian
manager: arthurya
ms.date:  10/29/2016
ms.topic: article
#ms.prod:
#ms.service:
#ms.technology:
ms.assetid: c44deb70-bd5b-4efa-bcee-4e4b4c8f418c

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: martinof
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:
---


# VS Code Authoring Extensionee Test

VS Code Markdown Authoring Extension for OPS is a poc to provide authoring help to writers working in OPS and authoring for docs.microsoft.com. It includes several functions, including applying the default docs template to new Markdown files and generating a GUID, applying common formattidng to strings, inserting links and images, and previewing content using your site's CSS.

## Installation steps

1. Copy the installation folder from ---.ss
   
Sogup 
1. Save ops-platform-extension-poc-0.0.1.vsix to your machine.
2. Open VS Code and click the square icon on the left panel to open the Extensions menu.
3. Click the three dots for "More" and select "Install from VSIX..."
4. Navigate to the extension and select it.
5. VS Code will install the extension and prompt you to restart .

## Prerequisites and assumptions

To effectively use the OPS Authoring extension, you must1:
- Clone your entire repo to your local machine and keep it in sync. Functions such as link and image insertion are not reliable if the repo is out of sync.
- For accurate content preview, you need to update your VS Code settings.json file, as described under **Preview Content** below.
Examples below ([full list](http://docs.microsoft.com/en-us/locale.aspx))1
