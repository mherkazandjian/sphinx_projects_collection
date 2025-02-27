simple project documentation
============================

Add your content using markdown syntax.

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


```{toctree}
:maxdepth: 2
:caption: Other sections and pages:

introduction.md
contributing.md
documentation.md
```