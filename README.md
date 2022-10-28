<h1 align="center">
  <a href="https://pypi.org/project/random-profile/">
  Random Profile Generator
  </a>
  V0.2.3
</h1>

<h4 align="center">Python Module To Generate Random Profile Data</h4>

<p align="center">
<img src="https://img.shields.io/pypi/v/random-profile.svg">
<img src="https://img.shields.io/pypi/pyversions/random-profile.svg">
<img src="https://img.shields.io/pypi/l/random-profile.svg">

</p>
<p align="center">
<img src="https://img.shields.io/pypi/dd/random-profile.svg">
<img src="https://img.shields.io/pypi/dw/random-profile.svg">
<img src="https://img.shields.io/pypi/dm/random-profile.svg">
</p>

[RandomProfile](https://pypi.org/project/random-profile/) is a powerful and simple tool to generate fake data. You can use it to mock classes, populate databases and much more. You can check the full documentation here. Check on [Pypi](https://pypi.org/project/random-profile/)

## Installation

- This is A python 3 Package.
- Install python 3.0+ or Anaconda 3.0+

```bash
pip install random-profile   # using pip
conda install random-profile # using anaconda
```

## Documentation

### As Python Module
You can use the RandomProfile as a module in your python code. You can check the full documentation here.

```python
from random_profile import RandomProfile
rp = RandomProfile(num=5)

rp.full_profile(num=10)
```

for detailed documentation check [here](https://randomprofilegenerator.readthedocs.io/)

### As Command Line Tool
You can also use the RandomProfile as a command line tool. You can check the full documentation here.

```bash
random-profile --help
Usage: random-profile [OPTIONS]
```

```bash
random-profile -n 10 -p
```

for detailed documentation check [here](https://randomprofilegenerator.readthedocs.io/)

## Upcoming Features

- Support for more languages

## Changelog

Check the [Changelog](/CHANGELOG.md) for the latest changes.

## Contributing

Check the [Contributing](/CONTRIBUTING.md) for the contribution guidelines.

## License

The project is licensed under the <a href="/LICENSE">MIT</a> license. 

## Contributors

<a href="https://github.com/codePerfectPlus/awesomeScripts/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=codePerfectPlus/randomprofilegenerator" />
</a>
