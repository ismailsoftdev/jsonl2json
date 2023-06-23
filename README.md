# jsonltojson

A Python package for formatting JSONL files to a single JSON array.

## Installation

You can install `jsonltojson` using `pip`:
<br>

```shell
pip install jsonltojson
```

## Usage

You can use `jsonltojson` in your Python code like this:

```python
from jsonltojson import JsonlToJsonFormatter

formatter = JsonlToJsonFormatter('input.jsonl', 'output.json')
formatter.to_json()
```

This will read the input file input.jsonl and write a JSON array to the output file output.json.

# License

jsonltojson is released under the MIT `License.txt`. See LICENSE for more information.
