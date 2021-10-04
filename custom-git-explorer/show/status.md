---
layout: default
title: status
nav_order: 1
parent: show/view
grand_parent: Custom-Git Explorer
permalink: /explorer/show/status
---

# `gstatus`
{: .no_toc }

Shows the status of the repository (staged, unstaged, untracked files etc.), after clearing the terminal screen.
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## <i class="fas fa-video"></i> Demo
<div class="container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/5dB2JSyE14w?modestbranding=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gstatus demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## <i class="fas fa-file-alt"></i> Internals
`clear` - clear the terminal screen <a href="https://linux.die.net/man/1/clear" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }
`git status` - show the working tree status <a href="https://git-scm.com/docs/git-status" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }

## <i class="fas fa-code"></i> Implementation
<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fcustom-git%2Fcustom-git-bash%2Fblob%2Frelease-0.3%2Fcmd%2Fgstatus&style=github&showBorder=on&showFileMeta=on&showCopy=on"></script>