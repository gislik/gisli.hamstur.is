% Bitcoin
% Gísli Kristjánsson
% 2014-06-19

# Intro

## What is bitcoin?

Bitcoin is a client/server platform, defined by a protocol, which implements a secure, distributed ledger.

## Why does Bitcoin have value?

Its value is derived from its scarcity and utility.

# Terminology

## Capital B or not?

- Bitcoin - protocol, software, and community

- bitcoin units of the currency

- also BTC

## Crypto

Techniques for secure communication in the presence of third parties

## Key pairs

- Private key is computed

- Public key is derived from the private key

- Form a crypto key pair

## Addresses

- A (more) readable representation of the public key

- Identifier of 27-34 alphanumeric characters

- Represents a possible destination for a Bitcoin payment

- Can be generated at no cost 

## Transactions

<img src="Transaction.png" style="float: left">

<div style="float: right">
- Input

- Output

- Broadcast to the network <br>
  and collected into blocks
</div>

## Blocks

A collection of transactions

## Blockchain
<div style="float: left">
- Ordered collection of blocks 

- A block points to the previous block <br>
  creating a chain of blocks
</div>

<img src="Blockchain.png" style="float: right">

## Peers

Miner, nodes and wallets

## Miners

### a.k.a. weavers

Try to order blocks in the blockchain by solving math puzzles and are rewarded with new BTC

## Nodes

Verify blockchain and communicate with peers

## Wallets

- File that contains a collection of private keys

- Often refers to the software managing that file

# Comparision

## Early Internet 1/3

* It's for nerds. "Fine, you nerds can do what you want but normal people are never going to use this thing."
* It's completely decentralized, which means you can't trust it. No business is ever going to do anything on it because businesses won't work on an untrusted environment. There won't ever be any e-commerce.
* There will never be any internet payments. No one will put their credit card on the internet.
* It's an open-source kind of thing so there will be no Internet companies.

## Early Internet 2/3

* It's got all these technical deficiencies. It's slow. It's unreliable. It doesn't work right. When you do a search, sometimes you get an answer back and sometimes you don't. Sometimes when you dial in you get a busy signal.
* What happen if your ISP goes out of business? Then you can't get back online.
* Once you get on the internet, even assuming you get on the internet, there's nothing to do. There's no content. Time magazine isn't online, the New York Times isn't online. It's just a bunch of nerd stuff.

## Early Internet 3/3

Basically every single criticism of the Internet ended up getting solved. Every single supposed fatal flaw got eliminated.

## HTTP

<center>
<table width="100%">
<tr>
  <th>Protocol</th>
  <td>HTTP</td>
  <td>Bitcoin</td>
</tr>

<tr>
  <th>Server</th>
  <td>Web server</td>
  <td>Node</td>
</tr>

<tr>
  <th>Client</th>
  <td>Browser</td>
  <td>Wallet</td>
</tr>

<tr>
  <th>Prog.lang.</th>
  <td>CGI</td>
  <td>Script</td>
</tr>

<tr>
  <th>Content</th>
  <td>HTML</td>
  <td>BTC</td>
</tr>

<tr>
  <th>Value</th>
  <td>Information</td>
  <td>Money</td>
</tr>

</table>
</center>


# Details

## Security

The ledger is secured by having the nodes agree on the information stored in the blockchain.

## Consencus

- Agreement among the nodes is achieved by having the miners vote.

- The number of total votes is based on computing power.

## Anonymity

- Balance is simply associated with an address and its public-private key pair

## Mining

- Coins are slowly mined into existence

- Search for a solution to a very difficult math problem whose difficulty is precisely known

- Difficulty is automatically adjusted

- Block reward

- 13 million bitcoins (July 2014)

- No more than 21 million bitcoins will ever exist

- Happens in 2140

## Trading

- BTC/USD $600

- Market cap 7-8 billion USD

- 24 hour trading volume 8-9 million USD

- Mining

- Exchanges

- Face to face

## Volatility

## Economics

While the number of bitcoins in existence will never exceed 21 million, the money supply of bitcoins can exceed 21 million due to Fractional-reserve Banking.

## Deflation

- Keynesian economists argue that deflation is bad

- The Austrian school of thought counters this criticism

## 51% attack

![Mining pool distribution](pools.png)

## Blockchain fork

- Created from time to time when two blocks are created just a few seconds apart

- More serious forks have occurred after fixing bugs that required backward-incompatible changes

# Possibilities

## Online payments for the rest of the world

## BIPS

Bitcoin Improvement Proposals

- Multi-Sig Transactions

- M-of-N Standard Transactions

- Pay To Script Hash

- Hierachical Deterministic Wallets (HD)

- Payment Protocol

## Crowd funding

### a.k.a. insurance contracts

Individuals pledge money to a project that is taken from them only if enough pledges are received to meet the target.

- Kickstarter

- Web page translation

# Smart property

- Car keys

- Key cards

## Micro payments

- Listening to Internet radio paid by the second
- Viewing web pages with a small tip for each ad not shown
- Buying bandwidth from a WiFi hotspot by the kilobyte

## Multi-signature accounts

Certain number of a defined group of persons agree to sign the transaction

## Dispute mediation

A 3-party can approve or reject a transaction in case of disagreement between the other parties without having control on their money

## Oracles


## Financial instruments

- Trustless collaterized lending

- Bonds

- Funds with policies

- Exchanges (Ripple)
