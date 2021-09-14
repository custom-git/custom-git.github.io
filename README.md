An open source, general-purpose, highly efficient command line git tool.

### YouTube

Visit the [custom-git YouTube Channel](https://www.youtube.com/channel/UC_pNb_w0nc_mnfBOUtCmhQQ) for videos of hands-on implementation of the custom-git commands.

<iframe width="600" height="337.5" src="https://www.youtube.com/embed/StaPAVXnAm0?controls=0&modestbranding=1&disablekb=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gadd demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Note for Windows users

`custom-git` works only with the [Git for Windows](https://git-scm.com/download/win) executable.<br>

### Installation

Run this command in bash or zsh shells.

```shell
if command -v curl >/dev/null 2>&1; then
    bash -c "$(curl -fsSL https://custom-git.io/install)"
else
    bash -c "$(wget -qO- https://custom-git.io/install)"
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

### gadd \\ _j**ē**-add_ \\

`gadd` is a customized version of `git add` command.

<iframe width="600" height="337.5" src="https://www.youtube.com/embed/StaPAVXnAm0?start=166&end=186&controls=0&modestbranding=1&disablekb=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gadd demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br><br>

### Contact Us

Get Support : [support@custom-git.io](mailto:support@custom-git.io) <br>
Say Hello : [hello@bhavidhingra.dev](mailto:hello@bhavidhingra.dev)

<br>

### Disqus

<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */

    var disqus_config = function () {
        this.page.url = 'https://custom-git.io';  // Replace PAGE_URL with your page's canonical URL variable
        this.page.identifier = 'j0SakKsidsdA5L8XPnxz'; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };

    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://custom-git.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();

</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

