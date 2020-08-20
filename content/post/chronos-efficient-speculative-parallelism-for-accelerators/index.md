---
title: "Chronos: Efficient Speculative Parallelism for Accelerators"
subtitle: ""
date: 2020-08-20T17:26:50.654Z
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
![]()

<!--StartFragment-->

**Maleen Abeydeera, Daniel Sanchez** 

**ASPLOS 2020**

We present Chronos, a framework to build accelerators for applications with speculative parallelism. These applications consist of atomic tasks, sometimes with order constraints, and need speculative execution to extract parallelism. Prior work extended conventional multicores to support speculative parallelism, but these prior architectures are a poor match for accelerators because they rely on cache coherence and add non-trivial hardware to detect conflicts among tasks. Chronos instead relies on a novel execution model, Spatially Located Ordered Tasks (SLOT), that uses order as the only synchronization mechanism and limits task accesses to a single read-write object. This simplification avoids the need for cache coherence and makes speculative execution cheap and distributed. Chronos abstracts the complexities of speculative parallelism, making accelerator design easy. We develop an FPGA implementation of Chronos and use it to build accelerators for four challenging applications. When run on commodity AWS FPGA instances, these accelerators outperform state-of-the-art software versions running on a higher-priced multicore instance by 3.5× to 15.3×.

<!--EndFragment-->