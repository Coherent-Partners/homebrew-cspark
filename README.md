# homebrew-cspark

[![CI Build][ci-img]][ci-url]

[Homebrew] formula allowing for installation of Coherent Spark CLI using homebrew tap.

Coherent Spark CLI (currently in beta) is a command-line tool that lets developers
interact with the Coherent Spark platform. It is built on top of the
[Coherent Spark Python SDK](https://pypi.org/project/cspark/) and allows
developers to perform basic operations such as authenticating to Spark, listing
available services, and executing Spark services.

## Installation

Using [Homebrew]:

```bash
brew tap Coherent-Partners/cspark
brew install cspark
cspark --help
```

Using [pipx]:
(`python >= 3.8` required):

```bash
pipx install 'cspark[cli]'
cspark --help
```

> **Note**: We recommend installing the CLI in a virtual or isolated environment
> when using `pipx`.

## More Info

In short, the CLI is designed for developers who want to interact with the platform
in a more programmatic way, without having to write code.

Refer to its [documentation][cspark-docs] to learn more.

<!-- References -->

[ci-img]: https://github.com/Coherent-Partners/homebrew-cspark/workflows/Build/badge.svg
[ci-url]: https://github.com/Coherent-Partners/homebrew-cspark/actions/workflows/build.yml

[Homebrew]: https://brew.sh
[pipx]: https://pipx.pypa.io/stable/
[cspark-docs]: https://github.com/Coherent-Partners/spark-python-sdk/tree/main/docs/cli
