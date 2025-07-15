# Octra-Guide
Octra Guide

Wallet Generation Step

## Step 1:
````bash
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
````

## Step 2:
````bash
bun install
````
## Step 3:
````bash
bun run build
````
##  Step 4:
````bash
bun start
````


Wallet Generated, Back up private key

Go to https://faucet.octra.network/

Paste Wallet address & claim faucet

Quest1 - Send Tokens
## Step 1
````bash
pip install -r requirements.txt
````

## Step 2
````bash
cp wallet.json.example wallet.json
````

## Step 3
Paste your test wallet details
````bash
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
````
## Step 4 : Send a test transaction
Replace address with any address from explorer - https://octrascan.io/

````bash
python cli.py send --to octECeUEKyTeFMYBumubqnskCYo292LJaDi8pR7ETJB4NYz --amount 0.01
````

Quest2 - encrypt & decrypt Tokens

## Step 1
````bash
pip install -r requirements.txt
````

## Step 2
````bash
cp wallet.json.example wallet.json
````

## Step 3
open the file: wallet.json
Replace with your Pvt key & octra address u generated in previous guide

````bash
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
````

##  Step 4 : Send a test transaction

Replace address with any address from explorer - https://octrascan.io/

````bash
python cli.py send --to octECeUEKyTeFMYBumubqnskCYo292LJaDi8pR7ETJB4NYz --amount 0.01
````
Now run 4th cmd

Blue Terminal will open

type 4 for encrypton & 5 for decryption of tokens
