Analytics with R
----------------

The icons `database_icon`, `user_icon`, `file_icon` and `folder_icon` in the
`SVG` directory are taken from Google's
[material design icons](https://github.com/google/material-design-icons)
collection. The rest of the SVG graphics were made with
[Inkscape](https://inkscape.org/en/).


#### Build ####

To build you will need to install pandoc, and then run from the root directory of the repo:

```bash
$ pandoc -V slidy-url=slidy --self-contained -i -s -t slidy -o slides.html git-for-analysts.md
```
