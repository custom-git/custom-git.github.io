An open source, general-purpose, highly efficient command line git tool.

### YouTube
Visit the [custom-git YouTube Channel](https://www.youtube.com/channel/UC_pNb_w0nc_mnfBOUtCmhQQ) for videos of hands-on implementation of the custom-git commands.
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBhLj4Qomfk?controls=0&modestbranding=1&disablekb=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="custom-git YouTube teaser" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Note for Windows users
`custom-git` works only with the [Git for Windows](https://git-scm.com/download/win) executable.<br>

### Installation

Run this command in bash or zsh shells.

```shell
if command -v curl >/dev/null 2>&1; then
    $SHELL -c "$(curl -fsSL https://custom-git.io/install)"
else
    $SHELL -c "$(wget -qO- https://custom-git.io/install)"
fi
```

### Try it without installation

Run this command in bash or zsh shells:

```shell
if command -v curl >/dev/null 2>&1; then
    curl -fsSL -o ~/.custom-git.try https://custom-git.io/try
    source ~/.custom-git.try
else
    wget -q -O ~/.custom-git.try https://custom-git.io/try
    source ~/.custom-git.try
fi
```

<br>

### FAQs
`Q.` Not working properly in bash shell on MacOS.<br>
`A.` Make sure ~/.bashrc file is sourced in ~/.bash_profile.<br>
         If not, add the following line at the end of ~/.bash_profile file.<br>
                 source ~/.bashrc

`Q.` What to do if something doesn't work?<br>
`A.` Restart your shell session and try again.<br>
         Reason: network issues may occur while fetching the try or install scripts from the website.

`Q.` What to do if the issue still persists?<br>
`A.` Forward your queries to [support@custom-git.io](mailto:support@custom-git.io).

<br>

## Demos

### gadd \\ *j**ē**-add* \\
`gadd` is a customized version of `git add` command.

<iframe width="600" height="337.5" src="https://www.youtube.com/embed/StaPAVXnAm0?start=166&end=186&controls=0&modestbranding=1&disablekb=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gadd demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br><br>
### Contact Us
Get Support : [support@custom-git.io](mailto:support@custom-git.io) <br>
Say Hello : [hello@bhavidhingra.dev](mailto:hello@bhavidhingra.dev)
