# spitfire-audio-app
Helper script to install and launch the Spitfire Audio App on Linux

## Disclaimer
This project was just an attempt to see if my personal music production workflow could work on Linux.
I tested the installation of Spitfire stuff (Albion, Studio Woodwinds, LABS and Originals Felt Piano) through the app and bridged them using
[Yabridge](https://github.com/robbert-vdh/yabridge).

The Kontakt libraries seemed to work fine, although the Native Access app installation through Wine isn't smooth,
hence I didn't make the same kind of helper script for it.
As far as the Spitfire plugin goes (LABS and Felt Piano), I ran into a lot of xruns which I could mitigate by changing the cache settings,
but then the exports would cut a lot of notes short.

I'm happy to see how far music making on Linux has come, but I think the niche-within-a-niche of media composers,
or at least people like me who regularly use orchestral/scoring libraries hasn't yet been filled.
I'm keeping this repo here just in case someone wants to experiment with it,
but I won't be maintaining it as I'm switching to a different OS for music production.

## Dependencies

* curl
* wine
* lib32-gnutls
