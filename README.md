# pycolors (pycoloredprompt)

Simple and lightweight cross-platform Python 16 colors terminal text package

### Index

- [Installation](https://github.com/gioggino/pycolors/blob/main/README.md#Installation)
- [Usage](https://github.com/gioggino/pycolors/blob/main/README.md#Usage)
- [Documentation](https://github.com/gioggino/pycolors/blob/main/README.md#Documentation)
- [Contributing](https://github.com/gioggino/pycolors/blob/main/README.md#Contributing)
- [License](https://github.com/gioggino/pycolors/blob/main/README.md#License)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pycolors

```bash
pip install pycoloredprompt
```

## Usage

- Import the package

```python
import pycolors
```

- Import the modules

```python
from pycolors import fore, back, style, init
```

- Use this to make it work with Windows command prompt

```python
init.init()
```

- Now let's try it!

```python
print(f"{fore.RED}{back.WHITE}{style.URL}Hello World!{style.RESET}")
```

## Documentation

Documentation is coming soon

## Contributing

Pull requests are welcome! You can do a pull request [here](https://github.com/gioggino/pycolors/pulls)

Please report any issues [here](https://github.com/gioggino/pycolors/issues)

## License

pycolors is distributed under the [MIT](https://choosealicense.com/licenses/mit/) License

project's license can be found [here](https://github.com/gioggino/pycolors/blob/main/LICENSE)
