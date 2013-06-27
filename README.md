# minify-json.py

Minifies JSON strings.

    % minify-json.py [input] [output]

Where `input` is:
* A JSON filepath
* A directory

And `output` is:
* Optional
* A filepath
* A directory

Note: When `input` is a directory, JSON files will be minified recursively within the specified path.
Note: If `output` is unspecified, minified JSON will print to `stdout`.

