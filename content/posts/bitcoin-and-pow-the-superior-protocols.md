---
title: "Bitcoin and PoW: The Superior Protocols"
date: 2022-05-16T15:30:00-04:00
draft: false
---

1/12/25 Update: This article was written awhile ago. While I still agree with what I wrote I think it's not at a depth I'm happy with. If I have the time I would like to write a much more comprehensive, in-depth article with plenty of footnotes & citations arguing in favor of Bitcoin. If I ever find the time I might.

First, let me start by saying I can't claim to be unbiased here. I'm a bit of a "Bitcoin maxi" (though I usually don't use that term).
However, I've been following Bitcoin/cryptocurrencies since a whole bitcoin was only a few hundred US dollars (i.e. somewhere around 7 years now).
I've done an immense amount of research through the years to support my opinions, which leads to my pro-Bitcoin bias.

Let me lay out what this post is and isn't. It is about why I believe Bitcoin, the Lightning Network, and proof of work (PoW) to be the only cryptocurrency protocols viable as money.
It isn't about shitting on other cryptocurrencies, though they will be mentioned where relevant (i.e. talking about PoS means talking about Ethereum).

Bitcoin has a lot of things going for it. It's truly decentralized. It's creator is unknown which is a good thing that led to a diverse decentralized group of developers working on it in the open. Etcetera.
What makes Bitcoin so great for money that most others cryptos lack is a large PoW mining population, true decentralization (which is supported by it's small blocksize allowing anyone to run a node), and political neutrality.

No-one is disagreeing with these points. Bitcoin critics usually have 2 major points: that PoW uses a lot of energy (leading to environmental concerns), and that on-chain Bitcoin takes too long / has high fees.

I'll address the latter first. Yes, it's true that Bitcoin blocks take 10 minutes on average to mine and can sometimes have fees of a few dollars USD.
These concerns were valid many years ago but are no longer so. Bitcoin provides a very secure and stable chain for medium and large transactions.
When you are sending 4, 5, 6, 7, 8, 9, or more figures USD of Bitcoin, you want it to be this secure.
Think of it like sending a wire transfer, wire transfers are not instant and often have fees reaching into the hundreds of dollars.
Those fees are paid because of the security of a wire transfer. The same is true of an on-chain Bitcoin transfer.

So what do you do for smaller transactions? That's where the lightning network comes in. I'm not going to say there are zero issues with the lightning network, but it works fine for day-to-day transactions which is it's primary purpose.
The lightning network allows you to send bitcoin for fees as low as 0 but usually around a few cents USD. It's great for smaller transactions (less than 4 figures).
This lines up nicely, because lightning allows instant, almost-free payments for day-to-day transactions (think of where you would use a debit card), whilst larger transactions can use on-chain Bitcoin giving them the immense security of the Bitcoin network.
The real issue with lightning is liquidity, but this is less of a problem these days, especially when considering lightning is for smaller transactions so you really don't need a large amount of liquity for personal nodes. According to [1ML](https://1ml.com/statistics) currently the lightning network has over $114 million worth of Bitcoin in liquidy, with nodes averaging $6,500 each. And this is actually low because USD-Bitcoin price is down right now, it'll be closer to $200 million total capacity if/when the price recovers.

TLDR: Use on-chain Bitcoin for larger transactions or those needing immense security. Use the lightning network for instant and nearly-free smaller day-to-day transactions.
Just think of when you would do a wire/ACH transfer or write a check and use on-chain for those situations, and lightning for situations where you'd use cash/card.

With that addressed, the other major concern of Bitcoin critics is energy usage of the PoW mining protocol. First, let me say this is intentional.
Energy-usage is not some accidental byproduct of the PoW protocol, it's the main input. Only PoW backed cryptocurrencies can say they are secured by literal energy.
***Literally secured by energy***, that's crazy to say but it's true. Whenever you see those stats of "a bitcoin block on average takes x energy usage", that means your bitcoin block is *literally secured by that energy* (in addition to time).
Note that measuring per block makes sense, but ignore people measuring the "energy per transaction", that's not how Bitcoin works.
Miners mine blocks with a variable number of transactions, so that number is always changing and very misleading (and ignores that many transactions happen on the lightning network leading to a much lower overall number than they claim).
Technically, the amount of energy securing that specific block is slowly reduced as more efficient mining hardware is released, but that's alright because by time that makes a difference there will be tens of thousands of additional blocks in front of that block securing the whole chain.
When people say "Bitcoin uses the same amount of energy as a small country", what they are saying is not only would an attacker need billions of dollars worth of hardware to perform a 51% attack, they also need to have access to **the same power output as a small country**!

What this means is that the only attackers who could even potentially perform a 51% attack is essentially nation states with a TON of excess energy output, TONS of extra money for procuring the hardware required, and the ability to actually get their hands on that supply.
There is currently no nation capable of this, it would take many years to actually acquire that amount of hardware due to supply constraints, and by then most other miners would have added more equipment as well as upgrading to better hardware.
So the target for an attacker looking to perform a 51% attack is a floating one that is moving ever further away from the reality of being able to be pulled off.
Additionally, whilst some nation states may have access to that amount of capital, they don't have access to that much excess energy.
When energy production facilities produce excess, they dial down their production, and get closed down if not needed.
So, a nation state would have to spend billions more and many years to bring back online shut down plants and build new ones.
Once again, a moving target, as the total amount of energy needed increases as new miners come online.
So a moving target in terms of both hardware needed and energy needed (and thus money needed as well).
It's essentially impossible to do this, it's much more efficient to just launch scams sites to steal Bitcoin from people or to find and exploit bugs in applications utilizing Bitcoin.

You might say "that's all well and great, but that energy usage is hurting the environment!" This is partially true.
Even when you ignore that most other money has externalities associated with it that Bitcoin doesn't (e.g. keeping the poor out of the system), let's address Bitcoin's energy usage.
According to data from [OpenNode](https://www.opennode.com/blog/bitcoin-bad-for-the-environment/) many miner use renewable energy resources, with around 73% having it in their energy mix, and about 40% of total consumption being from renewable sources.
On top of that some energy comes from "wasted energy". This is energy that's being wasted (e.g. natural gas flaring), so Bitcoin is using a resource that's otherwise being wasted.
You cannot attribute these emissions to Bitcoin mining because they were already being emitted.
Think of a gas-powered self-driving car that's always driving, whether I'm in the car or not it's emitting emissions so those emissions can't be attributed to me just because I got in the car. It's actually a good thing because at least those emissions aren't being emitted for no purpose anymore.
According to [OpenNode](https://www.opennode.com/blog/wp-content/uploads/2022/01/OpenNode_Energy_Report_1.14.22.pdf) it's estimated that 39 - 73% of Bitcoin's energy consumption is carbon neutral.
So to look at it another way, already at least half of Bitcoin's energy consumption is coming from renewable and wasted energy sources.
And Bitcoiners do want to make the other half carbon neutral as well. There's a better way of looking at this: Bitcoin can **increase** the proliferation of renewable energy sources.
The biggest problems with renewable is they are located in weird locations (e.g. you may not live in a sunny or windy area) and that they are intermittent.
Bitcoin can help solve both this problems, building mining hubs where renewables sources are located, giving a reason for renewables to be built there, and in addition
Bitcoin miners can turn themselves on and off to even out the intermittentness.

TLDR: Bitcoin's energy usage is already much cleaner than you probably thought, at least half of it's usage is essentially carbon neutral. Additionally, Bitcoin could be used to significantly increase the number of renewable energy sources and even out the problems of intermittentness.

P.S. Proof of Stake (PoS) is not a viable alternative to PoW. Instead of securing the network with energy, it takes a "the rich get richer" mentality that matches traditional fiat.
If you can't afford to buy into the network, you get no control in the network. PoS is not a fair democratic system, PoW is.

It's time to separate money from state, as church and state were a few centuries ago, and Bitcoin is the only money with potential to do so.
