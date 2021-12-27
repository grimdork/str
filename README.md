# str
Some convenient string functions.

## What
This package contains a couple of functions to remove duplicates from string slices and optionally sort them, plus a rather over-engineered wrapper around strings.Builder.

### Primary functions
- RemoveDuplicateStrings() - Removes duplicate strings from a slice of strings, optionally sorting them.
- RemoveDuplicateStringsAndTitle() - Removes duplicate strings from a slice of strings, turns the first character to upper case and optionally sorts the slice.
- NewStringer() - Creates an expanded strings.Builder. Its Write() function accepts many datatypes, and slices can optionally have a configurable separator added between elements.

## Stringer
The main functions in Stringer are as follows:
- Write(): Writes strings, bytes, integers, floats, booleans, maps, and slices to the underlying strings.Builder.
- WriteStrings(): Writes an arbitrary number of strings to the underlying strings.Builder.
- SetCliceComma(): Sets the separator for slice elements when concatenating them into the underlying strings.Builder.
- SetEquals(): Sets the separator for map keys and values when concatenating them into the underlying strings.Builder.
