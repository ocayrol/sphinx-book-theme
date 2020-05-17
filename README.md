# sphinx-book-theme

[![codecov](https://codecov.io/gh/executablebooks/sphinx-book-theme/branch/master/graph/badge.svg)](https://codecov.io/gh/ExecutableBookProject/sphinx-book-theme) | [![Documentation Status](https://readthedocs.org/projects/sphinx-book-theme/badge/?version=latest)](https://sphinx-book-theme.readthedocs.io/en/latest/?badge=latest)

**An interactive book theme for Sphinx**.

This is a lightweight Sphinx theme designed to mimic the look-and-feel of an
interactive book. It has the following primary features:

* **Bootstrap 4**
  for visual elements and functionality.
* **Flexible content layout** that is inspired by beautiful online books,
  such as [the Edward Tufte CSS guide](https://edwardtufte.github.io/tufte-css/)
* **Visual classes designed for Jupyter Notebooks**. Cell inputs, outputs,
  and interactive functionality are all supported.
* **Launch buttons for online interactivity**. For pages that are built with
  computational material, connect your site to an online BinderHub for interactive content.

## Get started

To get started with `sphinx-book-theme`, first install it with `pip`:

```
pip install sphinx-book-theme
```

then, activate the theme in your Sphinx configuration (`conf.py`):

```
...
html_theme = "sphinx_book_theme"
...
```

This will activate the Sphinx Book Theme for your documentation. Note that you may
need to change your `html_theme_options` configuration depending on your previous
theme. See the pages to the left for information about what you can configure with
`sphinx-book-theme`.

## Documentation

See [the Sphinx Book Theme documentation](https://sphinx-book-theme.readthedocs.io/en/latest/)
for more information.
