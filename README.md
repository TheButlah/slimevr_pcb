# slimevr_pcb
A collection of PCBs designed for SlimeVR full-body trackers

- [ferrous_slime](/hardware/ferrous_slime/) - A fully custom surface-mount PCB.
  Unlike most of the SlimeVR community, it uses the ESP32-C3, a newer and more
  powerful chip. Designed to be a more powerful development platform, as it natively
  supports JTAG debugging over USB, more compilers and languages, including Rust,
  and supports Bluetooth LE v5.0.
  ![3d render](/hardware/ferrous_slime/renders/front.png)
- [breakout_slime](/hardware/breakout_slime/) - A through-hole PCB for use with
  breakout boards. Simplest and easy to assemble by hand, but not as small of a
  form factor as it could be.
  ![3d render](/hardware/breakout_slime/renders/front.png)

## License
**This hardware is licensed under the CERN-OHL-P v2 license**, which is a permissive,
non-viral and non-reciprocal open hardware license. Unlike software licenses like
MIT and Apache 2.0, it better handles the nuances of hardware and protects both
the licensor and licensee from patent lawsuits.

**Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in this work by you, shall be licensed as above, without any
additional terms or conditions.**

### Conveying notice of License
Note that as part of the CERN-OHL-P v2 license, recipients of manufactured
hardware must also receive notice of the above license. One such
method of conveying the notice is to include a link to the original source repo,
or printing "Licensed under CERN-OHL-P v2" on the PCB silkscreen. For more info,
see [here](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2).

This is conceptually similar to the MIT/Apache 2.0 Licenses, where the original
license must still be included as a notice even when the source is modified and
subsequently relicensed under different terms.
