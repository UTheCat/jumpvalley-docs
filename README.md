# Jumpvalley Documentation
This is the repository hosting the documentation for Jumpvalley (mainly, its core API). The documentation website was built using [Doxygen](https://www.doxygen.nl/).

The documentation can be found [here](https://uthecat.github.io/jumpvalley-docs/index.html).

## Building the documentation site with Doxygen

`doxygen_config.txt` in this repository's root is the Doxygen configuration used to build Jumpvalley's documentation site. Here's some characteristics about this file:

- The built documentation will go in the `docs` folder in this repository's root.
- The configuration assumes that you have both this repository and the primary Jumpvalley repository (the one with Jumpvalley's code) cloned locally and in the same directory.
    - Make sure your locally-cloned copy of the primary Jumpvalley repository as stated above is named `jumpvalley`.
