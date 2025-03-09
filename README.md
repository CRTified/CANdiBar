# CANdiBar Hub

## What is this?

This repository aims to contain a small CAN bus and power distribution
board. However, I wanted to avoid making all devices connected by a stub.

Properties:

 - Five ports for a 2x3P Molex MicroFit 3.0
 - Proper CAN setup (No star topology that makes everythin a stub)
 - Termination and pass-through connection possible on every port

## Why?

I wanted to try [atopile](https://atopile.io/) and a simple
distribution board seemed like a great fit to test the whole design
process.

I also wanted to have a sane piece of hardware for simplifying the
wiring in my 3D printer, as the
[Voron v0.2r1](https://vorondesign.com/voron0.2) gets pretty crowded
when using more than two MCUs.
