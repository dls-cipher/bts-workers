 ---
language: en
layout: worker
type: budget
bfid: 2018-09-bitshares-website-development-management
workerid: not created yet
title: BitShares.org - Website Development, Content/Domain Management, Hosting 
name: Milos Preocanin
company:
 name: Zavod Premik
 url: http://move-institute.si
status: draft
discussions:
 - name: bitsharestalk
   url: ""
price: 88,780.00 USD
price_division:
    fixed: 7,180.00 USD
    variable: 81,600.00 USD
duration: 13 months
start: 2018/09/10
end: 2019/10/11

---

# **Introduction**

Earlier this year, Cryptonomex and its President and Director, signed agreement with new appointed care-taker AP Asia Tech Co., LTD. Included in that agreement was handling the domain
and its related services, make-up and polishing of new website and its content done by Richard Castro, and proper SEO services. Once AP Asia Tech Co., LTD was warned for non-profit status
requirement for the owner of the domain, Milos Preocanin (DL) called his non-profit partner "Zavod Premik" from Slovenia (based on partnership agreement from 2017) and moved ownership to non-profit status. 

# **Review of work done from March 2018 till September 2018**

- New CloudFlare Premium DNS Service
- New website with clean and corporate look available at http://demo.bitshares.org
- Responsive/Mobile ready (few css improvements/cleanups to be done)
- 14 New pages with Content aligned by current/ongoing Core team publications/updates and new Whitepaper by BitShares Blockchain Foundation
- BTS Price ticker from CoinMarketCap
- Blocktivity.info table fully integrated through api (using php 'include' to avoid err printing on site) - Courtesy/Collaboration of Estefan
- Acquired list of legal requirements for having DEX being hosted/operated in Slovenia (see ref. document #worker-website-dex-legal)
- Legal check of content for bitshares.org
- Content SEO optimizations (targeted keywords, titles, metas, descriptions, headings, sitemap, etc.)
- Hosting SEO preparations/optimization - bitshares.org ONLY
- New BitShares GitHub repository for bitshares.org (where the future development will be available and current staging and production website)
- Email server with SPF record and SSL (Shared) protection - currently hosted with apasia.tech
- Separation of header and footer with php in order to get content updates less complicated
- Load Balancer main node (shared root between collaborators) with 3 nodes behind (Entire setup by APT - Asia, EU, USA) - "Zavod Premik" would be holding root to the USA, Bitshares Blockchain Foundation would be offered with EU, and Abit/Ryan C. Fox would be offered to hold keys to Asia (Truly decentralized).
- DNS login restrictions are split to email and 2FA access, w
- New 'Website Terms of Agreement' and 'Content Restrictions' (Telegram groups removal from Contacts due to branding/reputation issues and number of the groups until proper worker for support is built, removal of the terms DEX from keyword and indexing, 

# **Worker Intent**

As seen from the demo, website is still missing content for DEX/Token Factory as Native dApps, CDN optimizations, proper code optimizations, CSS optimizations, and as any other website it will always have "room for improvements". 
Eco-system learned by now, that unmanaged website/domain can be very very damaging - re Brand, Marketing and Reputation (e.g. BitShares is not a DEX, BitShares is a Blockchain/Technology). After detailes analysis, reviews, legal advisory, 
opinions from other participants in our eco-system and some personal experience, we've selected a team of people that will for the following 12 months dedicate their best hours and skills to constantly keep improving bitshares.org in every possible way. 
The website and domain/hosting would be having General Roadmap for 12 months, with every 3 month presentations/review.

## **Online spotlights for the project**

1. https://github.com/BitShares/bitshares.org - New Website Repo
2. http://demo.bitshares.org - Live Demo
3. http://demo1.apasia.tech - Staging Demo

## **Budget**

Worker is divided between on-going/monthly 'fees' and fixed 'costs', it has pre-calculated lenght of 13 months against actual duration of 12 months of work, where 'costs' would be counted as one fixed month of payment. 

### **Team Positions and Hourly Rates - 'fees'**

| Name / Position              | Hourly Rate (bitUSD) |
| ---------------------------------- | -------------:|
| Milos Preocanin - Project Manager |   $100.00     |
| Richard Castro - Web Developer	         |   $120.00     |
| Alex Megalokonomos - CSS/JS Review/Opt      |    $120.00     |
| Ross Walker - Content Manager 	         |    $75.00     |
| Ryan C. Fox - Core/Content Liason     |	  $75.00     |
| Sigve Kvalsvik - DNS/Auth Manager      |    $50.00    |
| **GitHub Issue Bounties**               |   $30.00 - $125.00     |

- *Maximum budget per month is $6800.00 - This amount of monthly fees was calculated as worst-case scenario where complete re-design would be involved in that month (as example of scope of work needed for it)*
- *Escrow fee would be deducted/charged as **fixed** @8% x *(~6800) from monthly invoices issued to the escrow partner*
- *TopTracker will be used for tracking hours and tasks of each member of the team.*
- *For the GitHub Bounties, participants will be requested to do initial ETA on task/issue or to register/use TopTracker account within team.*

### **One time payments - 'costs'**

| Description        | Price (bitUSD) |
| ---------------------------------- | -------------:|
| 1-Time Reimbursement Fee |   $5,000.00     |
| 4 Positive(Comodo) Premium SSL Certificate / 12 months    |   $60.00     |
| CDN by StackPath / rough estimate for 12 months    |	 $320.00     |
| Website Balanced Hosting (1+3) with DDOS / 12 months    |    $1440.00     |
| E-mail Server (CentOS 6 x64) /w DirectAdmin |    $360.00     |
| **TOTAL**     |	  $7,180.00     |

### **1/4 3 Months General Roadmap**

- Finishing 2/3 native dApps pages
- Moving/Setting up emails to the new server
- Innovative hosting solution for bitshares.org (see ref. document #worker-website-hosting)
- Purchase/Deploy of SINGLE Premium SSL Certificate for bitshares.org
- Enabling status.bitshares.org as monitoring service for the nodes listed in wallet.bitshares.org
- Achieving double "A" Score on GTMetrix (Google PageSpeed and YahooSlow) for bitshares.org
- Achieving 88%+ on SEOSITECHECKUP for bitshares.org
- DNS updates for the premium domain requirements
- "Wallet Creation" being replaced with term "Account Creation" and incorporated to the website bitshares.org instead of sending users only to DEX
- PHP polishing (wrapping header/footer includes through all pages)
- Total of 27 files to be cleaned/organized (css, php, js, html)
- Improving on blocktivity.info table
- Integration of Ticketing system (new/separate worker) with various business departments as replacement to emails on contact page
- CDN (StackPath - ex MAXCDN) integration
- OPCache + Redis server deployment/configuration (80% of content we serve is static)
- Anti-Spam/Crawl for both website/emails
- Proper Google Analytics integration with monthly reporting/suggestions for improvements/potential marketing campaing opportunities
- Blog/News Updates/CMS - Newest from the eco-system similar to current "State-of-the-network"
- Proper/Legally OK structure to native dApps within the website bitshares.org - linking between main website and its native dApps

*General Roadmap is subject to constant changes and interraction of the team of this worker. 

## **Legal Disclaimer**

- "Zavod Premik" as legal representative and owner of the domain bitshares.org will continue respectfully to update and manage bitshares.org and it
- Any suggestion/request from stake-holders/proxies (regardless of their stake/weight), if doesn't meet legal requirements/limits in Slovenia will be sanctioned/ignored and legal substitute/solution will be resolved through other stake-holders and legal representatives.
- Milos Preocanin, as person having Power of Authority on behalf of "Zavod Premik" will be held as main/responsible contact for this worker.
- "Zavod Premik" will uphold agreement with the blockchain for 12 months, giving warranty on current structure/intent as CONSISTENT and fully transparent to the stake-holders and BitShares Ecosystem. 


<hr>


**NOTICE/ADVERTISEMENT:**

- This worker will constantly produce issues at it's corresponding repository on GitHub
*If you are from within the ecosystem, or completely random person and you are interested, for submissions please contact Worker Manager by Telegram (@murda_ra) or by discussion thread of this worker in BitSharestalk.org or directly by commenting referring issue on the GitHub
