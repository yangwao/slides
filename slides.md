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

# KodaDot: the Metahour

Brief history of KodaDot and beyond



<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---


# Who we are?

<div grid="~ cols-2 gap-2" m="t-2">


<div>
<img border="rounded" style="border-radius: 50%;" width="300" src="https://pbs.twimg.com/profile_images/1490359385108930563/tWaIhzMH_400x400.jpg">

- 📝 **vikiival** - magick
  - Simplier one, less features
  - bit slower reindexing time
  - backbone of KodaDot's RMRK markteplace
  - so far *stable*
  - no ability for external calls
  - aggregations out of the box
  - auto-balanced for more nodes
</div>

<div>
<img border="rounded" style="border-radius: 50%;" width="300" src="https://pbs.twimg.com/profile_images/1562000851174133762/3BxCwuL0_400x400.png">

- 🦑 **yangwao** - rubick
  - More complex, higher flexibility
  - super fast reindexing (~ 2days)
  - can be used for external calls (fetch metadata from IPFS)
  - *alpha quality software*
  - can write custom queries through resolvers
  - europe based
  
</div>

</div>

<br>
<br>

---


- desired talk length 25 min
- participants 
	- EXO, Pendulum, SubSquid, RMRK, Koda, Bifrost, Basilisk, Astar, MoonBeans, Phala Network, Dia


### KodaDot: past, present, future.
- 1 year recap of KodaDot ecosystem of 80+ contributors

#### Introduction 
Viki - co-founder, technical wizard of bleeding edge implementations in KodaDot 
Yangwao - co-founder, radical veteran in crypto and open source 

### Brief history
- how we got to the ecosystem 
	- SubKey in VueJS (PoC)
	- first grant from web3foundation
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
- ever breaking 🤷‍♂️  constat software evolution 

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
![[Pasted image 20220914113643.png]]

- first $50k paid out for merged pull requests

---
- standardizing program for paying out bounties to developers
- setting up payout bot in repository - crappy but worked!
- crossing 80+ contributors to KodaDot, hitting 250+ pull request per month 

![[Pasted image 20220914113812.png]]

---
### upgrading bounty process to next level
- trusted contributors 
	- could do payout for others
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
### Friendly user interface for managing your NFTs
- being your single asset interface for NFTs on Polkadot & Kusama
	- abstract technology from user 
	- which parachain I'm at and does it matter?
		- do necessary steps on behalf of user on background (token swaps, XCM transfers)
	- simplification of token transfers
	- safety of transfers
- brewing protocol compatibility between various NFTs standards called Reactive NFTs 

---
### RNFTs - Reactive NFTs (codename)
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
- we are heads down trying new things and you can too with us
	- abstracting NFTs from user experience
	- extremly fast multi-chain search
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
