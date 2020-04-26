# 1M Linear/Paged RAM/ROM
## One RC2014 memory card to rule them all!

This board combines the best features of currently available RC2014 memory boards in one:

- One 512K memory chip which can be RAM or ROM (selected with 3 jumpers)
- One 512K RAM chip
- Select between linear and paged memory using a single jumper
- Select between linear and paged memory in software (from Z80 or BusRaider)
- Support for the PAGE pin on the RC2014 bus (with an optional pull-up selected via a jumper)

Plays nicely with the BusRaider.

### Jumper Details

* It is recommended that you install the PAGE jumper on this board - see note below about the PAGE jumper
* The Linear/Paged jumper should be set into Paged position if you are using RomWBW and Linear position if using a Z180 with its extended addressing mode. If you are using BusRaider along with this card then you can set the jumper into Linear position as the BusRaider software can control the linear/paged function based on the machine you are emulating.
* The RAM/ROM jumper should be set into the appropriate position for the chip you are using in socket U1. All three of the RAM/ROM jumpers should be either in the RAM position (when using AS6C4008-55SIN) or ROM position (SST39SF040-70-4C-PHE).

More details of jumpers and IO addresses [are in the documentation](https://github.com/robdobsn/LinearPagedRAMROM1MB/wiki)
## License

The MIT License (MIT)

Copyright (c) 2018-2019 Rob Dobson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
