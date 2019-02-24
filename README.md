# AR-150 WiFi Pineapple NANO

Converting your AR-150 to a WiFi Pineapple NANO should be an easy process.  However, the web & git is full of broken bin images and botched firmware builders... resulting in a broken or partially-working firmware.  The latest working build available elsewhere is 2.0.2, which contains many bugs & security issues.  Here, we start with version 2.4.2.

As the AR-150 only has 1 radio, it's necessary to add a second WiFi adapter.  This firmware has been compiled with RT5370 support, available from Hak5 or Amazon for £5.

Summary:
1.  Correctly-configured MTDs, allowing 2.4MB of overlay/tmp for modules.  It doesn't sound like much, but with most modules being <10KB in size, it should be sufficient without adding an SD card.
2.  RT5370 WiFi adapter support built-in.
3.  PineAP(d) working.
4.  Added support for 2 port USB hub (https://www.ebay.co.uk/itm/USB-2-0-2-Dual-Port-Hub-For-Laptop-Macbook-Notebook-PC-Mouse-Flash-Disk/273070654192?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2060353.m2749.l2649)

AR-150: £24
2 x RT5370: £10
2 Port USB Hub: £4

Total: £38
WiFi NANO: £129 (at time of writing)
