# `\citeurl` - LaTeX URL Citation Macros

A small LaTeX utility for citing URLs inline without BibTeX. See [citeurl-example.pdf](./citeurl-example.pdf) for examples.

It provides:
- A `\citeurl{}` command that inserts a numbered, clickable domain in the text.
- Automatic collection of cited URLs.
- A `\showcitedurls` command to render a numbered, hyperlinked list of all cited URLs.

This is useful for lightweight documents where full bibliographic management is unnecessary, but traceable web references are still needed.

## Requirements

First copy `citeurl.sty` to the same dictionary as your `.tex` file. Then use:

```latex
\usepackage{citeurl}
```

## Usage

Include the code in your preamble, then use:

```latex
\citeurl{https://example.com/path}
```

and later:

```latex
\showcitedurls
```

## License

MIT