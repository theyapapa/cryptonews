# BitPay’s Copay Wallet Compromised by Malicious Code, Firm Issues Advice for Users ...

###### 2018-11-27 07:11

Crypto payment processor BitPay issued advice on its official blog yesterday, Nov. 26, for users of its open-source Bitcoin (BTC) wallet Copay, which has reportedly been compromised by malicious code.

The vulnerability pertains to a third-party Node.js module, also known as an “event stream,” which is used in versions 5.0.2 through 5.1.0 of BitPay’s Copay and BitPay apps.

BitPay’s post states that the BitPay app was not vulnerable to the malicious code, but that its team is investigating whether the vulnerability had been exploited against any CoPay users.

In the meantime, the company has outlined advice for its users, stating that anyone using Copay version from 5.0.2 to 5.1.0, “should not run or open the app.”

The company also warns that users of affected versions “should assume” their private keys may have been compromised, and therefore move any holdings to new, secure v5.2.0 wallets “immediately”:

“Users should not attempt to move funds to new wallets by importing affected wallets' twelve word backup phrases (which correspond to potentially compromised private keys).

Users should first update their affected wallets (5.0.2-5.1.0) and then send all funds from affected wallets to a brand new wallet on version 5.2.0, using the Send Max feature to initiate transactions of all funds.”

According to the GitHub issue report, a little-known user called right9ctrl requested and was granted publishing rights to the event-stream library (which is used in the Node.js module on the Copay app) from its previous maintainer, Dominic Tarr, who conceded he was no longer maintaining the repository and did not suspect the new user of malintent.

[Original source](https://cointelegraph.com/news/bitpays-copay-wallet-compromised-by-malicious-code-firm-issues-advice-for-users)

![stats](https://c.statcounter.com/11760860/0/a89fa40b/1/ "stats")