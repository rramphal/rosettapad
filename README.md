# RosettaPad

## Description

Especially with complex scripts, it can be hard to see
how the complex rendering of glyphs might be incorrect.
This tool, inspired by
[BabelPad](https://babelstone.co.uk/Software/BabelPad.html)
allows the user to enter in text and the tool will split
the text into individual characters and then generate a
table with a rollup of the Unicode information and
frequency for each character. You can also change the
CSS `font-family` for the output if you wish to use a
font installed locally on your system.

## Local Development

```shell
python3 -m http.server 8000

open http://localhost:8000
```

## Unicode Version

This tool uses Unicode v14.0.0 at present.
If a new version is released, the
[Unicode names](https://github.com/rramphal/unicode-character-code-names)
will need to be regenerated and the link in the footer
will need to be updated.
