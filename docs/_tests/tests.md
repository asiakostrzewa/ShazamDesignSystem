---
layout: default
title: tests
nav_order: 5
---

# tests
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Color schemes

Just the Docs supports two color schemes: light (default), and dark.


# Define Jekyll collections
collections:
  # Define a collection named "tests", its documents reside in the "_tests" directory
  tests:
    permalink: "/:collection/:path/"
    output: true

just_the_docs:
  # Define which collections are used in just-the-docs
  collections:
    # Reference the "tests" collection
    tests:
      # Give the collection a name
      name: Tests
      # Exclude the collection from the navigation
      # Supports true or false (default)
      # nav_exclude: true
      # Fold the collection in the navigation
      # Supports true or false (default)
      # nav_fold: true  # note: this option is new in v0.4
      # Exclude the collection from the search
      # Supports true or false (default)
      # search_exclude: true