---
layout: page
permalink: /software/
title: software
description: Formal software releases and research datasets with DOI.
nav: true
nav_order: 5
---

This page showcases formally published software packages and datasets with persistent identifiers (DOI), complementing the [GitHub repositories](/repositories/) page.

## Software Packages

{% bibliography -f citations -q @software* %}

## Research Datasets

{% bibliography -f citations -q @misc[note=Dataset]* %}