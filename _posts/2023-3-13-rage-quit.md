---
layout: post
title: Thinking About Rage Quit
---

*Disclaimer: [Prop 248](https://nouns.wtf/vote/248) has none of the properties that we traditionally associate with rage quit such as protection from 51% attacks. It is rage quit in name alone. The verbs implementation is a better starting point for Nouns rage quit. You can read about it here:*

[https://hackmd.io/jctHoCh0STORZGyJIQKpMA](https://hackmd.io/jctHoCh0STORZGyJIQKpMA?view)

## Majorities and Minorities 

Nouns DAO has many unique and interesting features, but one of the most novel and difficult to grapple with is its permissionless nature. While corporations have explicit objectives and management teams that filter participation in the name of achieving their objectives, Nouns and Nounish DAOs have no such thing. All objectives are emergent. 

Anyone can join Nouns DAO at any time, and so the objectives of the DAO are ultimately a venn diagram of the objectives of its ‘permissionless’ members. Given that reasons for membership are constantly evolving, the DAOs overall objectives will evolve too. At any given time Nouns is also likely to have more than one set of objectives, and it’s natural to assume that some objectives will be prioritised by the majority of members, and others will be championed by a minority.

## Protecting the Minority

The purpose of rage quit is to protect DAO minorities from tyrannical majorities (DAO majorities don’t need protection from minorities, because only majorities can pass proposals). The theory is as follows: if the majority approves a proposal that the minority objects to, the minority can take their pro-rata share of the DAO treasury and exit the DAO before the proposal is executed.

While the most extreme example of this kind of proposal is a ‘51% attack’, where a majority proposes that in addition to withdrawing their own pro-rata share of the DAO treasury, they’ll withdraw the minority’s share too, other examples are more subtle. 

A minority in one jurisdiction might be worried about legal risk if the majority in another jurisdiction passes a specific proposal. A minority might consider the spending of the DAO treasury on memes and public goods to be extremely wasteful. It’s ultimately not possible to encode rules in the protocol about what the minority should and shouldn’t be protected from; they are either protected by the ability to exit, or they are not.

## A Special Case for the Minority

Regardless of whether you believe the minority deserves to be protected in Nouns DAO, there is a special case where a minority with a specific objective will have high confidence that it can protect itself: when Noun auctions are settling below ‘book value’. 

When Noun auctions are settling below ‘book value’, it becomes theoretically possible to earn a profit from buying Nouns, and passing a proposal that withdraws each Noun’s pro-rata share of the treasury. If a minority forms with this objective, and the minority does not have a rage quit mechanism to achieve its objective, there is a natural incentive for the minority to attempt to become the majority.

This is because it’s easy for the minority to incentivize new members to join their cause: the more members that join, the higher the probability that a withdrawal proposal can be passed, and the higher the certainty of profit for each member. The venn diagram of the DAO will slowly but surely become focused on one thing: extraction of the treasury to satisfy the objectives of the profit seeking group.

As long-term oriented Nouners we can yell and cry that this was never the intended purpose of Nouns, or that turning something that is supposed to be about more than money into a pure arbitrage is immoral, but as crypto advocate Charlie Munger says, “show me the incentive and I'll show you the outcome”. And that’s where we are today. A minority’s incentivized attempt to become the majority is slowly starting to crowd out all other DAO objectives.

## What About the Veto?

The Nounders (founders) of the project initially granted ourselves a veto power to protect against situations like this. This power has since been transferred to a Cayman foundation company with a number of independent directors (two of the founders are a minority on the board). 

While the Foundation could theoretically use the veto to prevent proposals that attempt to withdraw the treasury from passing, using the veto against a large majority that is attempting to equitably withdraw the treasury will become increasingly awkward.

Additionally, the profit seeking group can employ other strategies as they increase their voting power, such as passing a proposal to pause minting or voting against all proposals and stalling the DAO until their proposal is allowed to pass.

## Regulatory Considerations

Given the above context, implementing rage quit seems like an obvious choice, but the most compelling argument against it, is that the ability for Nouners to withdraw the treasury could increase the probability that Nouns are securities. 

The legal arguments are complex and best left to lawyers, but if we assume that there is any increased probability of regulatory risk, we are forced to contend with a terrible set of incentives that emerge upon deployment of a non-compliant rage quit implementation: the quitters get the treasury ETH and the stayers get the regulatory risk. This is arguably a worse outcome than the standoff described above.

## Moving Forward

A compliant implementation of rage quit will not only protect future DAO minorities, it can also act as an escape hatch to prevent the need for the book value minority to try to become the majority. If we can implement a complaint version of rage quit, it should be a high priority. This will let us protect future minorities, and ultimately let other majorities resurface their long-term objectives so that we can get back to all the things that make Nouns fun.
