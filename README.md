This repository is built from an mdbook which is an open source command line tool to create books with Markdown.

The documentation for mdbooks can be found here: https://rust-lang.github.io/mdBook/index.html

In order to clone this repository and compile the book locally,  you will need to have Rust installed as well as Cargo. 

To make it easier to modify this book, you can clone it locally, make a feature branch and update the .md document files in the `src` folder.
1. The SUMMARY.md file is essentially the 'Table of Contents' for the book, and any new file that you want to add needs to be first added to the SUMMARY.md file.  Upon saving, mdbook will automatically create a new .md file within the  `src` folder structure.
2. There is a GitHub action that will build a new version of the live GitHub pages site any time a PR request is merged into the `main` branch
