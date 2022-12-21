[![GitHub release](https://img.shields.io/github/release/crazy-max/ghaction-dump-context.svg?style=flat-square)](https://github.com/crazy-max/ghaction-dump-context/releases/latest)
[![CI workflow](https://img.shields.io/github/actions/workflow/status/crazy-max/ghaction-dump-context/ci.yml?branch=master&label=ci&logo=github&style=flat-square)](https://github.com/crazy-max/ghaction-dump-context/actions?workflow=test)
[![Become a sponsor](https://img.shields.io/badge/sponsor-crazy--max-181717.svg?logo=github&style=flat-square)](https://github.com/sponsors/crazy-max)
[![Paypal Donate](https://img.shields.io/badge/donate-paypal-00457c.svg?logo=paypal&style=flat-square)](https://www.paypal.me/crazyws)

## About

GitHub Action [composite](https://docs.github.com/en/actions/creating-actions/creating-a-composite-run-steps-action)
to [dump context](https://docs.github.com/en/actions/reference/context-and-expression-syntax-for-github-actions#example-printing-context-information-to-the-log-file)
of your workflow.

___

* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)

## Usage

```yaml
name: dump

on:
  push:
  pull_request:

jobs:
  dump:
    runs-on: ubuntu-latest
    steps:
      -
        name: Dump context
        uses: crazy-max/ghaction-dump-context@v1
```

## Contributing

Want to contribute? Awesome! The most basic way to show your support is to star the project, or to raise issues. If
you want to open a pull request, please read the [contributing guidelines](.github/CONTRIBUTING.md).

You can also support this project by [**becoming a sponsor on GitHub**](https://github.com/sponsors/crazy-max) or by
making a [Paypal donation](https://www.paypal.me/crazyws) to ensure this journey continues indefinitely!

Thanks again for your support, it is much appreciated! :pray:

## License

MIT. See `LICENSE` for more details.
