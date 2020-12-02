---
title: "Hugo Documentation Revamp Proposal"
---

# Hugo Documentation Revamp Proposal

Most of this site has been generated using `gomplate` ([site](https://docs.gomplate.ca/)). 

Data source used to generate placeholder pages is located in `sources/docs.yaml`.

The template for the `md` pages is located in `gomplate/foo.tmpl`.

Generated placeholder pages are located in `generatedcontent/`, mounted to `content/`.

Non-generated pages are located in `content/`.

To re-generate `generatedcontent`, run `gomplate` at the root of the project.

`gomplate` config file is located at `.gomplate`.


Project uses [Learn](https://themes.gohugo.io/hugo-theme-learn/) theme.

Repo at https://github.com/pointyfar/hugo-docs-revamp-proposal