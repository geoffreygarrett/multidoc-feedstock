About multidoc
==============

Home: https://multidoc.readthedocs.io/

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/geoffreygarrett/multidoc-feedstock/blob/master/LICENSE.txt)

Summary: A Python library that automates C++/Pybind11/Python docstring generation
from a single source.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/geoffreygarrett/feedstock-builds/_build/latest?definitionId=1&branchName=master">
        <img src="https://dev.azure.com/geoffreygarrett/feedstock-builds/_apis/build/status/multidoc-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-multidoc-green.svg)](https://anaconda.org/ggarrett13/multidoc) | [![Conda Downloads](https://img.shields.io/conda/dn/ggarrett13/multidoc.svg)](https://anaconda.org/ggarrett13/multidoc) | [![Conda Version](https://img.shields.io/conda/vn/ggarrett13/multidoc.svg)](https://anaconda.org/ggarrett13/multidoc) | [![Conda Platforms](https://img.shields.io/conda/pn/ggarrett13/multidoc.svg)](https://anaconda.org/ggarrett13/multidoc) |

Installing multidoc
===================

Installing `multidoc` from the `ggarrett13` channel can be achieved by adding `ggarrett13` to your channels with:

```
conda config --add channels ggarrett13
conda config --set channel_priority strict
```

Once the `ggarrett13` channel has been enabled, `multidoc` can be installed with:

```
conda install multidoc
```

It is possible to list all of the versions of `multidoc` available on your platform with:

```
conda search multidoc --channel ggarrett13
```




Updating multidoc-feedstock
===========================

If you would like to improve the multidoc recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ggarrett13` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ggarrett13` channel.
Note that all branches in the geoffreygarrett/multidoc-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@geoffreygarrett](https://github.com/geoffreygarrett/)

