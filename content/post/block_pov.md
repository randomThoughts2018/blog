---
title: "Why Blockchain is Not a Solution To Every Problem"
date: 2018-02-15T18:48:37Z
categories: ["blockchain", "innovation"]
draft: true
---

# Introduction 

There is a hype wave flowing through the financial world around blockchain. It is touted as the most important innovation in finance since the invention of fiat money. It promises to bring huge benefits, reduce costs, and allow banks to become as nimble and lean as Silicon Valley startups. Everybody is buying into the hype. Central banks, big banks, small banks and financial startups all drool over the possibilities. Either you are in or you’re not cool. This document falls squarely in the latter category.

We will here explain some of the reasons why blockchain is actually just a tech bubble waiting to burst, and why the challenges to implement blockchain technology more often than not overwhelm the benefits that they bring. Most of the optimism around blockchain is likely to be unjustified, and we intend to start an exercise of thoughtful reflection that will lead to insight and better decisions free of hype.

*Disclaimer*: We think that we may be an undiagnosed low-intensity hipster, in part because of our bias against hype, so when we see hype, we want to kill it. This document may be just a knee-jerk reaction against virtuous (as opposed to vacuous) hype, but we have yet to see such a thing as virtuous hype.

# What in the World is a Blockchain?

First of all, blockchain is not Artificial Intelligence, nor it is Gort from “The Day the Earth Stood Still”, although it could resemble it to the untrained eye. A blockchain is not a database, but it can be used as a means to share and synchronize one. A blockchain is not a bank, although it can be used as a way to keep an accounting book. A blockchain is not… you get the idea.

After a few hours trying to define what a blockchain is, We came up with this: “A shared transaction log collectively validated and synchronized using cryptography.” That sounds a bit unsexy for an object of so much hype, and it is! A blockchain is a way to validate and synchronize an ever-growing log between different computers. It can be made to work even where the operators of these computers do not trust one another, depending on how they take advantage of the cryptography part.

# Bitcoin, the First Blockchain

Blockchain technology was designed to solve an outstanding problem: creating an asset to be used as a medium of exchange (money?) that was not under the control of bureaucrats, was not subject to (permanent) inflation, was not susceptible to censorship, and did not involve counterparty risk. Such an asset had better be digital and live on the Internet, to reduce the risk of physical seizure and to make it portable and easy to transfer. It could not require central systems to track ownership, since powerful governments could gain control of these or shut them down. Blockchain technology was designed as a means to run the Bitcoin network, which through the bitcoin asset has resolved these issues.

# Blockchain Technology

Blockchain technology is very elegant, and has been altered in multiple ways to support alternative uses. Notably the Ethereum blockchain can be used to run arbitrary validated computations known as smart contracts. Some private blockchains have been created that are not censorship-resistance and are meant to keep a log of transactions relevant to particular industry requirements. The financial industry has seen a potential benefit in blockchain technology to run automatically-validated accounting ledgers including the ability to execute smart contracts for complex financial instruments. The idea that a set of computers operated by different parties that do not trust each other can keep a log of computational transactions that is hard to tamper with is attractive, since it reduces the need for manual processes to maintain the books and prevent fraud.

# Albatross: A Very Large Oceanic Bird
One aspect that is missing in most discussions about blockchain technology in the financial industry is the suitability, risks and barriers involved. We claim that that these considerations are far from negligible, and make most blockchain projects pointless albatrosses: solutions looking for a problem.

In this section we will deconstruct some of the requirements for a successful implementation of blockchain technology, to show why it is much harder than everyone thinks.

# Cryptographic Keys
Cryptography needs keys, no, not passwords but long hard-to-remember cryptographic keys that usually reside in disks or specialized hardware. These are the bane of any cryptographic deployment. We have had public key cryptography for a long time, but its adoption is limited, because it requires managing these blobs of data securely. It is surprisingly hard to prevent cryptographic keys from falling on the wrong hands. In fact the single most contentious issue with Bitcoin is precisely its reliance on cryptographic keys. It seems you can’t have your cake and eat it too. Time and again people lose keys either to oblivion or to thieves, and the associated bitcoins evaporate. This is the price to pay for being a pioneer using such cutting-edge technology.

As Bitcoin establishes itself and its adoption increases, solutions such as multi-signature accounts, offline wallets, managed wallets, and specialized hardware is popping up to tackle the issue of cryptographic key management, but a general fail-proof winner-takes-all solution is yet to be found for this tricky issue. Now, economies of scale make it so that brave security providers target the Bitcoin ecosystem. It has achieved certain size, and whatever good solution is created will find a good market where to operate. I am confident that the key management problem will be significantly mitigated in Bitcoin.

