# Running Step
1. Install Aptos client [here](https://aptos.dev/tools/install-cli/automated-install)
2. Init aptos client:
```
aptos init

```
3. Fund your account
```
aptos account fund-with-faucet --account default
``` 
4. Compile contract
```
aptos move compile --named-addresses nftango=default
```
5. Run test
```
aptos move test --named-addresses nftange=default
```