# Project Title

A CFPB specific configuration for the [Lighthouse](https://github.com/GoogleChrome/lighthouse) command line tool.

## Requirements

Node v5+ or Node v4 w/ --harmony


## Installation

First install Lighthouse

```
npm install -g lighthouse
```

Then clone this repository:

```
git clone git@github.com:cfpb/lighthouse-config.git
```


## Usage

To run the tests set, `cd` into the cloned directory and run the test with the `config-path` flag. To run the tests agains the homepage of consumerfinance.gov we would:

```
lighthouse --config-path=config.json http://consumerfinance.gov
```




----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)
