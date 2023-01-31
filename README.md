Spine Toolbox development bundle
================================

This Python meta-package can be used to install the latest development version 
of [Spine Toolbox](https://github.com/spine-tools/Spine-Toolbox)
including its dependencies.

Usage
-----

Install [pipx](https://pypa.github.io/pipx/) (pipx allows to create an isolated 
environment to avoid package conflicts)

    $ python -m pip install --user pipx
    $ python -m pipx ensurepath
        
Install the latest Spine Toolbox development version using

    $ python -m pipx install git+https://github.com/spine-tools/spinetoolbox-dev

Launch Spine Toolbox with

    $ spinetoolbox

The executable can be found under `~/.local/bin` (`%USERPROFILE%\.local\bin` on Windows), and a direct shortcut can also be created for it.

To upgrade to the latest, use

    $ python -m pipx upgrade spinetoolbox-dev
