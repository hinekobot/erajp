[![pypi](https://img.shields.io/pypi/dm/erajp.svg)](https://pypi.python.org/pypi/erajp)
[![pypi](https://img.shields.io/pypi/v/erajp.svg)](https://pypi.python.org/pypi/erajp)
[![GitHub license](https://img.shields.io/github/license/recruit-mtl/erajp.svg)](https://github.com/recruit-mtl/erajp)
[![travis](https://img.shields.io/travis/recruit-mtl/erajp.svg)](https://travis-ci.org/recruit-mtl/erajp)
[![coveralls](https://img.shields.io/coveralls/recruit-mtl/erajp.svg)](https://coveralls.io/github/recruit-mtl/erajp)

# erajp: Convert datetime to Japanese era

## Requirements
- Python 2.7+
- Python 3.2+

## Installation

Install erajp via PyPI:
```
pip install erajp
```

## How to use

```python
>>> strjpftime()
 'H27.08.05' # now
>>> strjpftime(datetime.datetime(1989, 1, 8)) 
 'H1.01.08'
>>> strjpftime(datetime.datetime(1989, 1, 8), u"%O%E年")
 '平成元年'
```

### New available date format

 - %o : alpabet era
 - %O : Chinese charactor era
 - %E : era year
 - %e : era year(Number of digit=2)
 
## Main Project Website.

 [https://github.com/recruit-mtl/erajp](https://github.com/recruit-mtl/erajp)

## License
MIT License

## Changes
### 190517
- 新元号（令和）を追加
- Data formatに`%e`（和暦2桁表示）を追加