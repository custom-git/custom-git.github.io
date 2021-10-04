---
layout: default
title: new changes
parent: add
grand_parent: Custom-Git Explorer
permalink: /explorer/add/new-changes
---

# `gadd`
{: .no_toc }

Easily select the modified or untracked files from a list to stage them for the next commit.
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
## <i class="fas fa-video"></i> Demo
<div class="container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/tp2_sGJMe1A?modestbranding=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gadd demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## <i class="fas fa-file-alt"></i> Internals
`git add <filepath>`
<br>add file contents to the index. <a href="https://git-scm.com/docs/git-add" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }

`git add --intent-to-add <filepath>`
<br>An entry for the path is placed in the index with no content. This is useful for showing the contents of a new file with `git diff` <a href="https://git-scm.com/docs/git-add#Documentation/git-add.txt--N" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }


## <i class="fas fa-code"></i> Implementation
<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fcustom-git%2Fcustom-git-bash%2Fblob%2Fmain%2Fcmd%2Fgadd&style=github&showBorder=on&showFileMeta=on&showCopy=on"></script>