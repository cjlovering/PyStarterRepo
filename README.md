# README

## Why?

Using this setup will format your code at each commit, and help maintain a readable and uniform format with little additional effort.

## How?

```bash

pip install -r requirements.txt
pre-commit install
```

Now, proceed to use git as normal: each commit requires code-compliant code. If the pre-commit hooks fail, you will have to commit again.

## Resources

See the following sources for more details:

* https://ljvmiranda921.github.io/notebook/2018/06/21/precommits-using-black-and-flake8/
* https://github.com/python/black
