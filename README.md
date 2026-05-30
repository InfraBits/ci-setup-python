# Setup Python environment

Setup a basic Python environment.

## Example Usage

```
  execute-tests:
    runs-on: ubuntu-latest
    steps:
      - uses: infrabits/ci-setup-python@main
        with:
          install_dependencies: false
          install_tox: true
```
