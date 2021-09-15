---
layout: default
---

### Further Considerations

**Spending order of operations**
With the recommended setup, there are various ways to send a transaction, some are more secure, some are more accessible. This should be the priority:
* Primary use- use retained keys and one of your signatories' hardware devices or software key to sign a transaction
* Secondary- destruction of one or more keys requires accessing metal backups to regenerate hardware devices to sign a transaction
* Tertiary- you are unavailable to to death, imprisonment, or health catastrophe and the inheritance plan is put into place with signatories only
* Worst case/FUBAR- you are unavailable and signatories cannot fulfill duties. This is an edge case that may be solvable with a dead man's switch like <a target="_blank" rel="noopener noreferrer" href="https://finalmessage.io/">Final Message</a>, encrypted files, shamir secret sharing, etc. These are outside the scope of this guide, for now.

**Bonus**
* Mentioned previously, read the <a target="_blank" rel="noopener noreferrer" href="https://en.bitcoin.it/wiki/Privacy">privacy wiki</a> to understand implications of using the Bitcoin network privately and storing perverted UTXOs long term.
* Sparrow wallet allows for multiple methods of connecting to your own Bitcoin node. Consider this if not already doing so. 
* Sever the link between you and your coin with coinjoin.
* Only obtain KYC free bitcoin with <a target="_blank" rel="noopener noreferrer" href="https://bisq.network/">Bisq</a> or other peer-to-peer platforms with privacy best practices.
* Generating entropy on your own. Do this for at least one of your signers. This can be done with a source of entropy like dice (I used 11 coins), and an airgapped computer using <a target="_blank" rel="noopener noreferrer" href="https://twitter.com/parman_the">Arman</a> the Parman's <a target="_blank" rel="noopener noreferrer" href="https://armantheparman.com/bitcoin-seed-with-dice/">guide</a>, and verified with <a target="_blank" rel="noopener noreferrer" href="https://seedpicker.net/guide/GUIDE.html">Seed Picker</a>, <a target="_blank" rel="noopener noreferrer" href="https://seedsigner.com/">Seedsigner</a> or <a target="_blank" rel="noopener noreferrer" href="https://github.com/cryptoadvance/specter-diy">Spector DIY</a>.

**Miscellaneous Commentary**
A note on perversion and treason. In order for a quorum (3 signatories) to send transactions, they need the wallet file (or public keys and descriptors) for the entire fellowship (5 signatories). This gives them the ability to  at least create a watch-only wallet (committing perversion) or collude with others to steal funds (commit treason). IT IS NOT RECOMMENDED TO hinder this access unless you feel that you cannot trust your entire fellowship. If selecting new signatories is not an option, you can add control access to the wallet via a password or withold the descriptor data. This adds a significant level of complexity that can bork the entire operation (increases fragility). Some have discussed putting descriptor or wallet password data in a dead man's switch (like finalmessage.io or a gmail message), but if you choose to do this, consider adding redundancy with multiple switches or adding attorneys/trustees.

You might consider having a backup of your seeds that you can access without help from your trustees, such as with a shamir secret or encrypted file. If you chose to do this, do not keep such information at home, work, or any other location you have daily access to. This will help mitigate some risk against physical threats (the $5 wrench attack).

Some devices allow you to type your seed phrase on your computer, which has a full keyboard. This undermines the security assurances of using a hardware device and is not recommended. Only type your seed phrase on the device it self.

[Main](../index.md)<br />
Previous [Setup](setup.md)<br />
Next [Template for Signatories](instructions_template.md)
