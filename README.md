About noise-feedstock
=====================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/noise-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/caseman/noise

Package license: MIT

Summary: Perlin noise for Python

Development: https://github.com/caseman/noise

Perlin noise is ubiquitous in modern CGI. Used for procedural texturing,
animation, and enhancing realism, Perlin noise has been called the "salt" of
procedural content. Perlin noise is a type of gradient noise, smoothly
interpolating across a pseudo-random matrix of values.

The noise library includes native-code implementations of Perlin "improved"
noise and Perlin simplex noise. It also includes a fast implementation of
Perlin noise in GLSL, for use in OpenGL shaders. The shader code and many of
the included examples require Pyglet (http://www.pyglet.org), the native-code
noise functions themselves do not, however.

The Perlin improved noise functions can also generate fBm (fractal Brownian
motion) noise by combining multiple octaves of Perlin noise. Shader functions
for convenient generation of turbulent noise are also included.

- 1.2.2 AppVeyor support for Windows builds (Thanks to Federico Tomassetti)

- 1.2.1 Fixes MSVC compatibility (Thanks to Christoph Gohlke)

- 1.2.0 adds 4D simplex noise, tiling for 2D simplex noise, 
  and parameterized lacunarity

See CHANGES.txt for more details

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.9.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.9.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_python3.9.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_python3.9.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_python3.9.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_python3.9.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.9.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.9.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.9.____73_pypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.9.____73_pypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=691&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/noise-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-noise-green.svg)](https://anaconda.org/conda-forge/noise) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/noise.svg)](https://anaconda.org/conda-forge/noise) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/noise.svg)](https://anaconda.org/conda-forge/noise) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/noise.svg)](https://anaconda.org/conda-forge/noise) |

Installing noise
================

Installing `noise` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `noise` can be installed with `conda`:

```
conda install noise
```

or with `mamba`:

```
mamba install noise
```

It is possible to list all of the versions of `noise` available on your platform with `conda`:

```
conda search noise --channel conda-forge
```

or with `mamba`:

```
mamba search noise --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search noise --channel conda-forge

# List packages depending on `noise`:
mamba repoquery whoneeds noise --channel conda-forge

# List dependencies of `noise`:
mamba repoquery depends noise --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [Anaconda-Cloud](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating noise-feedstock
========================

If you would like to improve the noise recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/noise-feedstock are
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

* [@johanneskoester](https://github.com/johanneskoester/)

