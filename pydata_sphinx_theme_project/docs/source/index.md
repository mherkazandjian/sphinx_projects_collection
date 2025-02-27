---
sd_hide_title: true
---

# PyData based markdown template project

refer to the source documentation of pydata for detailed info and examples
[main doc source code](https://github.com/pydata/pydata-sphinx-theme/tree/main/docs)
[main doc conf.py](https://github.com/pydata/pydata-sphinx-theme/blob/main/docs/conf.py)

```{note} figure out how to have the full index on the left
```

```{warning} the title at the top overlaps with the top navigation bar
```

```{note} learn how to use the todos
```

```{todo} learn how to use the todos
```

Add your content using markdown syntax.

```{toctree}
:maxdepth: 4
:caption: Other sections and pages:

introduction.md
contributing.md
documentation.md
development.md
```

Section 1
---------

This is a simple section. You can add more sections by creating new `.rst` or `.md` files.

Section 2
---------

This is another simple section. You can add more sections by creating new `.rst` or `.md` files.

```python

def hello_world():
    print("Hello World")
```

Read more about using the sphinx markdown plugin markdown in this [guide](https://myst-parser.readthedocs.io/en/latest/faq/index.html)

```{include} introduction.md
```

```{include} contributing.md
```

```{seealso}
If you are looking for a Sphinx theme that puts all of its sub-pages in the sidebar, the [Sphinx Book Theme](https://sphinx-book-theme.readthedocs.io/) has a similar look and feel, and [Furo](https://pradyunsg.me/furo/quickstart/) is another excellent choice. You can also see the [Sphinx Themes Gallery](https://sphinx-themes.org) for more ideas.
```