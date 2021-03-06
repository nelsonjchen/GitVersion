![Icon][icon]

#GitVersion
Versioning when using git, solved. GitVersion looks at your git history and
works out the [semantic version][semver] of the commit being built.

[![Gitter][gitter-badge]][gitter]
[![Build status][appveyor-badge]][appveyor]
[![Build Status][travis-badge]][travis]
<!-- [![Build Status][azure-pipeline-badge]][azure-pipeline] -->

|                                       |                Stable                     |                 Pre-release               |
| ------------------------------------: | :---------------------------------------: | :---------------------------------------: |
|                              **Docs** |     [![Docs][docs-badge]][docs]           |    [![Docs][docs-pre-badge]][docs-pre]    |
|                    **GitHub Release** | [![GitHub release][gh-rel-badge]][gh-rel] |                      -                    |
|               **GitVersion.Portable** | [![Chocolatey][choco-badge]][choco]       |   [![Chocolatey][choco-pre-badge]][choco] |
|                    **GitVersionCore** |     [![NuGet][gvc-badge]][gvc]            |       [![NuGet][gvc-pre-badge]][gvc]      |
|                    **GitVersionTask** |     [![NuGet][gvt-badge]][gvt]            |       [![NuGet][gvt-pre-badge]][gvt]      |
|            **GitVersion.CommandLine** |     [![NuGet][gvcl-badge]][gvcl]          |       [![NuGet][gvcl-pre-badge]][gvcl]    |
| **GitVersion.CommandLine.DotNetCore** |     [![NuGet][gvcd-badge]][gvcd]          |       [![NuGet][gvcd-pre-badge]][gvcd]    |
|                               **Gem** |       [![Gem][gem-badge]][gem]            |                      -                    |
|                          **Homebrew** |   [![homebrew][brew-badge]][brew]         |                      -                    |
|                 **Docker DotnetCore** |   [Dotnetcore][dockerhub-dotnetcore]      |                      -                    |
|                     **Docker FullFX** |   [FullFX][dockerhub-fullfx]              |                      -                    |


## Compatibility
GitVersion works on Mac, Linux with Mono and Windows.

Tip: If you get `System.TypeInitializationException: The type initializer for
'LibGit2Sharp.Core.NativeMethods' threw an exception. --->
System.DllNotFoundException: lib/linux/x86_64/libgit2-baa87df.so`

You likely need to install `libcurl3`. Run `sudo apt-get install libcurl3`

## Quick Links
 - [Documentation][docs]
 - [Contributing][contribute]
 - [Why GitVersion][why]
 - [Usage][usage]
 - [How it works][how]
 - [FAQ][faq]
 - [Who is using GitVersion][who]

## GitVersion in action!
![README][gv-in-action]

You are seeing:

 - Pull requests being built as pre-release builds
 - A branch called `release-1.0.0` producing beta v1 packages

## Icon
<a href="http://thenounproject.com/noun/tree/#icon-No13389"
target="_blank">Tree</a> designed by <a
href="http://thenounproject.com/david.chapman" target="_blank">David Chapman</a>
from The Noun Project

[icon]:                 https://raw.github.com/GitTools/GitVersion/master/docs/img/package_icon.png
[semver]:               http://semver.org
[gitter]:               https://gitter.im/GitTools/GitVersion?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[gitter-badge]:         https://badges.gitter.im/Join+Chat.svg
[appveyor]:             https://ci.appveyor.com/project/GitTools/gitversion/branch/master
[appveyor-badge]:       https://ci.appveyor.com/api/projects/status/sxje0wht0cscmn7w/branch/master?svg=true
<!-- [azure-pipeline]:       https://dev.azure.com/arturcic/OSS/_build/latest?definitionId=2 -->
<!-- [azure-pipeline-badge]: https://dev.azure.com/arturcic/OSS/_apis/build/status/GitVersion -->
[travis]:               https://travis-ci.org/GitTools/GitVersion
[travis-badge]:         https://travis-ci.org/GitTools/GitVersion.svg?branch=master
[docs]:                 http://gitversion.readthedocs.org/en/stable/
[docs-badge]:           https://readthedocs.org/projects/gitversion/badge/?version=stable
[docs-pre]:             http://gitversion.readthedocs.org/en/latest/
[docs-pre-badge]:       https://readthedocs.org/projects/gitversion/badge/?version=latest
[gh-rel]:               https://github.com/GitTools/GitVersion/releases/latest
[gh-rel-badge]:         https://img.shields.io/github/release/gittools/gitversion.svg
[choco]:                https://chocolatey.org/packages/GitVersion.Portable
[choco-badge]:          https://img.shields.io/chocolatey/v/gitversion.portable.svg
[choco-pre-badge]:      https://img.shields.io/chocolatey/vpre/gitversion.portable.svg
[gvc]:                  https://www.nuget.org/packages/GitVersionCore
[gvc-badge]:            https://img.shields.io/nuget/v/GitVersionCore.svg
[gvc-pre-badge]:        https://img.shields.io/nuget/vpre/GitVersionCore.svg
[gvt]:                  https://www.nuget.org/packages/GitVersionTask
[gvt-badge]:            https://img.shields.io/nuget/v/GitVersionTask.svg
[gvt-pre-badge]:        https://img.shields.io/nuget/vpre/GitVersionTask.svg
[gvcl]:                 https://www.nuget.org/packages/GitVersion.CommandLine
[gvcl-badge]:           https://img.shields.io/nuget/v/GitVersion.CommandLine.svg
[gvcl-pre-badge]:       https://img.shields.io/nuget/vpre/GitVersion.CommandLine.svg
[gvcd]:                 https://www.nuget.org/packages/GitVersion.CommandLine.DotNetCore
[gvcd-badge]:           https://img.shields.io/nuget/v/GitVersion.CommandLine.DotNetCore.svg
[gvcd-pre-badge]:       https://img.shields.io/nuget/vpre/GitVersion.CommandLine.DotNetCore.svg
[gem-badge]:            https://img.shields.io/gem/v/gitversion.svg
[gem]:                  https://rubygems.org/gems/gitversion
[brew]:                 http://brew.sh/
[brew-badge]:           https://img.shields.io/homebrew/v/gitversion.svg
[contribute]:           https://github.com/GitTools/GitVersion/blob/master/CONTRIBUTING.md
[why]:                  http://gitversion.readthedocs.org/en/latest/why
[usage]:                http://gitversion.readthedocs.org/en/latest/usage/usage/
[how]:                  http://gitversion.readthedocs.org/en/latest/more-info/how-it-works/
[faq]:                  http://gitversion.readthedocs.org/en/latest/faq/
[who]:                  http://gitversion.readthedocs.org/en/latest/who/
[gv-in-action]:         https://raw.github.com/GitTools/GitVersion/master/docs/img/README.png
[dockerhub-fullfx]:     https://hub.docker.com/r/gittools/gitversion-fullfx/
[dockerhub-dotnetcore]: https://hub.docker.com/r/gittools/gitversion-dotnetcore/
