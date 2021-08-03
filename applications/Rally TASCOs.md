# Bepro Network Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Grants Program Process](https://github.com/bepronetwork/grants-program/#pencil-process) on how to submit a proposal.

* **Project Name:** Rally TASCOs
* **Team Name:** TASCO
* **Payment Address:**  0x1BdB26fCb8eF6222F1f2Dc91A619fE8764f99CC0 ($BEPRO)


> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*


### Overview

####Summary:
The project has as ambit to develop a ludic component associated to cryptocurrencies and NFTs focusing the Portuguese culture. We have as an objective to show the latest developments in cryptocurrencies to the Portuguese population in a simple and playful way.

####Scope:
The game is called Rally TASCOs, and aims to make Portuguese culture known to the Portuguese and to give value to what we have best in Portugal, the "tascos", our traditional and modest establishments.
The game will be presented through a map and a marketplace of NFTs.
At the launch of our game we will focus on the capital of Portugal with 10 restaurants.

### Project Details

The game will work as follows:
The player registers on our website/app, receives an email for validation in the email. Once you validate your user you will receive the instructions of the game and its operation in the email through a newsletter.  
The app will display a map of the city of Lisbon with pins to locate the different restaurants.
When you click on the pin, a column will appear on the left side with the description of the place, name, 1 sentence with the restaurant's history. If it is the first time that the player opens the restaurant, a message will appear explaining how to access the specific tavern's market.
At the bottom of the menu will appear a button to import a photo (establishment + person). Once imported, the access to that tavern will be pending our validation. The button will become unavailable and a message saying that it is under validation will be displayed.
Once the photo is validated, the player will receive an email notification. The button will disappear and a new one will appear saying "enter" the tavern.
The player will be sent to a marketplace of the establishment itself. There will be a gallery of restaurant-specific NFTs to buy. And there will be a space to trade/sell/buy second hand NFTs. All NFTs will be transacted in TASCO, the game currency.  
Each establishment will have its own marketplace and unique artwork.

####Business Mechanisms
To create the desire effect and create supply, we will create some currency distribution mechanisms, so players can buy NFTs.
* 1st mechanism - After registration confirmation the player will receive % under the maximum total of 685 TASCO/day. The more players the platform has the less each user receives. The TASCO will be shared from 0.04/block, each block is mined 5/5sec (according to EWC).
* 2nd mechanism - Drawing for the first 10 players. 1 of those 10 players will receive 1 NFT of the game + airdrop.
* 3rd mechanism - we will make available 700K TASCOs to distribute through referrals. For each referral the player will receive 1 TASCO/month
These mechanisms will be implemented over time.
Other mechanisms of currency distribution / NFTs can be created as the team sees fit.
There are other mechanisms that we have in mind like having a race to the tavern, the first to go to the tavern will receive 1 prize. Or the first to go to 5/10 different taverns will receive a TASCO airdrop.

####TASCO Tokenomics
* Hard Cap 20M - never meant to be reached
* 8M - mining program
* 1M - Dev allocation & war chest
* If it turns out to be too much we just burn it or use it for more games
* 1M - distribution in register incentives (1 year)
* 2M - referral incentives (1 year)

* 5M (early stage) - Calibrated to be 4 years - Games and challenges -
When early stage is over, no more airdrops. we will focus on NFTs and create valued NFTs (create demand)
Our goal is following that the number of tokens follows the pattern of Portuguese Population after early stage is over.



### Ecosystem Fit

Help us locate your project in the Blockchain landscape and what problems it tries to solve by answering each of these questions:

* Where and how does your project fit into the ecosystem?
  NFTs marketplace - gamification 
* Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
  dapp, our own user base.
* What need(s) does your project meet? The need of having something valuable traditionally portuguese 
* Are there any other projects similar to yours in the BEPRO Network ecosystem?Apart from a NFT marketplace realfevr, but I guess is quite different from what BEPRO Network ecosystem has. 
  * If so, how is your project different? The part of gamification is completely different, and the association to the portuguese culture as well.
  * If not, are there similar projects in related ecosystems?The part of trading NFTs.

## Team :busts_in_silhouette:

### Team members

* Leader: Joao Fernandes
* Miguel Henriques
* Hugo Correia
* Andre Loureiro
* Pedro Gradissimo

