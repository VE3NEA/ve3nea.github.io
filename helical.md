---
title: Helical Filter for SAT Reception
nav_order: 2
---

# Helical Filter for SAT Reception

My location is pretty noisy on all bands. In particular, the
[King City station of Land Mobile Radio Network](https://www.radioreference.com/db/site/42847)
continuously transmits several trunked signals between 141 and 143 MHz. These signals are so strong
that the SDR receivers are overloaded, and no reception on the 2m band is possible:

<a href="images/helical/spect_no_filter_hi_gain.png" target="_blank" rel="noopener noreferrer"><img src="images/helical/spect_no_filter_hi_gain.png" alt="spectrum1"></a>

When the receiver gain is turned down to prevent clipping, weak signal reception is no longer possible,
but at least the offending signals become visible on the band scope.

<a href="images/helical/spect_no_filter_lo_gain.png" target="_blank" rel="noopener noreferrer"><img src="images/helical/spect_no_filter_lo_gain.png" alt="spectrum1"></a>
