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



<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---


# Who we are?

<div grid="~ cols-2 gap-2" m="t-2">


<div>

<img border="rounded" style="border-radius: 50%;" width="300" src="https://pbs.twimg.com/profile_images/1490359385108930563/tWaIhzMH_400x400.jpg">
<br>

<h2>vikiival</h2>

- co-founder
- technical wizard
- bleeding edge implementations in KodaDot 

</div>

<div>
<img border="rounded" style="border-radius: 50%;" width="300" src="https://pbs.twimg.com/profile_images/1562000851174133762/3BxCwuL0_400x400.png">

<h2>yangwao</h2>

- co-founder
- radical veteran in crypto
- building public goods and open source
  
</div>

</div>

<br>
<br>

---

# How we got to the ecosystem (2019) ?

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- SubKey in VueJS (Proof-of-concept)

- First grant from Web3Foundation

- Reimplementation of DotApps from React into VueJS

- Winning hackathons in Ethereum & Polkadot ecosystem in 2019 - 2020 together

</div>
<div>

  <img border="rounded" src="https://miro.medium.com/max/1400/1*bx_emZ-Wn0IKKelK-fVaFQ.png">
</div>

</div>

---

# RMRK and first pivot (Nov 2020)

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- We were looking into NFT ecosystem for creative leverage

- Kusama native NFTs were introduced (RMRK)

- First implementation of RMRK v0.0.1

- Our DotApps was rebranded to KodaDot

</div>
<div>
  <img border="rounded" src="/rmrk-reader.jpeg">
</div>

</div>

---

# Did we have any struggles? (hint: yes)

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- Implementation of distributed & decentralized database (Textile/ThreadDB)

- Added SubSocial for commenting

- Wonky UI -- craiglist's pit

- lot of features, but few has worked well

- ever breaking 🤷‍♂️  constant software evolution 

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

- huge traction with translation contributors, approx 16 languages

- changed Textile to SubQuery -> improved loading times a lot for users

- deploy previews for anyone who wanted to contribute & help

- issued first bounties for translations

- first bounties for external contributors

- first $50k paid out for merged pull requests to contributors

</div>
	<div>
		<img border="rounded" src="/translation.png">
	</div>
</div>

---

# Setting up the winning mentality (Q3 2021)

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- participating in Arweave cohort hackhathon
	- among finalists with PermaFrost project for metadata hosting

- raised first money in company

- cross-chain NFT strategy -- Kodadot 

- experimental NFT infrastructure -- Metaprime.network

</div>
	<div>
		<img border="rounded" src="/metaprime.png">
	</div>
</div>

---

# Speeding up bounty process

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- standardizing program for paying out bounties to developers

- setting up payout bot in repository - crappy but worked!

- crossing 80+ contributors to KodaDot's repositories

- hitting 250+ pull request per month 

- over 300+ stars and 200+ forks of repository


</div>
	<div>
		<img border="rounded" src="/new-issues.png">
		<img border="rounded" src="/open-issues.png">
	</div>
</div>

<!--
- thanks to that we are among most popular
- open source NFT frontend, right after DotApps
- substrate repository on Polkadot right after Acala,Astar & Moonbeam 
-->

---


# Upgrading bounty process to next level

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- trusted contributors 
	- could do payout for others pull-requests
	- merge things to `main` branch

- created code review guild to distribute and offload core team

- setting up experimental Q&A guild to help us going through the stuff

</div>
	<div>
		<img border="rounded" src="/pay-other.jpg">
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
	- abstract technology from user 
	- which parachain I'm at and does it matter?
		- do necessary steps on behalf of user on background (token swaps, XCM transfers)
	- simplification of token transfers
	- safety of transfers
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

- make offers & royalties 
- collab
- reactive actions 
- equips & linking NFTs 
- loot and bundles
- forking & remixing
- game integrations  
- protocol compatibility 
- XCM token transfers 
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

- ✅ extremely fast multi-chain search (wink SubSquid)

- abstracting NFTs from user experience

- generative art minting

- zkPrompts marketplace

- on-chain art without need for off-chain code

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

# SubWork -- your best web3 retreat in mountains

<div grid="~ cols-2 gap-2" m="t-2">
<div>


- physical space outside from city to laser focus on your project

- based in Bled, Slovenia, on footstep of Julian Alps

- rated among top10 beautiful places in the Europe

- up & running