As for the sure-to-be myriad of different little private blockchains in financial institutions, I have not much hope at this point. Unless/until the financial industry coalesces towards a particular blockchain technology that security experts can focus their energies on, there is little hope that appropriate cryptographic key management will happen. We all know how good the financial industry is at agreeing on common standards without the motivational power of a regulatory agency.

# Blockchain for Distributed Decentralized Disruptive Lean Innovation
Buzzwords are the opium of the tech industry. They say nothing but still are uttered with gravitas. Your great idea for a blockchain for <insert buzzword> will almost surely not work, unless you have read the Bitcoin whitepaper and actually understood what it says. No, it is not hip to love blockchain and hate Bitcoin, therefore not reading the Bitcoin whitepaper at all. We are not saying you need to be able to do elliptic curve cryptography on a napkin, but you at least should know what public key cryptography is, what a cryptographic hash is, and how they are assembled together to form a blockchain. You must also understand the difference between Bitcoin and Ethereum, and maybe even understand why people buy bitcoins at all. Yes, there is a rational motive. Find it! Also, while you’re at it, find out why Freicoin (or pretty much every altcoin) is doomed.

I do not recommend starting to learn about blockchain technology from the Ethereum website. Hyperbole such as “Build unstoppable applications” or “Ethereum is how the Internet was supposed to work” will fill you with false expectations. Just don’t. Be smart. Read the actual documentation and write the smart contract.

If you are not capable of writing software, you will not understand how a blockchain works, and you’ll be unable to come up with reasonable use cases. A blockchain is a computer science concept. Teach yourself some computer science first.

# Blockchain for Blockchain’s Sake
Blockchain for the sake of blockchain is like preventive chemotherapy. There is a possibility that you might be solving a problem that you may or may not have, but the downsides are discouraging. The only way to find out if your problem can be solved by blockchain technology is not learning about blockchain technology and then come up with contrived use cases to justify the time it took to learn how the thing works.

# Blockchain for Politics
Maybe the anarchist-libertarian underpinnings of Bitcoin ruffle your feathers, and you think that an asset with monetary qualities that isn’t under the strict control of a group of bureaucrats is an insult to mankind, or goes against economic best practices. You are not alone, there are many like-minded people that would love to see Bitcoin die, even former Bitcoin developers. Look for “bitcoin obituaries” online for an amusing selection.

But coming up with a blockchain project (e.g. Freicoin) for political reasons is likely to lead to disappointing outcomes. The success of a P2P network depends on carefully incentivizing behavior that leads to a better collective outcome for participants. Bitcoin has been designed to carefully balance incentives. Freicoin hasn’t. If you think you have a good blockchain idea, and you have figured out how to keep everyone incentivized to play by the rules, then you may be onto something. It is time to start developing (I said you need know how to program, right?) and prove the world they’re wrong and you’re right. Duty calls.

# Party Like it’s 1976
Most of the people that swear that blockchains are the greatest thing in the universe actually never came across the concept of digital signatures.  Digital signature technology for some reason hasn’t caught up with banks the way it should have by now. The idea that you can know that someone did something (sending a signed message, usually) through a mathematical algorithm has the power to amaze today as much as it did in 1976 when it was first described.

Blockchains are just a novel way to use cryptographic signatures (1976) and cryptographic hashes (1976) to write transaction logs (I still don’t get the hype). In other words, the only thing that was novel to bitcoin or shall we say ”blockchain” was distributed trustless consensus or to the novice what we call mining in bitcoin  and that is precisely the feature that large organizations do not want. That raises a very important question of are we really interested blockchain or its just a huge conspiracy theory of fellow bitcoiner’s to take bad PR from Bitcoin to something that we actually have no evidence of, yes you thought right it’s “blockchain” and give them time to fix few of the technical holes in the implementation and comeback to bite us in future.

We think that the main reasons why digital signatures haven’t been adopted more widely in the financial industry are the same reasons why ultimately blockchain technology faces the same challenges. Namely managing and exchanging cryptographic keys poses a real challenge and overhead for any organization.

In conclusion, we really think we need to take a really hard look at ourselves and decide what we actually want because at the moment it really seems that all of us really want the features of blockchain but are not willing to accept the demands that it puts, in terms of novel business models and brave decisions. 