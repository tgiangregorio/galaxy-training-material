---
title: The UMAP Plots errors out sometimes?
box_type: tip
layout: faq
contributors: [nomadscientist, mtekman]
---

Try a different colour palette. For upstream code reasons, the default color palette sometimes causes the tool to error out.

- Under **Plot attributes**, do
  - *"Colour map to use for continuous variables"*: `viridis`
  - *"Colors to use for plotting categorical annotation groups"*: `plasma`
