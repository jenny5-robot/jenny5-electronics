# Jenny 5 electronics

## Arm electronic

Currently is built around the [Pololu A-Star 32U4 Mini](https://www.pololu.com/product/3104) board.

It can control 6 bipolar stepper motors (through A4988 driver) and read several sensors (six AS5147 connected through SPI).

You need [Fritzing](http://fritzing.org/home/) to view or modify this board.

Pololu A-Star 32U4 Mini part for Fritzing can be found into [utils](utils) folder.

You can modify it as you want and then validate it (from _PCB_ tab, menu _Routing|Design Rules Check_) and then export it for production (from _PCB_ tab, menu _File|Export|For Production|Extended Gerber_)

### Weaknesses

Currently the +/- logical connectors are too small and cannot fit all wires properly. In the next iteration I will add another connector for +/-.
I do not know if the power traces are thick enough (I could not make them thicker with Fritzing. Probably I should use 2 separate traces.).

## Base platform electronics

under development...

## Leg electronics

under development...

## Head electronics
under development...

**_WARNING_**

** Build on your own risk! I offer no warranty whatsoever! **