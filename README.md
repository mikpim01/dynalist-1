# Dynalist
[![LICENSE](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)
[![pypi](https://img.shields.io/pypi/v/dynalist.svg?&style=flat-square&colorB=brightgreen)](https://pypi.org/project/dynalist/)
[![docs](https://readthedocs.org/projects/dynalist/badge/?version=latest&style=flat-square)](https://dynalist.readthedocs.io/en/latest/)

Unofficial Dynalist API Written in Python.

## Installing

```
pip install dynalist
```

## Documentation
Full documentation here:

https://dynalist.readthedocs.io/

### Usage Example

Below are some of the methods available in the wrapper.

For the full list and documentation visit the [docs](https://dynalist.readthedocs.io/)

```
dynalist = Dynalist('your_file_id')

dynalist.file  # file info

dynalist.doc  # document

dynalist.get_node(node_id='root')

dynalist.get_children(node_id='root')

dynalist.to_json()

```

## License
[MIT](https://opensource.org/licenses/MIT)

## Requires
* requests
