# How do I change validator details?

In order to change different information about your validator you can use the command below. Make sure to change the parts in brackets to fit your own information.\
\
`bcnad tx staking edit-validator --new-moniker=["myMoniker"] --website=["http://mywebsite.com/"] --identity=[00000000000] --details=["My detail"] --chain-id=bitcanna-testnet-[number] --gas-adjustment 1.5 --gas="auto" --gas-prices="0.01ubcna" --from=[walletName] --commission-rate="0.01"`
