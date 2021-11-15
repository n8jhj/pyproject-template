# pyproject-template

A template for my Python projects

# Testing

## pytest

The pytest documentation discusses two alternatives for test layouts. The test layout strategy chosen for this repository is ["Tests outside application code"](https://docs.pytest.org/en/6.2.x/goodpractices.html#tests-outside-application-code), without the presence of `__init__.py` files. This is because you can avoid using test files with the same name as application files by using test files with the same name as application files, suffixed with "_test".

## pytest-cov

As demonstrated in [this example](https://github.com/ryanluker/vscode-coverage-gutters/tree/94abefc02fe0df1505ca6d5a33e65bc2b949a507/example/python), use:
`poetry run pytest --cov myapp --cov-report xml:cov.xml`

## Coverage Gutters

The Coverage Gutters VSCode extension is the tool of choice for displaying coverage within the editor.

### Keyboard shortcuts
* `Ctrl+Shift+8` to turn on coverage watch
* `Ctrl+Shift+9` to turn it off

### VSCode settings
`"coverage-gutters.showLineCoverage": false,`
