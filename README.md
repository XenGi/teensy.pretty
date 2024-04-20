![maintenance](https://img.shields.io/maintenance/yes/2024)
[![Donate using Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/xengi/donate)


Teensy footprint library for KiCAD
=======================================

This repo includes KiCAD footprints for the following Teensy versions:

| Teensy       | Pinouts | 3D model |
| ------------ | ------- | -------- |
| Teensy 1.0   | [C](https://www.pjrc.com/teensy/card1a.pdf), [Arduino](https://www.pjrc.com/teensy/card1b.pdf) | ❌ |
| Teensy++ 1.0 | [C](https://www.pjrc.com/teensy/card3a.pdf), [Arduino](https://www.pjrc.com/teensy/card3b.pdf) | ❌ |
| Teensy 2.0   | [C](https://www.pjrc.com/teensy/card2a_rev5_web.pdf), [Ardino](https://www.pjrc.com/teensy/card2b_rev5_web.pdf) | ❌ |
| Teensy++ 2.0 | [C](https://www.pjrc.com/teensy/card4a_rev2_web.pdf), [Arduino](https://www.pjrc.com/teensy/card4b_rev2_web.pdf) | ❌ |
| Teensy 3.0   | [Front](https://www.pjrc.com/teensy/card5a.pdf), [Back](https://www.pjrc.com/teensy/card5b.pdf) | ❌ |
| Teensy 3.1   | [Front](https://www.pjrc.com/teensy/card5a_rev7.pdf), [Back](https://www.pjrc.com/teensy/card5b_rev6.pdf) | ❌ |
| Teensy 3.2   | [Front](https://www.pjrc.com/teensy/card7a_rev3_web.pdf), [Back](https://www.pjrc.com/teensy/card7b_rev3_web.pdf) | ❌ |
| Teensy LC    | [Front](https://www.pjrc.com/teensy/card6a_rev4_web.pdf), [Back](https://www.pjrc.com/teensy/card6b_rev4_web.pdf) | ❌ |
| Teensy 3.5   | [Front](https://www.pjrc.com/teensy/card8a_rev3_web.pdf), [Back](https://www.pjrc.com/teensy/card8b_rev3_web.pdf) | ✔️ (by [Darcy](https://forum.pjrc.com/members/44808-Darcy)) |
| Teensy 3.6   | [Front](https://www.pjrc.com/teensy/card9a_rev2_web.pdf), [Back](https://www.pjrc.com/teensy/card9b_rev2_web.pdf) | ✔️ (by [Darcy](https://forum.pjrc.com/members/44808-Darcy)) |
| Teensy 4.0*   | [Front](https://www.pjrc.com/teensy/card10a_rev2_web.pdf), [Back](https://www.pjrc.com/teensy/card10b_rev2_web.pdf) | ✔️ |
| Teensy 4.1   | [Front](https://www.pjrc.com/teensy/card11a_rev3_web.pdf), [Back](https://www.pjrc.com/teensy/card11b_rev3_web.pdf) | ✔️ (by [Zack Kummer](https://grabcad.com/library/teensy-4-1-1)) |

\* includes SMT version

Notes:
  - The Teensy 4.0 SMT footprint requires the addition of edge cuts (indicated
    by lines in the `Dwgs.User` layer) which create castellated connections
    for most pins. Pins 2, 3, 31, 32 & 34 are not castellated and will require
    careful soldering and probably a wire to ensure a reliable connection.
  - There are two footprints for Teensy 3.0/3.1/3.2 and 3.5/3.6. One that
    includes the through-hole connections on Teensy and one that adds all of
    the SMT connections on the bottom of the Teensy.

For symbols look here: https://github.com/XenGi/teensy_library
