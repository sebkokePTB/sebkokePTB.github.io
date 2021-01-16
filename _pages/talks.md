---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

As speaker
======

12. S. Koke, A. Kuhl, T. Waterholter, S.M.F. Raupach, O. Lopez, E. Cantin, N. Quintin, A. Amy-Klein, P.-E. Pottie, G. Grosche, „Repeatability of fiber-based optcal frequency dissemination over 1400 km combining fiber Brillouin amplification with a repeater laser station“, IFCS-ISAF 2020, 23.07.2020

11. T. Jürß, S. Koke, G.Grosche, „Monolithic interferometer for accurate optical frequency dissemination“, IFCS-ISAF 2020, 21.07.2020

10. S. Koke,  J.  Kronjäger,  E.  Cantin,  O.  Lopez,  A.  Kuhl,  T. Waterholter, E. Benkler, A. Amy-Klein, P.-E. Pottie, G. Grosche, „Operation  of  the  Fibre  Links  PTB–UoS  and  NPL–LPL  in  the  First Trinational  Fibre  Link  Clock Comparison Campaign“, EFTF 2018, Turin, 10.04.2018

9. S. Koke, A. Kuhl, O. Lopez, N. Quintin, A. Amy-Klein, P.-E. Pottie, G. Grosche, „Performance of a Fibre Link Combining Fibre Brillouin Amplification with a Repeater Laser Station“, EFTF-IFCS 2017, Besançon, 11.07.2017

8. S. Koke, C. Grebing, A. Kuhl, G. Grosche, „Validating Frequency Transfer via a Stabilised Fibre Link for Optical Clock Comparisons“, EFTF 2016, York, 07.04.2016

7. S. Koke, C. Grebing, and G. Steinmeyer, „Acousto-optical self-referencing of frequency combs“, Laser Optics Berlin, Berlin, 22.03.2010

6. S. Koke, S. Birkholz, J. Bethge, C. Grebing,  G. Steinmeyer, „Self-diffraction SPIDER“, Conference on Lasers and Electro-Optics Europe 2009, München, 18.06.2009

5. S. Koke, C. Grebing,  G. Steinmeyer, „Self-referenced optical frequency combs“, Conference on Lasers and Electro-Optics Europe 2009, München, 17.06.2009

4. S. Koke, C. Grebing, B. Manschwetus, G. Steinmeyer, „Direct Measurement of the Carrier-Envelope Phase of Amplified Pulses with Multi-kHz Update Rates“, Conference on Lasers and Electro-Optics 2008, San Jose, USA, 07.05.2008

3. S. Koke, C. Grebing, B. Manschwetus, G. Steinmeyer, „Selbstreferenzierendes f-2f Interferometer zur Phasenstabilisierung von Femtosekundenlasern“, DPG Frühjahrstagung 2008, Darmstadt, 13.03.2008

2. S. Koke, D. Träger, Ph. Jander, C. Denz, „Counterpropagating solitary waves in periodically modulated media“, EOS Annual Meeting 2006, Paris, 19.10.2006

1. S. Koke, Ph. Jander, T.D. Frank, C. Denz, „Dynamics of counterpropagating spatial solitons in photorefractive crystals“, DPG Frühjahrstagung 2006, Frankfurt, 15.03.2006

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
