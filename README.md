[![CIF syntax check](https://github.com/COMCIFS/cif_core/actions/workflows/main.yml/badge.svg)](https://github.com/COMCIFS/cif_core/actions)

# Core CIF dictionary

This repository is for review and development of the IUCr core CIF
(coreCIF) dictionary managed by COMCIFS. The coreCIF dictionary defines
a set of data items designed to cover the requirements of archiving and
exchanging raw and processed data and derived structural results for
single-crystal small-molecule and inorganic crystal studies.

Dictionary definitions are described using DDLm attributes, which
are themselves described in the [DDLm reference dictionary](https://github.com/COMCIFS/DDLm).

## Warning

[This dictionary](cif_core.dic) is the latest **draft** version. Definitions are subject to change and software
should be careful not to hard-code information. The latest approved coreCIF dictionary is
available from the [IUCr CIF website](https://www.iucr.org/resources/cif/dictionaries).

## Contributing

Contributions are very welcome, both from crystallography experts and people with technical CIF knowledge. Ways of contributing include:

1. Raising an issue, including suggesting a new data name (see "Issues" tab above)
2. Creating a pull request with suggested improvements to the dictionary
3. Commenting on already existing issues
4. Reviewing pull requests

If the "GitHub way" is not familiar to you, we suggest looking at
[some closed issues](https://github.com/COMCIFS/cif_core/issues?q=is%3Aissue+is%3Aclosed)
and [some closed pull requests](https://github.com/COMCIFS/cif_core/issues?q=is%3Apr+is%3Aclosed)
to see how the process works. 
You may also find [this wiki entry](https://github.com/COMCIFS/cif_core/wiki/Getting-started-with-Github-and-Git-for-development-of-CIF-dictionaries) helpful.

## Update guidelines

In general, any changes to the semantic content of the dictionary should be presented as a pull request. Someone
other than the author of the original pull request should merge the pull request once they are satisfied that the
pull request is suitable for inclusion. This protocol is not necessary for changes to the layout of the dictionary 
that do not change the meaning of any data names.
