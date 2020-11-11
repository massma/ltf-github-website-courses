Materials for the "Git for course deployment and websites" workshop
===================================================================

Workshop website
----------------

is at: <https://massma.github.io/ltf-github-website-courses/>

Directory structure
-------------------

-   **lectures** - contains two lectures for editing.
-   **sample-websites** - contains a couple of websites that could be
    useful to collaborate on in the future.

Contribution guidelines
-----------------------

Please only modify Markdown files (`.md`). All other files are generated
from the Markdown files.

Useful commands for merging conflicts
------------------------------------

`git diff --name-only --diff-filter=U` : lists all filenames that have conflicts
`git diff --check` : lists all filenames that have conflicts, with line numbers

Building the website locally
----------------------------

### Software requirements

- [Pandoc](https://pandoc.org/)
- [GNU Make](https://www.gnu.org/software/make/)

### Instructions

1. Clone the repository: `git clone --recursive git@github.com:massma/ltf-github-website-courses.git`.
2. Run make: `cd ltf-github-website-courses && make`.
