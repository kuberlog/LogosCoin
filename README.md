# Logos Coin

## Definition

Logos Coin is a meta-coin, a process if you will, that allows every entity with an internal Logos, (IE a Holy Spirit inside of them), to issue their own currency. Every internal Logos will also keep a table of exange rates that determine how much they value other currencies. Since each currency is wholy minted and retracted by a single issuer, then the exchange rate that each currecny defines will be the actual exchage rate. 

## Example

If kuberlogCoin defines an exchange rate as follows `{aCoin: 10, bCoin: 5, cCoin: 1, dCoin: 0}`, then an entity with 1 aCoin can exhange that aCoin with the kuberlogCoinMint for 10 kuberlogCoins, a bCoin can be exchanged with the mint for 5 kuberlogCoins, a cCoin can be exchanged for 1 kuberlogCoin, and a dCoin is worthless for exchanging with a kuberlogCoin.

## Space complexity

Because of the n^n space complexity of keeping tables of one-way exchange rates, a meta-currency that groups currencies together, can be used in the one-way exhange rates to compress that complexity. A table of meta currencies that group currencies by "country of origin" would be identical to the current state of affairs, excpet there would be n^(country^2) exhange rates instead of the (country^2) exchange rates we see today. Technically, today there are n^(country^2) exchange rates, since each individual is able to set the price they are willing to trade at, but realisitically that price converges onto a single point since each countries currency is a concrete currency and not a meta currency.


## Dynamics

So how would the dynamics of a Logos Coin economy play out. Just think of each Logos (IE Person, Corporation, Government) as their own sovereign. If the sovereign devalues their currency by trading lots of their minted currency for things, then the exchange rates for their currency will decrease dynamically and their currency will inflate to worthlessness. Each entity's currency is backed by that entity's potential (IE intrinsic value). When purchasing goods from an entity, prices are set in that soverigns own currency (but foreign currency can still be traded at the set exchange rate). 

## Taxation
Each entity's mint has the ability to tax any other entity in the mint's currency (given that the other entity posses currency to pay), which means if `a` has 10 `kuberlogCoin` and kuberlog does not wish to keep those coins in circulation, `kuberlog` could simply tax all 10 `kuberlogCoins` from `a`. The mint has unilateral power to rectract coins from the economy from anyone they wish, however, excessive use of this power will devalue or even blacklist the currency from other sovereign exchange rates alltogether.

## Rational

If we are going to say that every person is uniquely valuable and sovereign in the eyes of the Logos, then it must be the case that each and every person can issue their own currency. Soverigns by right have the ability to issue currency. There is really no escaping this conclusion in any economic system based on currency that is embedded in a philisophical system that declares each and every being to be a sovereign with a holy spirit. A economic system that deviates from this is philisophically inconsistent.

## Implementation of a Jugement currency

A LogosCoin is a representation of value, specificially the value of how much a specific being (the being who's face is on the coin) places on another specific being (the being that holds the coin). This representation of value can be directly controlled by placer of value. If an idea or person decreases in value, a coin can be taxed by the mint (owned by the being who's face is on the coin). The act of taxation is a markdown of value of a particular person or thing.

If a person places logoscoin from their mint into an idea or concept, they have "invested" into that concept. The percentage of coins invested relative to coins ever minted represent the "level of investment" in the idea. That level of investment is then treated as equity in the idea. Ideas gain value when others invest their own coin into it. The level of investment of each shareholder on an idea can be used to calculate percentage ownership of the concept (i.e. shares). As more and more investors come on board (by buying the product, supporiting taxation proceeds going to the idea, and the like) the early shareholders gain more and more value by controlling the coins invested. At any point in time, a person can retract their coins from the entaglement by taxing the coins away. If for instance the concept turns out to be dangerous or harmful, then the shareholders can tax the concept, eliminating its capital in the process, effectively killing the idea. Deltas will be tracked and measured, so it will be visable if an idea or concept had lots of support and then later lost it. This effectively would implement an meritocratic system of jugement. Each coin invested is an entaglement and there can be nearly unlimited entaglements, the value of each entanglement is inversely proportional to the number of entaglements in extant at the time of mint multiplied by the value of other coins entangled in the entaglement.
