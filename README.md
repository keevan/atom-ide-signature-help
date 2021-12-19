# atom-ide-signature-help

[![Build Status](https://badgen.net/travis/atom-ide-community/atom-ide-signature-help/master)](https://travis-ci.org/atom-ide-community/atom-ide-signature-help)

__Note: Custom fork which improves current param highglighting but removes the syntax coloring otherwise used__
![image](https://user-images.githubusercontent.com/9924643/146671319-6bb19769-45a7-4f3b-8478-55ea31774035.png)

Which can then be styled as such in your application's stylesheet.
```
.signature-snippet code strong {
    color: #c6b6fe;
}
```

A replacement of the Signature Help functionality from the original Atom-IDE / Nuclide package developed by Facebook.

## Getting Started

1. Install `atom-ide-signature-help` in Atom.

2. Install an IDE language package that you would like to use:

- TypeScript & JavaScript [ide-typescript](https://atom.io/packages/ide-typescript)
- Python [ide-python](https://atom.io/packages/ide-python)
- Rust [ide-rust](hhttps://atom.io/packages/ide-rust)

You can also search for [packages](https://atom.io/packages/search?q=IDE) in Atom.

3. Install `busy-signal` package in Atom, which is used for signaling background tasks.

![screenshot](https://user-images.githubusercontent.com/16418197/106399337-a3164500-63dd-11eb-8241-d859b61e2d90.png)

## Contributing

Please see the [contributing guidelines](CONTRIBUTING.md).
