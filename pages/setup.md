---
layout: default
---

### The Setup

Use a Bitcoin wallet application like <a target="_blank" rel="noopener noreferrer" href="https://sparrowwallet.com/">Sparrow Wallet</a> to create a 3-of-5 multisig wallet with at least three hardware devices from different manufacturers. Do not add any passphrases (aka a 13th or 25th seed word). Consider using at least one fully airgapped hardware device. Feel free to use more hardware devices and more airgaps. Backup all seed phrases in metal (see **Backup** below).  [Consider linking to HWW guides on youtube/twitter]

You will need to export 6-x versions of the Sparrow Wallet file, where x is the number of hardware devices you used in your setup (i.e. three versions for three devices). One version will contain all descriptors but not any seed phrases, and will be given with each of the hardware devices. The others will contain a single seed phrase and all remaining descriptors, acting as a software signing key. One hardware device should be retained with one of the wallet files that also contains a seed phrase. This will leave you with exactly two keys for signing transactions (one short of a quorum). 

Assign four trustees to act as signatories and complete your fellowship. Draft a <a target="_blank" rel="noopener noreferrer" href="instructions_template">brief letter</a> explaining what they are to do and in what circumstances. Each signatory will receive a copy of this letter, a metal seed phrase backup, and either a hardware device with a wallet file or a wallet file containing a seed phrase (aka a software signing key). Note that one of the "software" keys will be held by both you and a signatory, so if you decide to send a transaction and need a third signatory you cannot select that individual. 

### Backup

Purchase a metal seed backup solution (such as one of the higher rated items <a target="_blank" rel="noopener noreferrer" href="https://jlopp.github.io/metal-bitcoin-storage-reviews/">here</a> for each of your 5 seed phrases. You can also <a target="_blank" rel="noopener noreferrer" href="https://www.econoalchemist.com/post/backup">create your own</a>. Be careful to give a specific label for each one that lets you know which seed it belongs to.  Note that the DIY method of using washers also requires numbering them to ensure proper order in case they are mixed somehow.  The metal backups should be given with the corresponding hardware device or software key to one of your signatories, preferably in<a target="_blank" rel="noopener noreferrer" href="https://twitter.com/nvk/status/1389641589878886407?s=20">different geographic locations</a>. The primary use of the metal backups is for the irrevocable loss of a wallet file or a hardware device, so it can be remade.

### Initialization and Maintenance

**Initialization**
After completing the above it's worth testing the wallet with a small amount of Bitcoin.  After giving the wallet file, instructions, and signing key to each of your signatories, send a small amount of funds to the wallet. Create a transaction to send those funds back to another wallet you control and sign it with the two keys you kept. Then go to each of your signatories to obtain a third signature (you do not need to broadcast until the final signatory). After having them sign the transaction, clear the seed from the hardware device (do this to your retained device as well). Once this is completed with each signatory, send another small amount of Bitcoin to the wallet. Use the metal backups to regenerate all hardware devices. Do another round of test signatures. If this is successful, initialization is complete.

**Maintenance**
At least annually, but possibly more frequent, test signing transactions with each signatory. Separately, check your metal backups to ensure they are still intact, <a target="_blank" rel="noopener noreferrer" href="https://seedsigner.com/">Seedsigner</a> and <a target="_blank" rel="noopener noreferrer" href="https://github.com/cryptoadvance/specter-diy">Spector DIY</a> devices are great for testing seeds remotely, without a computer, and disconnected from the internet. Set calendar reminders for this, if necessary. Or, use <a target="_blank" rel="noopener noreferrer" href="https://finalmessage.io/">Final Message</a> to send yourself an annual maintenance itinerary.

[Main](../index.md)<br />
Previous [Terminology](terminology.md)<br />
Next [Further Considerations](considerations.md)
