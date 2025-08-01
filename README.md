# IGLib.workspace.codedoc_resources

This repositort contains the necessary resources for generation of code documentation, namely the binaries of ***[Doxygen](https://gitlab.com/graphviz/graphviz)*** and ***[Graphviz](https://gitlab.com/graphviz/graphviz)***. Binaries distributed by this repository are used in the **[codedoc](https://github.com/ajgorhoe/IGLib.workspace.doc.codedoc)** repository used for generation of code documentation for the **[Investigative Generic Library(IGLib)](https://github.com/ajgorhoe/IGLib.modules.IGLibCore)**, but the *codedoc* repository can b easily adapted to use with any other source code repository (or a large group of repositories, as is the case with *IGLib*).

For licenses and source of the contained binaries, see the file

> *bin/0readme_bin.txt*

## Contained Binaries

This repository containd binaries under different licenses. Please refer to the license and copyright information included in the binary directories.

Source code corresponding to the included licenses can be clonet into the current directory bu running the PowerShell script

> UpdateRepo_codedoc.ps1

After running the script, source code cloned from the original repositories will appear in the `src/` directory.

## Other information

This repository is part of the Investigative Generic Library (IGLib).

See ***LICENSE.md*** for terms of use. Please note that license terms do not apply to third party software that is contained in this repository (mainly in binary form) - see above.

In order to use this repository, clone it by using the IGLib container repository located at:

> *https://github.com/ajgorhoe/iglibcontainer.git*

See the readme file of the above container repository for information about how to properly clone and use IGLib repositories.

For more information, see the documentation from IGLib base repository located at:

> *https://github.com/ajgorhoe/IGLib.workspace.base.iglib.git*


