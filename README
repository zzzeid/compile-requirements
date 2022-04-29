Example Usage
=============

To use this workflow, add a new workflow to your repo with the below content:

```yaml
name: Sandbox

on:
  pull_request:
    branches: [requirements]

jobs:
  call-compile-requirements:
    uses: zzzeid/compile-requirements/.github/workflows/compile-requirements.yml
    with:
        os: '["ubuntu-latest", "windows-latest", "macos-latest"]'
        python: '["3.6", "3.7"]'
```
