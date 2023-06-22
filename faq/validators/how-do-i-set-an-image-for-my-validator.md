# How do I add an image for my validator on the web wallet and explorer?

Besides a name for your validator, it is also possible to set an image for your validator to help you stand out. Thanks to Keybase.io, you're able to add an image to your validator. This image will show in the BitCanna wallet and explorer.

* First, if you do not already have an account on Keybase.io, create one.&#x20;  Once your account is set up; go to your account overview and set the image you want to use for your validator.&#x20;
* Create a PGP-key (Pretty Good Privacy).  &#x20;We will use the 64-bit key (consisting of a combination of 16 letters and numbers).&#x20;
* Send the transaction to bind the PGP-key to your validator below.&#x20;

`bcnad tx staking edit-validator --identity “[PGP-key]” --from [wallet name] --chain-id bitcanna-testnet-[number]   --gas auto   --gas-adjustment 1.5   --gas-prices 0.01ubcna`

\[PGP-key] = The key you created on Keybase.io&#x20;\
\[wallet name] = Your own wallet name

Once successful, the image of your validator will be updated. This can take up to 1 hour.&#x20;