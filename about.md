---
layout: single
title: About
permalink: /about/
toc: true
---

*Huira* is a library for space rendering, LiDAR simulation, and solar radiation pressure modeling. It is written in C++, with Python bindings, and is released under the MIT license.

## Background

Huira is a complete rewrite providing similar functionality to the [vira](https://github.com/nasa/vira) project, originally developed by the same author at NASA's Goddard Space Flight Center. While inspired by vira, Huira is built from scratch with new code.

Vira is also available on a [personal fork by the original author](https://github.com/crgnam/vira), but it is no longer maintained, and Huira is recommended in its place.

## The Huira sites

- **[huira.space]({{ '/' | relative_url }})**: this site.
- **[Quick Start]({{ site.quickstart_url }})**: examples that walk through Huira one feature at a time, in Python and C++.
- **[API Docs]({{ site.docs_url }}/)**: the C++ and Python API reference, build instructions, and the design notes. Built from the library's own source.
- **[Validation]({{ site.validation_url }}/)**: Huira's renders compared against real flight imagery.
- **[Media]({{ site.media_url }}/)**: the data and images the other sites and the examples use. See below.

## Media and data

[media.huira.space]({{ site.media_url }}/) holds the files that are too large to keep in git:

- **The data the examples use**: 3D models such as NASA's Gateway, textures of the Earth, and the Tycho-2 star catalog in Huira's format. Each example lists the files it needs, with a `curl` command to download each one.
- **Past versions** of prebuilt files.
- **Alternative datasets** to the ones the examples use.
- **The images** on this site, in the documentation, and in the example READMEs.

Keeping these out of the repositories keeps them small to clone, and gives every file a permanent address to download from in your own scripts.

The data comes from NASA, NAIF, ESA and CDS, and Solar System Scope, each under its own terms, and Huira's MIT license does not cover it. In particular, the Tycho-2 star catalog is licensed for **non-commercial use only**. See [Data Sources and Licenses]({{ site.docs_url }}/getting_started/data.html) for each dataset's license and how to credit it.

## Citing Huira

If you use Huira in published work, please cite it. On [GitHub]({{ site.repo_url }}), select **Cite this repository** in the sidebar for APA and BibTeX, or use:

```bibtex
@software{gnam_huira,
  author    = {Gnam, Christopher},
  title     = {Huira},
  year      = {2026},
  doi       = {10.5281/zenodo.23333475},
  url       = {https://github.com/huira-render/huira}
}
```

Please also note which version of Huira you used.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md]({{ site.repo_url }}/blob/main/CONTRIBUTING.md) before submitting a pull request. To ask for a feature, open a [feature request]({{ site.repo_url }}/issues/new?template=feature_request.md).
