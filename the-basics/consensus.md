# Consensus

“…79% of the consensus nodes, and all the major block explorers and endpoints for light wallets, were following this new chain. Perhaps the new dev fund will fund some development, or perhaps it will just all be embezzled by the leading pools and exchanges and their cronies. But regardless of how it turns out, the fund is for all intents and purposes a fait accompli, and regular users have no way to fight back.”&#x20;

“Can this happen on your blockchain? The elites of your blockchain community, including pools, block explorers and hosted nodes, are probably quite well-coordinated; quite likely they're all in the same telegram channels and wechat groups. If they really want to organize a sudden change to the protocol rules to further their own interests, then they probably can. The Ethereum blockchain has fully resolved consensus failures in ten hours; if your blockchain has only one client implementation, and you only need to deploy a code change to a few dozen nodes, coord inating a change to client code can be done much faster. The only reliable way to make this kind of coordinated social attack not effective is through passive defense from the one constituency that actually is decentralized: the users.”&#x20;

“If you have a community of 37 node runners and 80000 passive listeners that check signatures and block headers, the attacker wins. If you have a community where everyone runs a node, the attacker loses. We don't know what the exact threshold is at which herd immunity against coordinated attacks kicks in, but there is one thing that's absolutely clear: more nodes good, fewer nodes bad, and we definitely need more than a few dozen or few hundred.”     \
&#x20;                                                                                                \--Vitalik Buterin, The creator of Ethereum

## WeeLink RDPoSA

WeeLink Chain adopted the Random Delegated Proof of Staked Authority (RDPoSA) consensus mechanism. RDPoSA is a combination of Proof of Authority，Delegated Proof of Stake and Random Beacon. Here, blocks are produced by a limited set of authorized validators that are randomly elected in and out based on staking-based governance.

&#x20;PoA consensus is added as an optimizing method to the normal Delegated Proof of Stake model that leverages identity as the form of stake rather than only staking tokens. The identity is staked by a group of authorities that are pre-approved to validate transactions and blocks within the respective network. In the WeeLink Network, Public Cloud Nodes (“PCNs”) with full ledger are pre-approved and routinely inspected by the Security and Trusteeship Council under the WeeLink General Assembly, a decentralized authority.

&#x20;PoA removes a primary concern within the DPoS model that, although stakes between two parties may be equal, their value to each party may vary significantly depending upon their holdings. For instance, Alice may have 1,000 XYZ tokensstaked and Bob may also have 1,000 XYZ tokens staked. However, Alice has $10 million outside of her stake and Bob only has $10,000 outside of his. Therefore, Bob is much more likely to be invested in the success of the XYZ network than Alice since his stake represents a substantially larger portion of his overall finances. Decentralized PCNs have prominent advantages over other types of WeeLink nodes in that they have better facilities and computational capabilities, and are routinely monitored.&#x20;

Any validator who acts maliciously can easily be removed from the validation process and replaced. The end result for that validator would be a public hit to their reputation as well as a loss of future financial earnings. The use of reputation through identity is of especially particular relevance to contemporary times. As Warren Buffet put it:&#x20;

“It takes 20 years to build a reputation and 5 minutes to ruin it. If you think about that, you’ll do things differently.”&#x20;

In the current climate of social media in the age of the Internet, we have seen repeatedly how easy it is for people to completely lose their reputation through public condemnation based on something as miniscule as a poorly thought out comment or remark (whether deserved or not). The increasing awareness of the fragility of reputation in the public domain should serve as a potent incentive for validators to act honestly within the system.

There are 3 basic requirements to become a WeeLink validator which have important implications for the incentive structure driving their actions towards honest behavior:

* [x] Their identities need to be formally identified on-chain with the ability to cross-reference these identities through reliable data available in the public domain (such as a public notary database).&#x20;
* [x] Eligibility for becoming a validator must be difficult to obtain in order to ensure the long-term prospective position of the validator is one of clear incentive, both financially and reputationally, to remain an honest validator.&#x20;
* [x] There must be complete uniformity in the process for establishing validators.

Whether PoA or DPoS, the group of validators is usually supposed to remain fairly small (\~25 or less) in order to ensure efficiency and be manageable. To limit this disadvantage, WeeLink validators take turns to produce blocks that are randomly picked from a larger set of pre-approved validator pools, while the number they staked is among the top several hundred to top several thousand or above a threshold.



## PoW and Application Mining

Mining WLK on PCNs:

* [x] Obtain a WeeLink wallet: WLK are stored in digital wallets in an encrypted manner. This will keep your WLK safe.
* [x] Secure the wallet.
* [x] Choose a PCN: PCN service providers allow users to rent ESC (Elastic Compute Service).
* [x] Choose an ESC package: to choose a package, you will need to decide how much you are willing to pay and deploy your normal business assets.
* [x] The system will separate a small portion of computing power of your ECS and add it to the mining pool. A worker and an account are created that can be used to track your contributions to the pool.
* [x] The system puts your earnings in your wallet.

Workers across PCNs are randomly selected and grouped as fishermen, subchain validators and collators, etc., and rewarded in WLK and related ERC-20 Tokens. Workers are confined in security “sandboxes” mutually controlled and monitored by PCNs, Dao and Council to ensure integrity and proper behavior.

