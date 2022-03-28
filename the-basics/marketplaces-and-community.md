# Marketplaces and Community

WeeLink has three types of markets: _**the Development Market, the Application Market and the Resource Market**_. The three markets have the same structure but different functions. The Development Market allows Developers to pay contributors for using their App and Dapp developed components. The component might be packaged code that can be reused and deployed by another application, or a set of services that is merely exposed through the WeeLink Asset（pod） interface. The Application Market allows Clients to purchase ready-to-deploy Apps and Dapps. The Resource Market allows Clients or Developers to have Apps and Dapps deployed by paying PCNs the cloud resources they use. The network guarantees that providers are rewarded by the clients when providing the service or product.

## Collaborative Markets

There exist a great number of three types of Markets operated by different Vorgs for business purposes. Fig.14 shows a collaborative case.



## Requirements

We describe requirements for a market and additional operations by the WeeLink Network.

### Integrity

WeeLink is providing SHA512 hashes for all the packaged code images made available to clients in a DID Document. The DID Document is digitally signed by the Market and its contributor. This end-entity certificate is chained to the Market and Contributor’s Vorg Root DID Document assigned from the registration center. Authenticity of the registration center’s X.509 certificate chain is validated prior to DID document signature verification. Always verify the signature of the DID Document before using the contents from the Markets to add integrity to the WeeLink network. If the signature cannot be verified, then the contents cannot be trusted and must be abandoned.

### Copyright Protection

Market contributors can determine whether their original codes and packaged code images can be accessed directly while the customers can still use them in the Pods.

### License and Operation

A DID license is a contract between the entity that created and supplied an application, underlying source code, or related product and its end user. The license is designed to protect the intellectual property of the software developer and to limit any claims against them that may arise from its use. The license also provides legally binding definitions for the distribution and use of the software. End-user rights, such as installation, warranties, and liabilities, are also often spelled out in the software license, including protection of the developer’s intellectual property. WeeLink Network helps handle and control these cloud-based applications. Refer to the details in the DiD license including:

* [x] Whether monthly or annual charges are paid&#x20;
* [x] Duration of the agreement&#x20;
* [x] Terms of cancellation of the agreement&#x20;
* [x] Recovery of any charges if canceled during the agreement.

### Version Control

The Market and the WeeLink Network help end users to track, upgrade or downgrade their assets, the cloud -based applications.



## Feedback and Collaborative Maintenance

The marketplace is also responsible for maintaining public feedback about the quality of components applications and the reputation of their developers, as well as other information. This information will help users evaluate reusable components. All the marketplace information is recorded in the public ledger powered by WeeLink blockchain technology to ensure transparency and trust.

Though the end users can launch the applications from the Market using the WeeLink Automatic Deployment System, they could also enter into an agreement with the application contributors for them to help to maintain, upgrade and monitor the application performance while the end users are still the only owners of their business data.



## Staking, Promotion and Insurance

Market has put together a collaborative effort to build, manage and monetize Apps and DApps at scale. To achieve this in a fully decentralized way, the incentives of the participants will be reconciled through the governance, security, and value capture utilities of the WLK token. The project will have a completely open and direct governance model, where any WLK token holder will be able to stake to obtain direct voting privileges in the Market Dao. In addition, stakers will receive a portion of the Market revenue.

In the case of a malfunction, the end user will be able to claim compensation up to a pre-negotiated amount from the staking pool. An on-chain dispute resolution protocol will be used to decide if the claim is to be paid out based on the presented evidence. This will incentivize stakers to actively participate in governance to ensure that Apps and DApps are being managed transparently and in a way that minimizes security risks. Successful governance—generating revenue from Apps and DApps while avoiding mistakes that will result in paying out insurance claims—will be rewarded in WLK tokens, which will create a positive feedback loop that will continually improve governance.

The end users could also act as sales representatives to promote specific Market items and share the promotion fee.
