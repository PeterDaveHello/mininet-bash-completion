# mininet-bash-completion
bash tab-completion script for Mininet (mn) network emulator

This bash-completion script for Mininet network emulator is develmented
based on the awesome `bash-completion` project, which means its depends on
`bash-completion`.

Though `bash-completion` may be installed by default (or by package suggestions
of bash) in many unix-like distros, please make sure you already have it
on your environment, so that these completion can work properly, e.g. see
if you have one of these files in your system:


```
/usr/share/bash-completion/bash_completion
/usr/local/share/bash-completion/bash_completion
```

Above are the most common paths that `bash-completion` will be installed.

Once you make sure you have `bash-completion`, you can now just simply download
and put the `mn` script into `bash-completion`'s `completions` folder, e.g. :

```sh
wget https://github.com/PeterDaveHello/mininet-bash-completion/raw/master/mn
cp /source/path/of/mn /usr/share/bash-completion/completions/
```

Then re-active `bash-completion`:

```sh
source /usr/share/bash-completion/bash_completion
```

Now you can use `mininet`'s command `mn` with some auto-completions!


The whole project is released under GPL-3.0 license, please read the LICENSE
file under the root of the project repository for the details.

For the detail about bash-completion , please visit its homepage and GitHub:
 - https://alioth.debian.org/projects/bash-completion/
 - https://github.com/scop/bash-completion

For the detail about Mininet, please visit its homepage and GitHub:
 - http://mininet.org
 - https://github.com/mininet/mininet
