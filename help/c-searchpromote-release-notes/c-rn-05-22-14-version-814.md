---
description: Search&amp;Promote 8.14.0 release notes.
solution: Target
title: Search&amp;Promote 8.14.0 Release Notes (05/22/2014)
topic-legacy: Release Notes,Site search and merchandising
uuid: 308d84a9-ec38-4fec-b146-e8a353e65be4
exl-id: fcc00d85-128e-4015-aa82-7d31606cb076
---
# Search&amp;Promote 8.14.0 Release Notes (05/22/2014){#search-promote-release-notes}

 **Fixes**

* If [!DNL sqlite_open] fails, the old sqlite database file is moved out of the way and a new one is created from scratch. 
* Core search results were inconsistent when the same search was repeated. 
* Performance improvement of template processing when there are many fields being output per search result. 
* Added Notes to **[!UICONTROL Business Rule History]**. 
* Performance of the result-based triggers and actions preview-index regeneration phase, during indexing operations, steadily degraded over time. 
* Changed **[!UICONTROL Reset SPIN cache]** option from boolean no/next-run to a tri-state: no/always/next-run.
