---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# KodaDot: past, present, future.

1+ year recap of KodaDot ecosystem of 80+ contributors

---


# Who are we?

<div grid="~ cols-2 gap-2" m="t-2">


<div>

<img border="rounded" style="border-radius: 50%;" width="300" src="/vikiival.jpeg">
<br>

<h2>vikiival</h2>

- co-founder
- technical wizard
- bleeding edge implementations in KodaDot 

</div>

<div>
<img border="rounded" style="border-radius: 50%;" width="300" src="yangwao.png">

<h2>yangwao</h2>

- co-founder
- a radical veteran in crypto
- building public goods and open source
  
</div>

</div>

<br>
<br>

---

# How we got to the ecosystem (2019)?

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- SubKey in VueJS (Proof-of-concept)

- First grant from Web3Foundation

- Reimplementation of DotApps from React into VueJS

- Winning hackathons in Ethereum & Polkadot ecosystem in 2019 - 2020 together

</div>
<div>

  <img border="rounded" src="/grant.png" height="300">
</div>

</div>

---

# RMRK and first pivot (Nov 2020)

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- We were looking into the NFT ecosystem for creative leverage

- Kusama native NFTs were introduced (RMRK)

- First implementation of RMRK v0.0.1

- Our DotApps was rebranded to KodaDot

</div>
<div>
  <img border="rounded" src="/rmrk-reader.jpeg" height="300">
</div>

</div>

---

# Did we have any struggles? (hint: yes)

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- Implementation of distributed & decentralized database (Textile/ThreadDB)

- Added SubSocial for commenting

- Wonky UI -- craigslist's pit

- a lot of features, but few have worked well

- ever breaking ?????????????  constant software evolution 

</div>
<div>
  <img border="rounded" src="/rmrk-profile.jpeg">
</div>
</div>

---

# Craiglist's pit

<div grid="~ cols-2 gap-2" m="t-2">
  <div>
    <img border="rounded" src="/rmrk-create.png">
  </div>
  <div>
    <img border="rounded" src="/rmrk-detail.png">
  </div>
</div>

---

# How to win some first contributors?

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- tremendous traction with translation contributors, approx 16 languages

- changed Textile to SubQuery -> improved loading times a lot for users

- deploy previews for anyone who wants to contribute & help

- issued first bounties for translations

- first bounties for external contributors

- first $50k paid out for merged pull requests to contributors

</div>
  <div>
    <img border="rounded" src="/translation.png" height="200">
  </div>
</div>

---

# Setting up the winning mentality (Q3 2021)

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- participating in the Arweave cohort hackathon
  - among finalists with the PermaFrost project for metadata hosting

- raised the first money in the company

- cross-chain NFT strategy -- Kodadot 

- experimental NFT infrastructure -- Metaprime.network

</div>
  <div>
    <img border="rounded" src="/metaprime.png">
  </div>
</div>

---

# Speeding up the bounty process

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- standardizing program for paying out bounties to developers

- setting up a payout bot in the repository - crappy, but it worked!

- crossing 80+ contributors to KodaDot's repositories

- hitting 250+ pull requests per month 

- over 300+ stars and 200+ forks of the repository


</div>
  <div>
    <img border="rounded" src="/new-issues.png">
    <img border="rounded" src="/open-issues.png">
  </div>
</div>

<!--
- thanks to that, we are among the most popular
- open source NFT frontend, right after DotApps
- substrate repository on Polkadot right after Acala, Astar & Moonbeam 
-->

---


# Upgrading bounty process to next level

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- created code review guild to distribute and offload core team

- trusted contributors 
  - could do payout for others pull-requests
  - merge things to the `main` branch

- setting up an experimental Q&A guild to help us to test new features

</div>
  <div>
    <img border="rounded" src="/pay-other.jpg" height="300">
  </div>
</div>

---

# Cross-chain strategy of KodaDot

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- multi chain compatibility 

- RMRKv1 & RMRKv2

- Basilisk NFT marketplace

- MoonRiver & MoonBeam 

- Astar WASM & RMRK-runtime

- Acala EVM+

</div>
  <div>
    <img border="rounded" src="/cross-chain.png">
  </div>
</div>

---

# Friendly user interface for managing your NFTs

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- being your single asset interface for NFTs on Polkadot & Kusama
  - abstract technology from a user 
  - which parachain am I at, and does it matter?
    - do necessary steps on behalf of the user in the background (token swaps, XCM transfers)
  - simplification of token transfers
  - the safety of transfers
- brewing protocol compatibility between various NFTs standards called Reactive NFTs 

</div>
  <div>
    <img border="rounded" src="/new-landing.png">
  </div>
</div>

---

# rNFTs - Reactive NFTs (codename)

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- extension of existing NFT standards

- based on the transactions made on the blockchain

- we can trigger additional functionality

- what could be a trigger?
	- equips & linking NFTs 
	- XCM token transfers 
	- add collabolator to the project

- performance we are doing today is based on our experiment

- https://docs.kodadot.xyz/reactive-nfts

</div>
  <div>
    <img border="rounded" width="500" src="/reactive-spiral.gif">
  </div>
</div>

---

# We are heads down trying new things

<div grid="~ cols-2 gap-2" m="t-2">
<div>


<h3>and you can do too with us</h3>

- ??? high-speed multi-chain search (wink SubSquid)

- abstracting NFTs from user experience

- generative art minting

- zkPrompts marketplace

- on-chain art without the need for off-chain code

- Graph NFTs 


</div>
  <div>
    <img border="rounded" src="/search.png">
  </div>
</div>

---


# Your contribution matters

<div grid="~ cols-2 gap-2" m="t-2">
<div>

 
<h3>We are looking forward for more collaborators on</h3>

- music NFTs

- GLSL/shaders

- on-chain art grifters

- helping to shape our API/SDK for games

</div>
  <div>
    <img border="rounded" src="/anime-music.gif">
  </div>
</div>

---

# SubWork -- your best web3 retreat in the mountains

<div grid="~ cols-2 gap-2" m="t-2">
<div>


- physical space outside of the city to laser focus on your project

- based in Bled, Slovenia, in the footstep of the Julian Alps

- rated among top10 beautiful places in Europe

- up & running

- we've already had 20+ visitors over the summer of '22

- opening ceremony soon

- go to https://subwork.xyz for more

- https://twitter.com/subworkBled

</div>
  <div>
    <img border="rounded" src="/subwork.jpeg">
  </div>
</div>

---

# Thanks for having us

<h3>and thank you for your conribution</h3>
<br>

- You can find us  
  - https://dsc.gg/kodadot
  - https://twitter.com/kodadot
  - https://twitter.com/vikiival
  - https://twitter.com/yangwao
---
