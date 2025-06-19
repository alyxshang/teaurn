# TEAURN :teapot: :dragon:

![Teaurn CI](https://github.com/alyxshang/teaurn/actions/workflows/scoop.yml/badge.svg)

***An urn for Scoop packages for software written by me. :teapot: :dragon:***

## ABOUT :books:

This repository contains the source code for "bucket", [Scoop](https://scoop.sh)'s term for
a package repository. You can find a list of the software included here
below:

- [`mandy`](https://github.com/alyxshang/mandy)

## USAGE :gear:

To add this "bucket" to your list of buckets for your Scoop installtion,
run the following command from Powershell:

```Powershell
scoop bucket add teaurn https://github.com/alyxshang/teaurn.git
```

To install a package, run the following command from a Powershell
session. `package-name` represents any of the packages listed above.

```Powershell
scoop install package-name
```

## NOTE :scroll:

- *Teaurn :teapot: :dragon:* by *Alyx Shang :black_heart:*.
- Licensed under the [FSL v1](https://github.com/alyxshang/fair-software-license).
