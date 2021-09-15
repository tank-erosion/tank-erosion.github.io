---
layout: default
---

### Justifications

The <a target="_blank" rel="noopener noreferrer" href="https://bitcoin.org/bitcoin.pdf">Bitcoin white paper</a> emphazises self-empowerment and self-reliance by removing trusted third parties. Estate lawyers may be necessary to act on your behalf when automation isn't possible but the Bitcoin protocol, and open-source projects that build on it allow for full control of inheritance. With best practices, the effort and stress on our loved ones can be reduced by orders of magnitude.  Still, they shouldn't be in a position to send any transactions prior to that.  

Every "why?" below has a single short answer: it optimizes security, privacy, fragility, simplicity. The longer answers are really explaining "how is this accomplished?"

**Why multisig?** Multisig allows some room for failure, specifically compromised keys (e.g. malicious hardware manufacturers or software developers, untrustworthy trustees) and lost keys. Once it's set up, it's fairly easy to use. <a target="_blank" rel="noopener noreferrer" href="https://btcguide.github.io/why-multisig">Michael Flaxman's 10x guide</a> explains this well.

**Why 3-of-5?** 1) Risk balance 2) Reasonable security guarantees 3) Diminishing returns. 
* Risk Balance. In a choosing a quorum, you are balancing the risk of malice with risk of loss. If you believed your chosen fellowship is very likely to work together to steal from you, you could go for 4-of-5, but then losing access to funds due to two deaths is much more likely and you should really find more trustworthy signatories. If you suspect the hardware devices will break or be lost you might try 2-of-5, but then collusion is easier and you're exposing your private info to more people for less benefit. You're better off just doing an annual test to ensure devices are secure (as well as retaining the seed phrases stamped in metal described in the [setup](setup.md) section). In summary, an odd number N of trustees with a quorum of (N+1)/2 balances these risks well. 

* Security. a 2-of-3 setup would require two treasonous signatories, two colluding developer groups, or two lost/destroyed keys for a catastrophic failure.  This is likely a low risk, but three is exponentially more unlikely and adds a reasonable mount of trust/complexity (see diminishing returns).

* Diminishing returns. A 2-of-3 multisig wallet allows for one malicious trustee without risking theft or one lost seed without losing access to funds. A 3-of-5 allows for up to two of either. I.e. you get double the security for only 66% more trustees (66% more trust). Yet the next doubling of security is a 5-of-9 setup which requires 80% more trust than a 3-of-5. In short, by increasing your fellowship size and quorum threshold, your trust grows faster than security.  This is an example of "diminishing returns" and doesn't even take into account the effect of complexity on the fragility of your inheritance plan. An incremental effort in a particular direction might not get you an equal amount of value.  For a multisig setup, it's better to opt for simplicity over complexity and diversify your approach. I'd rather have a 3-of-5 with multiple hardware devices than an 8-of-15 setup.  Please note that this is fairly subjective.

**Why three hardware devices (or hardware wallets or signers etc)?** To achieve the security guarantees explained above, you must diversify your trust.  If you use a single hardware device but keep a 3-of-5 setup, then you are trusting either the wallet software or the hardware device to secure a quorum of your keys.  This should be avoided. Four devices is better as you can reduce trust in each to a single key. If you can't afford more than two hardware devices, then a 2-of-3 setup may be preferred.

**Why retain two keys instead of three, or all five and still give a copy to each trustee?** Keeping one fewer keys than is needed for a quorum means you can't send funds without working with one of your trustees. This helps prevent a <a target="_blank" rel="noopener noreferrer" href="https://xkcd.com/538/">$5 wrench attack</a>, disincentivizes regular withdrawals from your cold storage, and allows the opportunity to test the effectiveness of a particular trustee when you do decide to send funds. You will still be able to *send* funds to your wallet.

**Why not use a passphrase?** Passphrases can serve multiple purposes, such as single signature hardware device security and decoy wallets. These are not a concern for a multisig cold storage setup with signing keys in separate locations.

**Why a mutliple wallet files?** Setting up three or four different wallet files and keeping track of them seems unnecessarily difficult and can lead to confusion, but the alternative is to give public keys and descriptors.  Not only are these less user friendly, it places more difficulty on the signatory, in my opinion. If your signatories are at all less technical or Bitcoin-savvy than you are, it's worth putting tin the extra time so they only have to deal with a wallet file, instructions, and a hardware device.

[Main](../index.md)<br />
Previous [Too long, didn't read](tldr.md)<br />
Next [Terminology](terminology.md)
