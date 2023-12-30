# Karmstrup Multical 603

ESP Home Karmstrup Multical 603

### Inspiration:
(very much borrowed from)

- [Kamstrup Multical 402 for esphome](https://github.com/cenobitedk/esphome_multical402)
- [ha-kamstrup_403](https://github.com/golles/ha-kamstrup_403)
- [Aflæs Kamstrup elmålere med ESP8266 eller ESP32](https://smarthjemmet.dk/2021/09/aflaes-kamstrup-elmaalere-med-esp8266-eller-esp32/)(Danish)


### Optical Readers:


There are many options from many sources, in addition to the ones listed by [cenobitedk](https://github.com/golles/ha-kamstrup_403) there are also all the Hichi TTL readers:

- Amazon: [Hichi TTL - IR Reading Head](https://www.amazon.de/-/en/dp/B0BPMVX4VW?ref=ppx_yo2ov_dt_b_product_details&th=1) - does not ship outside Germany via eBay.

I eventually got the one from amazon, but found a cheaper option on eBay.de: https://www.ebay.de/itm/275076138187 which does need some soldering, but the sell have provided the documentation. 


### Optical Reader to ESP connection:

| ESP | TTL Module  | 
|---|---|
| 3v | + |
| GND | - |
| io16 | rx_pin |
| io17 | tx_pin  |

There should not be a difference if it's an ESP8266 or ESP32 module.


### Holder:

I used this as [inpiration: thing:5615493](https://www.thingiverse.com/thing:5615493), but as the case for my Kamstrup Multical 603 (E) is 40mm deep I had to modify it a bit.

And ended up with


--- working in progress ---