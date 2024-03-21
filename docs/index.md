---
layout: default
---

# Whats is an RfmUsb Adapter

An RfmUsb is a USB 2.0 device that exposes the functions of the Hope RFM69 radio modules over a serial command line interface. It can be used with any modern OS as it enumerates as a standard CDC usb device.

## Hardware Overview

The RfmUsb device supports the RFM69HCW radio module. An ATSAMD21E18A mcu performs USB and CLI processing functions.

_\* A future version may support the RFM95 module which is an FSK/OOK and Lora capable radio_

### RRM69HCW Module Specifications

* +20 dBm - 100 mW Power Output Capability
* High Sensitivity: down to -120 dBm at 1.2 kbps
* High Selectivity: 16-tap FIR Channel Filter
* Bullet-proof front end: IIP3 = -18 dBm, IIP2 = +35 dBm,80
dB Blocking Immunity, no Image Frequency response
* Low current: Rx = 16 mA, 100nA register retention
* Programmable Pout: -18 to +20 dBm in 1dB steps
* Constant RF performance over voltage range of module
* FSK Bit rates up to 300 kb/s
* Fully integrated synthesizer with a resolution of 61 Hz
* FSK, GFSK, MSK, GMSK and OOK modulations
* Built-in Bit Synchronizer performing Clock Recovery
* Incoming Sync Word Recognition
* 115 dB+ Dynamic Range RSSI
* Automatic RF Sense with ultra-fast AFC
* Packet engine with CRC-16, AES-128, 66-byte FIFO
Built-in temperature sensor

### Supported Frequencies

* 315 Mhz
* 433 Mhz
* 868 Mhz
* 915 Mhz

*\* Dependant on module variant installed on the RfmUsb board*

### Front View

![rfmusb-front.png](./images/rfmusb-front.png)

### Back View

![rfmusb-back.png](./images/rfmusb-back.png)

### Protective Case

![rfmusb-case.png](./images/rfmusb-case.png)

### Connectors

Connector | Description
---------|----------
 J1 | 50 Ohm SMA female connector
 J2 | 6 way 2.54mm pitch ISP header (not populated)
 J3 | USB 2.0 Type A

#### ISP Header

The in system programming header (ISP) can be used to flash the device with a boot loader or full flash image. It can also be used with an appropriate debugger to debug application code on the device.

Pin | Name | Function
---------|----------|---------
 1 | Vcc | Power supply ground 3.3v
 2 | Reset | Active low reset
 3 | Gnd | Power supply ground
 4 | SWDCLK | Serial Wire Debug Clock.
 5 | GND | Power supply ground
 6 | SWDIO | Serial Wire Debug Data Input/Output


![rfmusb-isp.png](./images/rfmusb-isp.png)

## Firmware Update


## Requirements



Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
