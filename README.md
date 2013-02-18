HERand
======

###High Entropy Random Number scraping from GRC.com's OffTheGrid project.###

GRC.com seeds their [client side Pseudo-Random Number Generator (PRNG) ](https://www.grc.com/otg/uheprng.htm)using some server side generated entropy. Steve Gibson claims this entropy to be pretty high quality. 

So here's a quick little script which scrapes out that "1536 bits of base64-encoded (256 chars) entropy" from the GRC.com's OffTheGrid page.

Very useful to quickly generate high quality random numbers.


#### Dependencies ####
- [cURL](curl.haxx.se)
- grep
- cut
