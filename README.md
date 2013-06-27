# minify-json.py

Minifies JSON strings.

    % minify-json.py [input] [output]

Where `input` can be:
* A JSON filepath
* A directory

And `output` can be:
* A filepath
* A directory

Note: When `input` is a directory, the script will search the directory recursively for JSON files, minify each one, and write it to the specified output path.

Note: If `output` is unspecified, minified JSON will print to `stdout`.

