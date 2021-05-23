An open source, general-purpose, highly efficient command line git tool.

### Note for Windows users
`custom-git` works only with the [Git for Windows](https://git-scm.com/download/win) executable.<br>

### Installation

Run this command in bash or zsh shells.

```shell
if command -v curl >/dev/null 2>&1; then
    sh -c "$(curl -fsSL https://custom-git.io/install)"
else
    sh -c "$(wget -qO- https://custom-git.io/install)"
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
`A.` Please paste it in the comment section.<br>
         You can also forward your queries to connect@bhavidhingra.dev.

<br>

## Usage

### gadd \\ *j**ē**-add* \\
`gadd` is a customized version of `git add` command.
A quick demo:
<div>
    <script id="asciicast-g3BNw6dsZpYqNH8bj0SF6U2pZ" src="https://asciinema.org/a/g3BNw6dsZpYqNH8bj0SF6U2pZ.js" data-cols="175" data-rows="35"></script>
</div>

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