- we've already had 20+ visitors over summer '22

- opening ceremony soon

- go to the https://subwork.xyz for more

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

---

### KodaDot: past, present, future.
- 1 year recap of KodaDot ecosystem of 80+ contributors

#### Introduction 
Viki - co-founder, technical wizard of bleeding edge implementations in KodaDot 
Yangwao - co-founder, radical veteran in crypto and open source 

### Brief history
- how we got to the ecosystem 
- SubKey in VueJS (PoC)
- first grant from Web3Foundation
- reimplementation of DotApps from React into Vuejs
- winning hackathons in Ethereum & Polkadot ecosystem in 2019 - 2020 together

### First Pivot 
- looking into NFT ecosystem for creative leverage
- Kusama NFTs (RMRK)
- RMRKv1 first implementation

### Struggles
- implementation of distributed & decentralized database (Textile/ThreadDB)
- implemented SubSocial for commenting
- wonky UI -- craiglist's pit
- lot of features, but few has worked well
- ever breaking 🤷‍♂️  constant software evolution 

### Winning mentality
- huge traction with translation contributors, approx 16 languages
- changed Textile to SubQuery -> improved loading times a lot for users
- deploy previews for anyone who wanted to contribute & help
- bounties system for code contributors
- participating in Arweave cohort hackhathon
	- among finalists with PermaFrost project for metadata hosting
- raised first money in company
- cross-chain NFT strategy -- Kodadot 
- experimental NFT infrastructure -- Metaprime.network
- build web3 coworking space in Slovenia's mountains -- SubWork

#### Bounties program
- issued first bounties for translations
- first bounties for external contributors


- first $50k paid out for merged pull requests to contributors

---
### Speeding up bounty process
- standardizing program for paying out bounties to developers
- setting up payout bot in repository - crappy but worked!
- crossing 80+ contributors to KodaDot's repositories
- hitting 250+ pull request per month 
- over 300+ stars and 200+ forks of repository
- thanks to that we are among most popular
- open source NFT frontend, right after DotApps
- substrate repository on Polkadot right after Acala,Astar & Moonbeam 

---
### upgrading bounty process to next level
- trusted contributors 
	- could do payout for others pull-requests
	- merge things to `main` branch
- created code review guild to distribute and offload core team
- setting up experimental Q&A guild to help us going through the stuff

---
### cross chain strategy of KodaDot
- multi chain compatibility 
- including support for 
- RMRKv1 & RMRKv2
- Basilisk NFT marketplace
- MoonRiver & MoonBeam 
- Astar WASM & RMRK-runtime
- Acala EVM+
---
### friendly user interface for managing your NFTs
- being your single asset interface for NFTs on Polkadot & Kusama
	- abstract technology from user 
	- which parachain I'm at and does it matter?
		- do necessary steps on behalf of user on background (token swaps, XCM transfers)
	- simplification of token transfers
	- safety of transfers
- brewing protocol compatibility between various NFTs standards called Reactive NFTs 

---
### rNFTs - Reactive NFTs (codename)
- make offers & royalties 
- collab
- reactive actions 
- equips & linking NFTs 
- loot and bundles
- forking & remixing
- game integrations  
- protocol compatibility 
- XCM token transfers 
- performance we are doing today is based on our experiment 
- https://docs.kodadot.xyz/reactive-nfts

---
### Experimental landscape
- we are heads down trying new things and you can do too with us
	- ✅ extremely fast multi-chain search (wink SubSquid)
	- abstracting NFTs from user experience
	- generative art minting
	- zkPrompts marketplace
	- on-chain art without need for off-chain code
	- graph NFTs 

---
### Your contribution matters 
we are looking forward for more collaborators on
- music NFTs
- GLSL/shaders
- on-chain art grifters
- helping to shape our API/SDK for games

---
### SubWork -- your best web3 retreat in mountains
- physical space outside from city to laser focus on your project
- based in Bled, Slovenia, on footstep of Julian Alps
- rated among top10 beautiful places in the Europe
- up & running
- we've already had 20+ visitors over summer '22
- opening ceremony soon
- go to the https://subwork.xyz for more
- https://twitter.com/subworkBled
---
### Enjoy party
- Thanks for having us
- Thank you for your conribution
- You can find us  
  - https://dsc.gg/kodadot
  - https://twitter.com/kodadot
  - https://twitter.com/vikiival
  - https://twitter.com/yangwao
  
