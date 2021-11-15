# pyproject-template

A template for my Python projects

# Tests

The pytest documentation discusses two alternatives for test layouts. The test layout strategy chosen for this repository is ["Tests outside application code"](https://docs.pytest.org/en/6.2.x/goodpractices.html#tests-outside-application-code), without the presence of `__init__.py` files. This is because you can avoid using test files with the same name as application files by using test files with the same name as application files, suffixed with "_test".
