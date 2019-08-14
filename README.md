About xraylib
=============

Home: https://github.com/tschoonj/xraylib/wiki

Package license: BSD 3-Clause

Feedstock license: BSD 3-Clause

Summary: A library for X-ray matter interaction cross sections for X-ray fluorescence applications



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=37&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/xraylib-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=37&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/xraylib-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=37&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/xraylib-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=37&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/xraylib-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-xraylib-green.svg)](https://anaconda.org/nsls2forge/xraylib) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/xraylib.svg)](https://anaconda.org/nsls2forge/xraylib) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/xraylib.svg)](https://anaconda.org/nsls2forge/xraylib) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/xraylib.svg)](https://anaconda.org/nsls2forge/xraylib) |

Installing xraylib
==================

Installing `xraylib` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `xraylib` can be installed with:

```
conda install xraylib
```

It is possible to list all of the versions of `xraylib` available on your platform with:

```
conda search xraylib --channel nsls2forge
```




Updating xraylib-feedstock
==========================

If you would like to improve the xraylib recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/xraylib-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@CJ-Wright](https://github.com/CJ-Wright/)
* [@ericdill](https://github.com/ericdill/)
* [@licode](https://github.com/licode/)
* [@tacaswell](https://github.com/tacaswell/)
* [@tschoonj](https://github.com/tschoonj/)

