# Pip package install action and python project dependencies 

A github action that makes it possible to install pip, and install the dependencies described in the requirements.txt file

## Example of use

```yaml
jobs:
  executar_jobs:
    runs-on: ubuntu-latest
    steps:
      - name: Install pip and packages
        uses: luisgs7/pip-packages@v1
```

## Inputs

``requirements``: Optionally add a requirements.txt file to the project
