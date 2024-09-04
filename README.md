# CoDEC <img src="man/figures/logo.svg" align="right" height="200" />

<!-- badges: start -->

[![R-CMD-check](https://github.com/geomarker-io/codec/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/geomarker-io/codec/actions/workflows/R-CMD-check.yaml)
[![Lifecycle: stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
[![latest github release for parcel dpkg](https://img.shields.io/github/v/release/geomarker-io/codec?sort=date&filter=parcel-*&display_name=tag&label=%5B%E2%98%B0%5D&labelColor=%238CB4C3&color=%23396175)](https://github.com/geomarker-io/codec/releases?q=parcel&expanded=false)
<!-- badges: end -->

The goal of the R package {codec} is to support [CoDEC](https://geomarker.io/codec) data
infrastructure through

- defining the CoDEC data specifications
- creation and hosting of an interactive data catalog and explorer
- providing developer tools to add new CoDEC data resources
- providing an R-based interface for retreiving CoDEC data stored online

### Installation

You can install the development version of codec from
[GitHub](https://github.com/) with:

    # install.packages("devtools")
    devtools::install_github("geomarker-io/codec")

### Usage

See https://geomarker.io/codec/reference/index.html for reference pages on included functions.

### Developing

Use `just` to login to aws using sso and to make and release a CoDEC data resource to `s3://geomarker-io/codec_data/`
