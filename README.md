# common_nonpublic
This repository contains those parts of [my common cofiguration](//github.com/johslarsen/common) that should not be publicly available.
Such parts include, but are not limited to, some of my ssh keys and configuration files that contain passwords and/or other sensitive information.

The published clone of this repository is only a skeleton, but one that is a common ancestor of the actual repository, and will **never** contain anything but this description.
Its only reason for existence is to enable the usage `git clone --recursive` on the repository that has this as its submodule.
The aforementioned repository *should* reference the publicly available commit of this repository (on my computers I checkout master anyway), as to avoid errors about missing commits.
