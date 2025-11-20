---
title: Helical Filter for SAT Reception
nav_order: 2
---

# Helical Filter for SAT Reception

My location is pretty noisy on all bands. In particular, the
[King City station of Land Mobile Radio Network](https://www.radioreference.com/db/site/42847)
continuously transmits trunked signals between 141 and 143 MHz. These signals are so strong
that the SDR receivers are overloaded, and no reception on the 2m band is possible. I tried
RTL-SDR, RSP1a and Airspy Mini, none of these receivers were able receive in the presence of these signals. I added the
[Minikits preamp](https://www.minikits.com.au/electronic-kits/rf-amplifiers/rf-preamplifiers/eme220-2m)
with a narrowband front end filter, but this did not help.

<a href="images/helical/spect_no_filter_hi_gain.png" target="_blank" rel="noopener noreferrer"><img src="images/helical/spect_no_filter_hi_gain.png" alt="spectrum1"></a>

*Click on the image to enlarge.*

When the receiver gain is turned all the way down to prevent clipping, weak signal reception is no longer possible, but at least the offending signals become visible on the band scope:

<a href="images/helical/spect_no_filter_lo_gain.png" target="_blank" rel="noopener noreferrer"><img src="images/helical/spect_no_filter_lo_gain.png" alt="spectrum1"></a>
