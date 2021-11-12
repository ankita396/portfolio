---
layout: post
title:  "Technical Writing Sample"
date:   2021-11-11 20:20:32 +0200
description: 
img: api-version.jpeg
tags: [API, Techinical Writing, Sample]
author: Ankita Parida
---
# API Versioning and Support Cycle
--------------

## Versioning
ABC supports versioning so that our internal and external stakeholders (developers, users, businesses) can stay up-to-date with changes and new releases. 

We follow the [Semantic Versioning 2.0.0](https://semver.org/) convention.

Versions are named as follows: MAJOR.MINOR.PATCH

A **Major** version is released when backwards-incompatible (outlined below) changes are implemented. Following is a non-exhaustive list of changes that warrants a major version release: 
- Removal of an API endpoint 
- Removal of an API attribute 
- Change in any API data formats 
- Database changes which can not be migrated automatically 
- Change in script syntax, which may break existing scripts 
  
A **Minor** version is released on the implementation of backwards-compatible (outlined below) changes. Following is a non-exhaustive list of changes that warrants a minor version release: 
- Addition of an API endpoint 
- Addition of an API attribute 
- Database changes which can be migrated automatically 
- Change in script syntax which can be migrated automatically 

A **Patch** version is released with bug fixes and minor improvements which do not cause any backward incompatibility.
   
**Example:** 
```
v1.3.2 - signifies this is the first major release. It has 3 minor versions with 2 patches in this minor version
```


### Curious about the latest changes?
The current version is **v3.4.3**. 

You can find more information about our version timelines, release dates and changes on our [changelog](https://fakelink.com/releases) page. 

## Deprecation 
To keep our services in line with customer expectations, certain outdated features are replaced with better functionalities from time to time. APIs are also deprecated to minimize critical security risks and to ensure legal compliance. We take the following steps to mitigate the effect of API deprecations and make the transition smoother for our users:
- Feature deprecations are released with a minor version.
- Part of the feature (which needs to be changed) is deprecated before introducing the backwards-incompatible change. This ensures a wide window for clients to prepare for the upcoming change.
- An alternative is usually available at the time of deprecation so no additional transition time is needed once the backwards-incompatible change is introduced. 
- Deprecated APIs are announced in the changelog of the release where the deprecation was introduced to keep users informed. 
   
## Support cycle 

We provide support to each major version for a period of at least two years starting from the first release of that major version. The support cycle for the latest major version is continued until a new major version is released.

During the support period, we do not add minor releases to past major versions, but we may add patch updates if required. 

We do not adhere to a fixed release schedule. Our efforts are always geared towards keeping the platform stable with the least amount of incompatible changes. We aim to minimize the number of major releases and guarantee that there won’t be more than one major release per year. 

Visit our [knowledge base](https://ankita396.github.io/portfolio/) to discover more about our API lifecycle management. 







