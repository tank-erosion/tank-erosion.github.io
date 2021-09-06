---
layout: default
---

### Further Considerations

**Spending order of operations**
With the recommended setup, there are various ways to send a transaction, some are more secure, some are more accessible. This should be the priority:
* Primary use- use retained keys and one of your signatories to sign a transaction
* Secondary- destruction of one or more keys requires accessing metal backups to regenerate hardware devices to sign a transaction
* Tertiary- you are unavailable to to death, imprisonment, or health catastrophe and the inheritance plan is put into place with signatories only
* Worst case/FUBAR- you are unavailable and signatories cannot fulfill duties. This is an edge case that may be solvable with a dead man's switch like [Final Message](https://finalmessage.io/). Details on how to implement in this plan are TBD.

**Bonus**
* Mentioned previously, read the [privacy wiki](https://en.bitcoin.it/wiki/Privacy) to understand implications of using the Bitcoin network privately and storing perverted UTXOs long term.
* Sparrow wallet allows for multiple methods of connecting to your own Bitcoin node. Consider this if not already doing so. 
* Sever the link between you and your coin with coinjoin.
* Only obtain KYC free bitcoin with <a target="_blank" rel="noopener noreferrer" href="https://bisq.network/">Bisq</a> or other peer-to-peer platforms with privacy best practices.
* Generating entropy on your own. Do this for at least one of your signers. This can be done with <a target="_blank" rel="noopener noreferrer" href="https://seedpicker.net/guide/GUIDE.html">Seed Picker</a>, <a target="_blank" rel="noopener noreferrer" href="https://seedsigner.com/">Seedsigner</a> or <a target="_blank" rel="noopener noreferrer" href="https://github.com/cryptoadvance/specter-diy">Spector DIY</a>.

**Miscellaneous Commentary**
A note on perversion and treason. In order for a quorum (3 signatories) to send transactions, they need the wallet file (or public keys and descriptors) for the entire fellowship (5 signatories). This gives them the ability to  at least create a watch-only wallet (committing perversion) or collude with others to steal funds (commit treason). IT IS NOT RECOMMENDED TO hinder this access unless you feel that you cannot trust your entire fellowship. If selecting new signatories is not an option, you can add control access to the wallet via a password or withold the descriptor data. This adds a significant level of complexity that can bork the entire operation (increases fragility). Some have discussed putting descriptor or wallet password data in a dead man's switch (like finalmessage.io or a gmail message), but if you choose to do this, consider adding redundancy with multiple switches or adding attorneys/trustees.

It's important to have a backup to your seeds that you can access without help from your trustees, but it's also not worth the complexity to split up (you've already done this with your trustees), turn into a <a target="_blank" rel="noopener noreferrer" href="https://blog.keys.casa/shamirs-secret-sharing-security-shortcomings/">shamir secret</a>, or otherwise complicate access to it for yourself. There are numerous other methods that would seemingly increase security beyond the recommendations in this guide, but the concept of diminishing returns is apparent in that very little additional security is gained at the risk of increased fragility and likelihood that all access to funds is lost. Adequate security is accomplished with backups separated in multiple locations, with a single passphrase that is separate from all seeds.

A short and easy-to-remember passphrase is preferred to a high-entropy, computer generated passphrase. A passphrase is not limited to the 2048 BIP39 word list that is used for the seed phrases, it can be anything. Some believe these should be very long and/or random characters generated by a password manager. Some hardware devices allow this to be entered on the device or the computer it's connected to. This is generally not recommended due to the risk of a computer having a key logger. Some devices allow the passphrase to remain on the device under a different pin, this is not recommended as information kept on hardware devices has been extracted.  This is the same reason you wouldn't want to use the passphrase with the software key. Therfore, we are left with entering it on a hardware device every time you use that device. With this being the case, it's reasonable to stick with a single, easy to remember word in lieu of random generated characters.

[Main](../index.md)<br />
Previous [Setup](setup.md)<br />
Next [Template for Signatories](instructions_template.md)