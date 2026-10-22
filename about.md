---
layout: single
title: About
permalink: /about/
toc: true
---

*Huira* is a library for space rendering, LiDAR simulation, and solar radiation pressure modeling. It is written in C++, with Python bindings, and is released under the MIT license.

The MIT license covers Huira's code, not its name or logo.
{: .notice--info}


## Background

Huira began as [vira](https://github.com/nasa/vira), which I developed at NASA's Goddard Space Flight Center. Vira was named for *Viracocha*, the creator deity of Inca mythology, who made the Sun, the Moon and the stars.

When I left NASA, vira and its names stayed behind. Huira is a complete rewrite, built from scratch with new code, and its name keeps the connection: *Huiracocha* is another spelling of *Viracocha*. In the same way, Huira is a new "implementation" of vira.

## Media and data

[media.huira.space]({{ site.media_url }}/) holds the files that are too large to keep in git, or that several of Huira's sites and repositories share:

- **The data the examples use**: 3D models such as NASA's Gateway, textures of the Earth and planets, and the Tycho-2 star catalog in Huira's format. Each example lists the files it needs, with a `curl` command to download each one.
- **Past versions** of prebuilt files.
- **Alternative datasets** to the ones the examples use.
- **The renders** on this site, in the documentation, and in the example READMEs.

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
