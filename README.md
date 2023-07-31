# fex-assets

Stores various resources (e.g. images) for [fex.cash](https://fex.cash)

### How to Submit Token Logo
If the community wants to submit a logo for a token, please submit a PR and follow the rules below:
1. upload it into `./logo`, file name is `{token-id}.png`
2. the image size does not exceed 64KB
3. size must be square (e.g. 16 * 16)


### How to Submit BCMR Token Information
First of all, the underlying contract(covenants) of fex fully supports cashtokens, only the front-end shows no support for BCMR tokens for the time being.
If the community would like to provide compatibility information for BCMR tokens on fex, please submit a PR and follow the rules below:
1. append the bcmr token information into `./bcmr-support/bcmr.json` file, 
2. the key is token category, the value is an object with decimals and symbol