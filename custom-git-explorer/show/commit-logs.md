---
layout: default
title: commit logs/history
nav_order: 3
parent: show/view
grand_parent: Custom-Git Explorer
permalink: /explorer/show/commit-logs
---

# `glog` / `gshow`
{: .no_toc }

Show the status of the repository including staged, unstaged and untracked files.
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## <i class="fas fa-video"></i> Demo
<div class="container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/XY7koJap_HM?modestbranding=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gadd demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## <i class="fas fa-file-alt"></i> Internals
`git log`
<br>show commit logs. <a href="https://git-scm.com/docs/git-log" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }
 
`git log --pretty='format:%C(auto)%h%d [%an] [%ar] %s' --graph`
<br>pretty-print the contents of the commit logs in a given format. <a href="https://git-scm.com/docs/git-log#_pretty_formats" target="_blank"><i class="fas fa-external-link-alt"></i></a>
<br>draw a text-based graphical representation of the commit history <a href="https://git-scm.com/docs/git-log#Documentation/git-log.txt---graph" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }

`git show <commitSHA>`
<br>show various types of objects <a href="https://git-scm.com/docs/git-show" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }


## <i class="fas fa-code"></i> Implementation
<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fcustom-git%2Fcustom-git-bash%2Fblob%2Fmain%2Fcmd%2Fglog&style=github&showBorder=on&showFileMeta=on&showCopy=on"></script>