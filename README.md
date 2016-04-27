# ifClippedAdjustVolume #

Max4Live patch that monitors a channel for clipping and adjusts the channel volume to compensate.

Add this patch as the last plugin on your channel. If the audio exceeds -0.3 dBFS (adjustable), the channel volume control will be adjusted (to a limit of -18 dB) to avoid clipping the mixer.
