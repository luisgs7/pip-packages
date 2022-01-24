# Pip package install action

A github action that makes it possible to install pip, and install the dependencies described in the requirements.txt file

## Example of use

```yaml
jobs:
  executar_jobs:
    runs-on: ubuntu-latest
    steps:
      - name: Install pip and packages
        uses: luisgs7/luisgs7/pip-packages@v{version}
```

## Inputs

``requirements``: Optionally add a requirements.txt file to the project
