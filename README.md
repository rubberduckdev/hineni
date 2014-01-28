How?
----

* Mobile app.
 * GPS
 * Local secret over wifi
* Sniffing:
 * MACs
  * Use `sudo airmon-ng start wlan0`
  * Calling `pcap.pcap()` needs sudo as well, this is kinda dangerous.
   * Sniffer that works in sudo and use zmq to produce logs in real time in a less privileged environment
    * Should it be:
     * One sniffer with `ether host ({MAC_1} or {MAC2} or ... or {MAC_n})`sniffing needs sudo.Many sniffers with one logger vs. one sniffer with one filter and one logger
     *
  * "ether host [MAC1]"
 * Bluetooth
* Video
 * Biometrics
   * ... [NOPE!](http://1.bp.blogspot.com/-k6q1p7igpOM/T3MUSJ0V0wI/AAAAAAAAAf4/1WrizGI1xlM/s1600/nooope.png)
 * Barcode - mobile reader with automatic upload?


