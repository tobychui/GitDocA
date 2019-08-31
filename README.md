# GitDocA
A Simple Github docs/ rendering script using Markdown

## Demo
https://tobychui.github.io/GitDocA/

## Installation
Download the whole repo as zip and change out the documentations in the docs/lang/* folders.

## Documentation Format
The documents are basically markdown with the first line a JSON array stating the meta-data of the current document. In most case, it is an array containing only the document title. For example:

```
["Hello World!"]
# This is the markdown title
More content goes here and more lines
can be added afterward.
```

