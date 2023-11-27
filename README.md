# kazhalgal

This static website of கழல்கள் created with [Hugo](https://gohugo.io/about/) static code generator.

This is simple to use static code generator is very easy to manage for none technical users also.

The content can be created using [markdown](https://www.markdownguide.org/cheat-sheet/) systax.

## Getting Started

Before you begin to edit this website you must:

1. Node JS
2. Install Hugo (extended edition, v0.112.0 or later)
3. Install Git

(Recommend to use git code spaces, it will have all the required installtion already)

# If first time follow the below step to add themes

Try adding submodule first with following command

    git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

If it fails with `fatal: 'quickstart/themes/ananke' already exists in the index` then try this below commands in order

    git rm -r themes/ananke
    git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

## How to test the code locally

    hugo server -D

## How to build the code

    hugo

Refer [Hugo](https://gohugo.io/about/) website for more details