---
title: "Quick Start"
layout: single
permalink: /setup/quick-start-guide/
excerpt: "Install Huira, get the examples, and render your first image."
toc: true
---

## 1. Install

**Python**, from [PyPI](https://pypi.org/project/huira/), for Python 3.9 or later:

```bash
pip install huira
```

**Python and C++**, from [conda-forge](https://anaconda.org/channels/conda-forge/packages/huira/overview):

```bash
conda install conda-forge::huira
```

**C++**, from [vcpkg](https://vcpkg.io/en/package/huira), where `[tools]` adds the `huira` command line program:

```bash
vcpkg install huira[tools]
```

Or [build Huira from source]({{ site.docs_url }}/getting_started/build_instructions/index.html) on Linux, macOS or Windows. The C++ examples are built this way.

## 2. Get the examples

Both Python and C++ example code are provided to demonstrate different use-cases of Huira.  These examples can be found either in [Huira's repository]({{ site.repo_url }}/tree/main/examples), or by visiting the [example documentation]({{ site.docs_url }}/examples/).

Make sure you're using the most recent version of Huira.  If you're using an older version (e.g., v0.9.11) make sure to check out the correct git-tag when viewing the repository.

**Warning:** Documented examples did not exist before v0.9.11.
{: .notice--warning}
