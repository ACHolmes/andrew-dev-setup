## Setting up NeoVim

This is how I configured my NeoVim on Ubuntu 22.04LTS. I try to have the same setup on Windows and Ubuntu for consistency, but the installation steps are obvioulsy likely to be largely distinct.

### Installing NeoVim

Installing NeoVim via apt gives such an old version of NeoVim that it isn't compatible with most packages. I install from source, namely following [these instructions](https://github.com/neovim/neovim/blob/master/BUILD.md) from the main neovim GitHub repository.

### Setting up NeoVim

I'm using a (currently minorly modified) version of typecraft's NeoVim setup. [See here](https://www.youtube.com/watch?v=zHTeCSVAFNY) for the first video in the series to set it up.

I am using LiberationMono as my NerdFont. Note that to install the NerdFont, I downloaded, used Ubuntu's Font Manager to install, and `fc-cache -fv` to get it to actually appear as an option for my terminal font. Credit [here](https://gist.github.com/matthewjberger/7dd7e079f282f8138a9dc3b045ebefa0) for that.
