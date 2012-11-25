# Homer’s works in digital format from Wiksource.

This is a digital edition of Homer from Wikisource.

I’m not interested in forking the text, but this is the only way to get an ePub file containing  Homer’s works from Wikisource.

There is a bug in [WSexport](http://wsexport.wmflabs.org/tool/book.php) that generates invalid ePub files from [Ὀμηρος](https://el.wikisource.org/wiki/Όμηρος) and [Αριστοτέλης](https://el.wikisource.org/wiki/Αριστοτέλης). I have already reported the bug (detailed information [here](https://github.com/wsexport/tool/issues/9)) and today the main developer begun to fix it.

The ePub file doesn’t have embedded fonts, since the `pandoc` version I use at my computer doesn’t support font embedding.

## Errors in the Greek text?

If you happen to find any errors on the text, please open an issue at this project and correct the text at [Wikisource](https://el.wikisource.org/wiki/Όμηρος).
