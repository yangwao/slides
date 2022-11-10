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

# The unified NFT developer experience

Making developers' lives easier

---


# Hey I am Viki 👋

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- co-founder of KodaDot

- technical wizard

- bleeding edge implementations in KodaDot 

- @vikiival

</div>

<div>
<img border="rounded" style="border-radius: 50%;" width="300" src="/vikiival.jpeg">
  
</div>

</div>

<br>
<br>

---

# What is KodaDot?

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- Open-source NFT markeplace in Dotsama ecosystem

- Multichain powered - Kusama, Basilisk, Moonbeam, Moonriver

- Technology agnostic - RMRK strings, runtime pallets,EVM, ink!

- Bounty based - bringing dev talent to the ecosystem

- 330 + forks, 220+ stars, 80+ contributors

</div>
<div>
  <img border="rounded" src="/new-landing.png">
</div>

</div>

---

# Architecture of KodaDot

<div grid="~ cols-2 gap-2" m="t-2">


<div>

- Frontend - Nuxt3, Vue composition API & Brick

- Services - Rust-based workers - pinning, images

- Backend - FireSquid Indexers by SubSquid, GraphQL API

- Packages
  - Minting
  - API
  - SubSquid utils
  - Conditional rendering

</div>
<div>
  <img border="rounded" src="/architecture.png">
</div>
</div>

---

# Hello, minimark!

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- Minimalistic implementation or RMRK protocol

- Do not rely on single implementation

- Covered by unit tests

- DX oriented

- How to upgrage to v2

- Batteries included - constructing metadata, resources

</div>
  <div>
    
  ```ts
  // Use RMRK1
  import { createCollection } from '@kodadot1/minimark/v1'

  // Use RMRK2
  import { createCollection } from '@kodadot1/minimark/v2'
  
  ```


  </div>
</div>

---

# Finally we have an API

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- Let's meet Uniquery

- Query builder on top of subsquid

- two implementations
  - Builder
  - REST

- Best thing? - no middleware server needed

- 15+ calls supported so far

</div>
  <div>
    <TokenDetail />
    <!-- <img border="rounded" src="/anime-music.gif"> -->
  </div>
</div>

---

# Why is Uniquery cool?

<div grid="~ cols-2 gap-2" m="t-2">
<div>
<h2>before</h2>

```graphql
  query nftListByCollectionId {
    nft: nftEntities(where: {
      collection: {id_eq: "2305670031"}}
  ) {
      id
      metadata
      currentOwner
      issuer
    }
  }
```

</div>
  <div>
  <h2>after</h2>

  ```ts
  import { getClient, ask } from '@kodadot1/uniquery'

  // using builder
  const client = getClient()
  const id = '2305670031'
  const query = client.nftListByCollectionId(id)

  // using REST
  const path = `/nftListByCollectionId/${id}`
  const result = await ask(path)

  ```

  </div>
</div>

<!--
- thanks to that, we are among the most popular
- open source NFT frontend, right after DotApps
- substrate repository on Polkadot right after Acala, Astar & Moonbeam 
-->

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


# Saving lines of code for XCMP

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- Have you ever played with XCMP?

- It's breaking tech, but it's not easy

- Luckily there is ParaSpell

- SDK for crosschain transfers

- Modular and easy to use

- Saving hundreds lines of codes

- Oriented on developers

</div>
  <div>
    <img border="rounded" src="/xcmp.jpeg" height="300">
  </div>
</div>

---

# Magic of ParaSpell

<div grid="~ cols-2 gap-2" m="t-2">
<div>

  <div>
  <h2>before</h2>
    <img border="rounded" src="/xcmp.jpeg">
  </div>

</div>
  <div>
  <h2>after</h2>
    
  ```ts
  import { xTokens as paraspell } from '@paraspell/sdk'

  const paraId = 1000
  const amount = 1e12
  const address = 'Fksmad33PFxhrQXNYPPJozgWrv82zuFLvXK7Rh8m1xQhe98'
  const call = paraspell
    .transferRelayToPara(api, paraId, amount, address)
  
  ```

  <img border="rounded" src="/paraspell.png">
  </div>
</div>

---



# Spin up your own DotSama project

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- KodaDot is a great example of how to build on Substrate

- To iterate fast we have sub-scaffold

- Open-source, hackable frontend scaffolding

- Based on Vue3, Nuxt3, NaiveUI

- ParaSpell UI will built on top of it

- Support for ink! coming soon

</div>
  <div>
    <img border="rounded" src="/scaffold.gif">
  </div>
</div>


---

# and what's next for KodaDot?

<div grid="~ cols-2 gap-2" m="t-2">
<div>

- being your single asset interface for managing NFTs on Polkadot & Kusama
  - abstract technology from a user 
  - which parachain am I at, and does it matter?
    - do necessary steps on behalf of the user in the background (token swaps, XCM transfers)
  - simplification of token transfers
  - the safety of transfers
- brewing protocol compatibility between various NFTs standards

</div>
  <div>
    <img border="rounded" src="/gallery-item.jpg">
  </div>
</div>

---

# We are heads down trying new things

<div grid="~ cols-2 gap-2" m="t-2">
<div>


<h3>and you can do too with us</h3>

- ✅ high-speed multi-chain search (wink SubSquid)

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
    <img border="rounded" src="/lucky-star-anime.gif">
  </div>
</div>

---

# SubWork -- your best Web3 retreat in the mountains

<div grid="~ cols-2 gap-2" m="t-2">
<div>


- physical space outside of the city to laser focus on your project

- based in Bled, Slovenia, in the footstep of the Julian Alps

- rated among top10 beautiful places in Europe

- up & running

- we've already had 20+ visitors over the summer of '22

- opening ceremony mid of December

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
