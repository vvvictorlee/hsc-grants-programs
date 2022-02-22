***For security issues related to cryptocurrencies and their components ONLY:***

If you have found a security issue that directly affects a cryptocurrency and/or its components (e.g. blockchain, node, wallet), please ensure that you report it directly to the program.

**Non-security related issues:**

To report an issue without security impact, please open a support chat at [https://www.hoosmartchain.com/en/support](https://www.hoosmartchain.com/en/support) (chat icon is located at the bottom right of the page). Thank you for your efforts in helping keep HSC and its users safe!


---


**About:**

HSC is the number one cryptocurrency exchange, operating in many places throughout the world. Specializing in crypto-to-crypto transactions, we provide access to hundreds of digital currency pairs. As a leading exchange platform, we prioritize security, liquidity, and speed, while maintaining some of the lowest fees in the industry. We strive to give our users the best experience possible, also providing access to some of the latest blockchain/DLT technologies available, with new cryptocurrencies being listed frequently.

HSC stands for “Binary Finance”, integrating digital technology with finance. Just as the name suggests, we are digital currency enthusiasts, with more than 20 years of combined finance, security, and development experience at top exchange platforms and companies including the Tokyo Stock Exchange, Morgan Stanley, Accenture, and other Top 100 companies from all over the world.

**Policy:**

At HSC, the security of our users is our number one priority. As such, we strive to provide the most secure platform possible. We will evaluate reported security issues based on the security impact to our users and the HSC ecosystem.

This bounty brief describes the rules of the HSC bug bounty program, as well as the eligibility of vulnerabilities and the rewards.


---


**Rewards/Ratings:**

This program takes reference from the [Bugcrowd Vulnerability Rating Taxonomy](https://bugcrowd.com/vulnerability-rating-taxonomy) for the prioritization/rating of findings. Prioritization/ratings may vary from the Bugcrowd Vulnerability Rating Taxonomy.

**Rewards will be paid out in*****USDT***.

Once your submission is accepted, please provide either of the following to receive your reward.

·       email address registered on HSC

·       your BUSD wallet address

We suggest researchers create a separate private HSC account, or a HSC Smart Chain wallet.

*Prices will change with the cryptocurrency markets and the dollar amount listed below could change.

***Please note that only vulnerabilities with a working proof of concept that shows how it can be exploited will be considered eligible for monetary rewards. Determination of whether a reported issue sufficiently meets the bar for monetary rewards is done at HSC's discretion.***

**HSC is eager to work with the community to make sure that every researcher's finding is rewarded fairly - based on the vulnerability's impact on business and overall severity. To this end, it is possible that extraordinarily severe issues or those with extreme impact may be rewarded up to $100,000.*

*HSC may award an additional reward bonus for exceptional reports. This will be done at HSC's discretion .*

**Scope and rewards**

**In scope targets**

**In scope**

Payment reward chart

$10000

**P1**

$500 – $1000

**P2**

$150 – $500

**P3**

$60 – $150

**P4**

$20 – $60



**Out of scope targets**

**Out of scope**

|support.hoosmartchain.*|·       Website Testing|    |
|:----|:----|:----|
|community.hoosmartchain.org|·       Website Testing|    |
|*.trustwallet.com|    |    |
|*.trustwalletapp.com|    |    |

*Any domain/property of HSC not listed in the targets section is out of scope.*

**Target Information:**

**HSC**

Primary Targets - Eligible for bounty from P4 and above

*.hoosmartchain.com (with exceptions, refer to Secondary Targets)

api.hoosmartchain.com

hoosmartchain.us

*.hoosmartchain.org

*dex.hoosmartchain.org

HSC Chain

HSC Chain Documentation

HSC Chain Github repositories in scope

HSC Chain Wallet - Chrome and Firefox extensions

HSC Smart Chain

HSC Smart Chain Github repositories in scope

HSC Mobile Application for Android

HSC Mobile Application for iOS

HSC Desktop Application

HSC macOS Application

Secondary Targets - Eligible for bounty for P1 and P2. P3 and P4 will be points only

academy.hoosmartchain.com

info.hoosmartchain.com

hoosmartchain.sg

 

**For Bugs Affecting Multiple HSC Exchanges**

If an issue reported for one of our exchanges (e.g. hoosmartchain.com) affects any of our other exchanges (e.g. hoosmartchain.je), and shares the same root cause, it will be treated as a single issue. Please do not report the same exact bug multiple times.

**HSC resources**

*Windows* : [Here](https://ftp.hoosmartchain.com/electron-desktop/windows/production/hoosmartchain-setup.exe)

*macOS* : [Here](https://ftp.hoosmartchain.com/electron-desktop/mac/production/hoosmartchain.dmg)

*iOS* : [Here](https://apps.apple.com/us/app/hoosmartchain/id1436799971?l=en)

*Android* : [Here](https://play.google.com/store/apps/details?id=com.hoosmartchain.dev&hl=en)

*API Documentation* : [Here](https://github.com/hoosmartchain-exchange/hoosmartchain-official-api-docs)

**HSC Chain & Smart Chain and DEX resources**

*HSC Chain Documentation* : [Here](https://hoosmartchain-chain.github.io/)

*HSC Chain Wallet - Chrome extension*: [Here](https://chrome.google.com/webstore/detail/hoosmartchain-chain-wallet/fhbohimaelbohpjbbldcngcnapndodjp)

*HSC Chain Wallet - Firefox extension*: [Here](https://addons.mozilla.org/en-US/firefox/addon/hoosmartchain-chain/)


---


**HSC Chain & Smart Chain Vulnerability Classifications**

**P1:**

·       Vulnerabilities that could undermine the safety of any user or validator's fund/fee

·       Subversion of the DEX trading logic

·       Vulnerabilities that could severely undermine trading or token economy

·       Remote Code Execution on any HSC Chain/Smart Chain node, such as Validator nodes, Witness nodes, or Seed nodes

·       Vulnerabilities related to key generation, encryption, decryption, signing and verification

·       Vulnerabilities that could disrupt the HSC Chain governance

·       Remote leaks of unencrypted private keys / mnemonic / key seed

·       Transaction origin spoofing or transaction malleability

·       Merkle proof validation vulnerabilities

·       Validator selection set manipulation

**P2:**

·       Denial of service of any HSC Chain validator node

·       Vulnerabilities that could undermine or disrupt trading or token economy

·       Vulnerabilities that could disrupt the Validator consensus result and performance

·       Vulnerabilities that could cause the [Accelerated Node](https://hoosmartchain-chain.github.io/blockchain.html#what-is-an-accelerated-node) to be unable to respond with user queries on orders, transactions, balances, market depth

·       Access of disabled channels for cross chain communication

·       Denial of service of cross chain communication

**P3:**

·       Denial of service of Web Wallet usage

·       Denial of service of the HSC Chain & Smart Chain Explorer

·       Denial of service of seed and/or data seed nodes.

·       Denial of service for BSC Relayers / Oracle Relayers

**P4:**

·       Vulnerabilities that could affect the stability or availability of HSC Chain / DEX / Explorer

·       Vulnerabilities that could affect the stability or availability of the Web Wallet

**For non-security related issues, you can ask questions and give feedback**[here](https://community.hoosmartchain.org/)**.**


---


**HSC Chain & Smart Chain Github Vulnerability Classifications**

**In Scope:**

[https://github.com/hoosmartchain-chain/tss-lib](https://github.com/hoosmartchain-chain/tss-lib)

[https://github.com/hoosmartchain-chain/bep3-smartcontracts](https://github.com/hoosmartchain-chain/bep3-smartcontracts)

[https://github.com/hoosmartchain-chain/bep3-deputy](https://github.com/hoosmartchain-chain/bep3-deputy)

[https://github.com/hoosmartchain-chain/ledger-app-hoosmartchain](https://github.com/hoosmartchain-chain/ledger-app-hoosmartchain)

[https://github.com/hoosmartchain-chain/hsc-genesis-contract](https://github.com/hoosmartchain-chain/hsc-genesis-contract)

[https://github.com/hoosmartchain-chain/hsc-relayer](https://github.com/hoosmartchain-chain/hsc-relayer)

[https://github.com/hoosmartchain-chain/oracle-relayer](https://github.com/hoosmartchain-chain/oracle-relayer)

[https://github.com/hoosmartchain-chain/hsc](https://github.com/hoosmartchain-chain/hsc)

**P1:**

Vulnerabilities that could undermine the fund safety of any user or business runner, including:

·       Vulnerabilities that could expose private keys or any other sensitive secrets

·       vulnerabilities that could allow unfair trading, swapping, exchange, or any economic practice that results in loss of funds

·       Vulnerabilities impacting the system, human governance or judgement that could cause significant economic unfairness or loss of funds

**P2:**

·       Vulnerabilities with similar impact as P1 vulnerabilities, but are dependent on specific prerequisites

**P3:**

·       Denial of service of critical functions

**P4:**

·       Denial of service of non-critical functions


---


**Trustwallet Vulnerability Classifications**

**In scope:**

[Trustwallet Android app](https://play.google.com/store/apps/details?id=com.wallet.crypto.trustapp)

[Trustwallet iOS app](https://apps.apple.com/app/trust-ethereum-wallet/id1288339409)

[Trustwallet walletcore](https://github.com/trustwallet/wallet-core/)

**Out of scope:**

*.trustwallet.com

*.trustwalletapp.com

**Examples of issues that we are looking for:**

·       Vulnerabilities that can cause a loss of user funds/assets remotely

·       Vulnerabilities that can cause exposure of private keys or mnemonic seed phrase remotely

·       Vulnerabilities in chain-related implementations

·       Denial of service of the wallet app

·       Remote code execution

·       Insecure cryptographic implementation for sensitive functions such as wallet generation, transaction signing etc.

·       Lock screen bypass

**Ineligible issues:**

·       Vulnerabilities that require root/jailbreak to exploit (points only if a change is made)

·       3rd party library dependencies

·       Address bar spoofing in dapp browser

·       Web vulnerabilities for *.trustwallet.com and *.trustwalletapp.com

·       Issues related to TWT referral


---


**Access:**

Researchers are encouraged to self-provision accounts as needed; when doing so, please sign up for an account using your @bugcrowdninja.com email address. For more info regarding @bugcrowdninja email addresses, see [here](https://researcherdocs.bugcrowd.com/v2.0/docs/your-bugcrowdninja-email-address).


---


**Actions to avoid:**

·       Testing on accounts other than those that you own

·       Automated testing using tools such as scanners

·       Excessive request attempts that affects the availability of our services to all users

·       Destruction of data


---


**Ineligible issues (Will be closed as out of scope):**

·       Theoretical vulnerabilities without actual proof of concept

·       Email verification deficiencies, expiration of password reset links, and password complexity policies

·       Invalid or missing SPF (Sender Policy Framework) records (incomplete or missing SPF/DKIM/DMARC)

·       Clickjacking/UI redressing with minimal security impact

·       Email or mobile enumeration (E.g. the ability to identify emails via password reset)

·       Information disclosure with minimal security impact (E.g. stack traces, path disclosure, directory listings, logs)

·       Internally known issues, duplicate issues, or issues which have already been made public

·       Tab-nabbing

·       Self-XSS

·       Vulnerabilities only exploitable on out-of-date browsers or platforms

·       Vulnerabilities related to auto-fill web forms

·       Use of known vulnerable libraries without actual proof of concept

·       Lack of security flags in cookies

·       Issues related to unsafe SSL/TLS cipher suites or protocol version

·       Content spoofing

·       Cache-control related issues

·       Exposure of internal IP address or domains

·       Missing security headers that do not lead to direct exploitation

·       CSRF with negligible security impact (E.g. adding to favourites, adding to cart, suhscribing to a non critical feature)

·       Vulnerabilities that require root/jailbreak

·       Vulnerabilities that require physical access to a user's device

·       Issues that have no security impact (E.g. Failure to load a web page)

·       Assets that do not belong to HSC

·       Any activity (like DoS/DDoS) that disrupts our services

·       Installation Path Permissions

·       Reports from automated tools or scans

·       Links to invalid/expired pages (Only valid if you can demonstrate an actual takeover of an official HSC social media account linked to on every page, not just specific past announcements/blog posts)

 

