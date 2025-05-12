<!-- badges: start -->

![lifecycle](https://img.shields.io/badge/lifecycle-active-green.svg)
[![NSF-2410965](https://img.shields.io/badge/NSF-2410965-blue.svg)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2410965&HistoricalAwards=false)
[![NSF-2410961](https://img.shields.io/badge/NSF-2410961-blue.svg)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2410961&HistoricalAwards=false)

<!-- badges: end -->

# Best Practices for Neotoma GitHub Repos
A repo that describes the recommended practices for setting up new repositories within the Neotoma Paleoecology Database.

## Initial Set up

### Repo Name
Choose a short and identifiable name for your repo.

### Description
Add a short description of the purpose of the repo; additional description will be put in the README.

### Public vs Private
Most repos will be public or made public upon the publication of the resource.

### README
This box should be checked upon repo set up. All repos should have a descriptive README document (see below).

### Gitignore
Check this if necessary for your specific project.

### License
All repos should have an appropriate license. The MIT license is a good default for NeotomaDB repos.

## README
### General advice
Your repository's README should provide a brief yet informative description of the repository's goal or mission (what it does, why it matters etc.).


This should allow new users or collaborators to understand the context of the project without having to sift through excessive or irrelevant information. 
### Badges
Badges provide at-a-glance information about a project's status, funding, and more. They improve the readability of your repo by quickly communicating key project metadata.

Including badges helps show that a project is actively maintained, clearly supported, and easy to trust.

***-Lifecycle Badges*** 

Lifecycle badges indicate the current development status of the project. 

These badges are adapted from the [r-lib lifecycle stages](https://lifecycle.r-lib.org/articles/stages.html) and use [shields.io](https://shields.io/) for badge rendering. The Neotoma version uses modified definitions and badges to better reflect internal project workflows and standards.


**Experimental**

The experimental badge indicates the project is in an early stage of development. It is subject to rapid changes, and features may be incomplete or unstable. 

```
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)

```

**Active**

The active badge indicates the project is developed and maintained. New features may be added, but they would integrate into a mature project; also considered production-ready.

*Note: We cannot link to a formal lifecycle stage for "active" as it is not part of the traditional classification.*

```
[![lifecycle](https://img.shields.io/badge/lifecycle-active-green.svg)]

```

**Stable**

The stable badge indicates the project is stable but not actively maintained unless needed. It is unlikely to experience significant changes; also considered production-ready.

```
[![lifecycle](https://img.shields.io/badge/lifecycle-stable-green.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)

```

**Paused**

The paused badge indicates the projects' development and maintenance has been temporarily put on hold. This badge implies updates to the repo will, most likely, resume. 

*Note: We cannot link to a formal lifecycle stage for "paused" as it is not part of the traditional classificiation.*

```

[![lifecycle](https://img.shields.io/badge/lifecycle-paused-orange.svg)]

```

**Archived**

The archived badge indicates the project is no longer maintained. It is preserved for reference, but updates and support are not provided. 

```
[![lifecycle](https://img.shields.io/badge/lifecycle-archived-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#archived)

```

**Deprecated**

The deprecated badge indicates the project is no longer recommended for use. It may be removed in the future. If there is a different recommended repo, it may have a link to the relevant repo.

```
[![lifecycle](https://img.shields.io/badge/lifecycle-deprecated-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#deprecated)

```

**Superseded**

The superseded badge indicates the project has been replaced by a newer or more complete solution. Users should migrate to the successor project. A link has been provided to the new project.

```
[![lifecycle](https://img.shields.io/badge/lifecycle-superseded-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#superseded/or link to successor repo)

```

***-NSF Grant Badges***

These badges recognize the support of specific NSF grants and link to their award details.

**Badge Display + Markdown Code**

![Badge Display](Example-badge-image.png)


```
<!-- badges: start -->

[![lifecycle](https://img.shields.io/badge/lifecycle-active-green.svg)]
[![NSF-1948926](https://img.shields.io/badge/NSF-1948926-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1948926)
[![NSF-2410961](https://img.shields.io/badge/NSF-2410961-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=2410961)

<!-- badges: end -->
```



## Other Recommended Practices
### Code of Conduct
Include a Contributor Code of Conduct to help ensure a respectful, inclusive, and harassment-free environment for all contributors. This sets a clear tone for collaboration. 


This repository contains a standard Code of Conduct in the files section, which outlines necessary expectations for behavior and procedures regarding the reports of misconduct. This is the default Code of Conduct for Neotoma. 
### Website
If your repo has a related website or documentaion hub, include the link in your repo settings and mention it in the README.

If there is ***no specific website for your project***, you can link to the [Neotoma Paleoecology Database](https://www.neotomadb.org) as the relevant organizational or umbrella website.
### Topics
Use Github's "topics" feature to tag your repo with relevant keywords (e.g, neotomadb, paleoecology, data, R, JS, etc.)


This improves discoverability and helps categorize your repo for others in the community.
### Releases
Use Github Releases to provided downloadable versions of your project, including versioned snapshots of documentation or templates.


Even if your repo isn't code-based, you can tag major updates to show development. 
### Citations
Encourage users to cite your work if they use your software, package, documentation, etc.


You can include a *Citation.CFF* file in the root of your repo (GitHub will automatically offer citation info)