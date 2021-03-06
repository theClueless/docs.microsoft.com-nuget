---
# required metadata

title: NuGet 3.4.1 Release Notes | Microsoft Docs
author: karann-msft
ms.author: karann-msft
manager: ghogen
ms.date: 11/11/2016
ms.topic: article
ms.prod: nuget
#ms.service:
ms.technology: null
ms.assetid: b016587f-0203-46c7-983d-abb03766f162

# optional metadata

description: Release notes for NuGet 3.4.1 including known issues, bug fixes, added features, and DCRs.
keywords: NuGet 3.4.1 release notes, bug fixes, known issues, added features, DCRs
#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer:
- karann-msft
- unniravindranathan
#ms.suite:
#ms.tgt_pltfrm:
#ms.custom:

---

# NuGet 3.4.1 Release Notes

[NuGet 3.4 Release Notes](../release-notes/nuget-3.4.md) | [NuGet 3.4.2 Release Notes](../release-notes/nuget-3.4.2.md)

NuGet 3.4.1 was released March 30, 2016 at the same time as the Visual Studio 2015 Update 2 and Visual Studio 15 Preview Release to address several issues that were identified in the 3.4 release.

## Updates and Improvements

* Corrected an issue that prevented browsing packages from the Visual Studio UI with a minimum Visual Studio install
* Corrected an issue with Visual Studio locating `lucene.net.dll`
* All sources should not be the default repository source after a NuGet extension install or update.  You can opt-in to this feature from the configuration settings.

We continue to track issues on our GitHub issues list which can be found at: [http://github.com/nuget/home/issues](http://github.com/nuget/home/issues)