# ksl.sh

Download and parse car ads from ksl.com

## Usage

```
  download suburban
  parse-listings > suburbans.psv
```

## Dependencies

Uses Pup for HMTL parsing
https://github.com/ericchiang/pup

The `download` command will download search results into ./pages, parse out the
listing urls into listing-urls, and then download each listing into ./listings.
parse-listings does a very rough parsing of the results and outputs them as |
(pipe) delimited values with a header.

MIT LICENSE
