

### Project Details

To develop the python addon we plan to use the [Serpens addon](https://blendermarket.com/products/serpens) for the blender scripting interface:
- [Importing](https://drive.google.com/file/d/1rPy4Gn2a-q89NF56scdsaJdBHfnIu7s8/view?usp=drivesdk) the [near python API](https://github.com/near/near-api-py) and trigger the standard [minting action on a mintbase contract](https://drive.google.com/file/d/1QtwZ_iCDoYQR1joiodVZRX_RCmnjg2x5/view?usp=drivesdk), the minting action would be fired after the rendering has finished and the user has logged in with a [simple button located in one of these standard positions](https://drive.google.com/file/d/1cEowRRnfi4PKBXf4L4or7RneG171D6T7/view?usp=drivesdk) on the blender interface, triggering a web login.
- To lock the source content on the Varda Vault we would implement a specific locking endpoint on the [varda vault API](https://github.com/jilt/Vault-API-Filecoin) and the data importing options ([1](https://drive.google.com/file/d/1sjVCX1BqLhvBf4ol52P_lt_cxrRL_WjD/view?usp=drivesdk) and [2](https://drive.google.com/file/d/1haCCWKAEPzMxbU5MLmOLCyhgI_qLBzfq/view?usp=drivesdk)) of the Serpens graphical scripting interface.
- Mintbase basic core functions [reference](https://github.com/Mintbase/mb-sdk), the user has to create his own smart contract on mintbase or be an allowed contributor of an already existing one.
- We are willing to submit the final addon in the blender market (they have a quite long selection process to be allowed to sell), gumroad and Serpens stores along with minting a mintbase nft on the jiltverse store with the addon as unlockable content. The whole developing rpocess will be finished by the end on October, because I'm November the #nodevember twitter creative challenge starts for the blender community and we wish to use our addon to create content for the whole challenge/month and use it to spread word of this new tool within the blender community.
Price will be 1$ on the stores were free download is not allowed, and money earned will go to a newly created DAO to support artists thatint with our solution.


### Ecosystem Fit

Help us locate your project in the Mintbase landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem? Unlockable nft content/nft utility
- Who is your target audience?
- integration of mintbase smart contracts with [one of the most used 3D editing interface in the world](www.blender.org).
- Are there any other projects similar to yours in the Mintbase / NEAR ecosystem?
  - If not, are there similar projects in related ecosystems? No, the blender community has tried to breach the Blockchain using tezos but it didn't work...

## Team :busts_in_silhouette:

### Team members

- Laura Camellini 

### Contact

- **Contact Name:** Laura Camellini 
- **Contact Email:** Contact email (e.g. jeeltcraft@gmail.com)
- **Website:** www.jeeltcraft.com

### Legal Structure

- **Registered Address:** Address of your registered legal entity, via Montegrappa 89 41132 Modena Italy
- **Registered Legal Entity:** Laura Camellini VAT number IT03764030361

### Team's experience

I just finished my very first [nft marketplace interface](https://nft.varda.vision) and custom nft smart contract with rust on near, I have experience with geometry nodes to [create art](https://paras.id/token/x.paras.near::51477/51477%3A1) for the nodevember challenge and with python as you can see from my TARDIS repository (last project a time machine for the Dropbox API)
Although the varda vault unlockable content project is using the mintbase API I never applied for mintbase grants before
### Team Code Repos

- https://github.com/jilt


### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/jeeltcraft

## Development Status :open_book:
Not yet started

## Development Roadmap :nut_and_bolt:

As per the links provided in the description
Milestone 1: Addon development
- timing: 1 month
- result: downloadable links on gumroad, Serpens marketplace and mintbase/varda-vault with the python addon and a video to explain how to use it with the mintbase interface.

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Mintbase. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

### Overview

- **Total Estimated Duration:** 1 month
- **Full-Time Equivalent (FTE):** 1 FTE plus about 2 freelance "helpers"
- **Total Costs:** 10,000 USD

### Milestone 1 Development

- **Estimated duration:** 1 month
- **FTE:**  1
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 1. | License |MIT

## Future Plans

Please include here
The Varda project aims to collaborate on and create an a reliable investing and service point for high level art and nfts on the near ecosystem, the Varda vault is built on the graph in order for queries to be the main source of tokens to sustain the project, we are waiting for the graph to be available as a decentralized network for the near Blockchain in order to achieve that, meanwhile we keep building on a decentralized data model and to share tools with the near creative community.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Twitter, Luis, Nate and Caroline <3

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.