### Contact

* **Contact Name:** Joao Filipe Silva Fernandes
* **Contact Email:** jofernandess@gmail.com
* **Website:** https://twic.pt/tasco/

### Legal Structure

* **Registered Address:** Rua Timor 5 1° andar, Lisboa 1170-371
* **Registered Legal Entity:** Joao Filipe Silva Fernandes

### Team's Location

* **Place of Operations:** Lyon, France
* **Place of Operations:** Lisboa, Portugal

### Team's experience

Joao Fernandes:
Novabase - applications development in Java
https://volterres.fr - Use of blockchain to trace energy assets and provide transparency to the electricity market and offers

Andre Loureiro - Senior fullstack developer

Hugo Correia - Senior Fullstack developer

### Team Code Repos

* https://github.com/jofernandess/TascoCoin
* https://github.com/andreloureiro88/tasco.api


Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

* https://github.com/jofernandess
* https://github.com/andreloureiro88
* https://github.com/hmsca



### Team LinkedIn Profiles (if available)

* https://www.linkedin.com/in/jofernandess/
* https://www.linkedin.com/in/andreloureiro1906
* https://www.linkedin.com/in/hugomscorreia

## Development Status :open_book:

Already initiated.

## Development Roadmap :nut_and_bolt:

Project Plan:

* **Estimated duration:** 33 weeks
* **FTE:** 0.15 (3 DEVs with a maximum of 5h of development per week)
* **Costs:** 4M $BEPRO

Week 1: Image & frontend website
* landing page
* Rules/game page 
* Timeline page
* About us
* Sponsors and partners
* Logo
* Slogan
* FAQs
* Contacts

2nd/3rd/4th week:
Registration - Insert users - validation of registration (BE)
Sending the newsletter with game rules (BE)
CRUD the restaurants in the DB and their coordinates and description to populate the map (BE)
admin page
CRUD restaurants
Add / remove address tokens
Map - API leaflet
Customize PIN

5th/6th/7th/8th week:
Create TASCO token (ERC20) on test network (use volta/ewc) - use bepro.network for tokenomics development
Create ERC721 NFTs on test blockchain (use volta/ewc)
Create logic for sale and 2nd hand market (BE).

9th/10th/11th/12th week:
Infrastructure setup
Security
Bug Fixing


13th/14th/15th/16th week:
Develop mechanism to distribute tokens by registration
Call smartcontract to distribute tokens
Develop mechanism to distribute tokens by referral
Call smartcontract to distribute tokens
Develop mechanism to distribute tokens to first 10 users
Call smartcontract manual from admin page
Develop images for NFTs for each restaurant (10 restaurants - 5 NFTs/restaurant) - associate with IPFS


17th/18th/19th/20th week:
Create image submission feature
Create image submission form
Create tavern page
Criar pagina do tasco
Create marketplace feature
Blockchain API connection
FE - NFTs gallery
Develop FE marketplace with dummy images associated with each restaurant (gallery)
FE - 2nd hand marketplace
Sell page
Buy page
Overall marketplace (show all NFTs) (to decide)

21st/22nd/23rd/24th week:
Create user page (FE) - show NFTs and associated tokens
Create image submission functionality (BE/FE)
Add images pending validation to Admin page
Trigger email on image approval / disapproval
Update image submission status


25th/26th/27th/28th: Application testing
29th/30th/31st/32nd: Pre Live
Teaser
Community engagement

33rd : Live :
Create countdown to make NFTs available (2 days in roman numbers but with double the speed)
Create countdown to make 1st coin distribution mechanism available (2 days in hexadecimal with half the speed)
Create countdown to make 2nd referral mechanism available (3 days otherwise)


## Future Plans

Please include here

* 29th/30th/31st/32nd: Pre Live
  Teaser
  Community engagement

* 33rd : Live :
  - Create countdown to make NFTs available (2 days in roman numbers but with double the speed)
  - Create countdown to make 1st coin distribution mechanism available (2 days in hexadecimal with half the speed)
  - Create countdown to make 2nd referral mechanism available (3 days otherwise)

* The goal is to continue to explore the portuguese culture apart from restaurants.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?**  Twitter


