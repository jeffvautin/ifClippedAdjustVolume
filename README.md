# ifClippedAdjustVolume #

Max4Live patch that monitors a channel for clipping and adjusts the channel volume to compensate.

Add this patch as the last plugin on your channel. If the audio exceeds -0.3 dBFS (adjustable), the channel volume control will be adjusted (to a limit of -18 dB) to avoid clipping the mixer.

## License

This is distributed under the [CC-BY-SA 4.0 License][1]. The full text is included [here][2]. In summary, you are free to:

**Share** — copy and redistribute the material in any medium or format  
**Adapt** — remix, transform, and build upon the material for any purpose, even commercially.  
The licensor cannot revoke these freedoms as long as you follow the license terms.

[1]: https://creativecommons.org/licenses/by-sa/4.0/
[2]: LICENSE.md
