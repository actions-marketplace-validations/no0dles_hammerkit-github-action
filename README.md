# Hammerkit - Github Action

## Usage
```
name: Some action
on: [push]
jobs:
  some-job:
    runs-on: ubuntu-20.04
    steps:
      - name: Checkout
        uses: actions/checkout@v2
      - uses: no0dles/hammerkit-github-action@v1
      - run: hammerkit --help
```
