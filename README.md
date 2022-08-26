# Effindice 🎲🎲🎲🎲🎲

## Browser-based Passphrase generator 

This is a single page run-in-browser web application that generates passphrases using the [EFF Dice-Based Passphrase wordlist and methodology](https://www.eff.org/dice) .. for lazy people.

It uses [this](https://github.com/sethblack/javascript-fortuna) javascript implementation of Fortuna pRNG as a cryptographically secure implementation as well as time-delays for each 'dice roll' to affect randomness.

I think this is better than the xkcd passphrase generator because it uses a better method and is completely self-contained with zero web requests.

## Using this application

[Latest release on github pages](https://replete.github.io/effindice/), published automatically.

It's a single html file. Download the .html file onto your computer and run it locally. There are no web requests except for a stupid github shortcut icon to the link back here. Also no javascript frameworks or anything like that. I know right? 

Tested in latest Chrome / Firefox

## Implementation

I hacked it together without any frameworks, it does use a generator function and other modern Javascript features. It's a hack, but whatever.

I tried a few pRNGs and experimented with online 'truly random' sources of RNG data. Quickly realized what a bad idea that was, but anyhow, Fortuna seems to do the trick.

Fortuna's minified script is 35KB. That's most of the payload just for random number generation. Bigger is better, I only wish it was 10MB.

## Demo
[Latest release on github pages](https://replete.github.io/effindice/), published automatically.

No promises on it being up to date.
