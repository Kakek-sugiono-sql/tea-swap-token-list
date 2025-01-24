# Adding a Token to TeaSwap Token List
---

Create a pull request with your new or updated token to tea-token-list.json.

The JSON Schema conforms to Uniswap V2's token list schema https://uniswap.org/tokenlist.schema.json

_Try and run your JSON file through https://jsonformatter.curiousconcept.com/# to ensure nothing broke in your changes._


TLDR: Fork this repo, add a json record that fits this to the tokens array in tea-token-list.json, and make a PR.

```js
{
  "chainId": 93384,
  "address": string /^0x[a-fA-F0-9]{40}$/,
  "name": string /^[ \S+]+$/,
  "symbol": string /^\S+$/,
  "logoURI" string,
  "decimals": integer
}
```
