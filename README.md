# CubesWriter

A tool that converts [Cubes](http://cubes.databrewery.org/) JSON models into usable, write-layer SQLAlchemy models.


## Installation

```
$ pip install cubeswriter
```

Note: The only addition that Cubes model configs need in order to work with `CubesWriter`, is an object mapping columns to their types.

For examples, look at the model fixture in  `tests/data/hello_world.json`

For use, refer to `tests/cubeswriter/test_parsers.py`
