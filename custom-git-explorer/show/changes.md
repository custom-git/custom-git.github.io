---
layout: default
title: changes
nav_order: 2
parent: show/view
grand_parent: Custom-Git Explorer
permalink: /explorer/show/changes
---

# `gdiff`
{: .no_toc }

Show changes of all the files (staged, unstaged, untracked etc.) in one scrollable list.
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## <i class="fas fa-video"></i> Demo
<div class="container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/S2D2jWXWlrA?modestbranding=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gdiff demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## <i class="fas fa-file-alt"></i> Internals
`git diff -- <filepath>`
<br>view the changes you made relative to the index (staging area for the next commit).
{: .fs-5 .fw-300 }

`git diff --cached -- <filepath>`
<br>view the changes you staged for the next commit relative to HEAD.
{: .fs-5 .fw-300 }

`git diff -- <oldpath> <newpath>`
<br>compare changes in the given two paths (while renaming a file).
{: .fs-5 .fw-300 }

`git diff --cached -- <oldpath> <newpath>`
<br>compare changes if the ranamed file is staged for the next commit. 
{: .fs-5 .fw-300 }

<a href="https://git-scm.com/docs/git-diff" target="_blank"><i class="fas fa-external-link-alt"></i> Ref.</a>

## <i class="fas fa-code"></i> Implementation
<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fcustom-git%2Fcustom-git-bash%2Fblob%2Frelease-1.0%2Fcmd%2Fgdiff&style=github&showBorder=on&showFileMeta=on&showCopy=on"></script>>