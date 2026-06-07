---
title: "Building a Cal/Val Report Agent"
description: "An early R&D concept for an agentic workflow that gathers acquisitions, reference measurements, processing metadata, and validation evidence into a structured cal/val report."
pubDate: 2026-06-06
tags:
  - "Prototype"
  - "R&D"
  - "Cal/Val"
  - "Agentic AI"
  - "Reporting"
draft: false
---
Calibration and validation work is full of small but important details. Acquisition timing, reference measurements, surface conditions, atmospheric assumptions, processing versions, and uncertainty all matter.

A cal/val report agent should not hide that complexity. It should help organise it.

## The useful version

The useful version of this workflow would gather:

- satellite acquisitions over a reference site;
- timing differences between image acquisition and field measurements;
- product metadata and processing baseline information;
- quality flags and masking decisions;
- comparison plots and tabular summaries;
- a short written assessment for review.

The output should be a draft report, not an unquestioned final answer.

## Why start here

Cal/val is a good test case for agentic EO workflows because it forces the system to care about provenance. A flashy answer is not enough. The workflow needs to show where the numbers came from, what was excluded, and what still needs expert judgement.
