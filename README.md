QubeCast-Max
============

QubeCast Max is a high powered radio module in the PocketQube PQ60 form factor. 

QubeCast Max combines a NiceRF RF4463F30 module, which is a general purpose ISM band transceiver with 30dBm output power, with a board based on the PocketQube PQ60 form factor. A PocketQube is a relatively new type of nanosatellite that is smaller than a 1U Cubesat. In fact, a 1P PocketQube is 1/8th the size of a 1U Cubesat! The means that it is 5cm x 5cm x 5cm, and weighs approx 150g.

This project is being built to test the RF4463F30 module, to determine its suitability for use in a PocketQube satellite that I am building - "OzQube-1" http://ozqu.be

The module is based on the SiLabs Si4463 transceiver IC, but adds a power amplifier to boost the Si4463's 100mw output to 1W. The radio communicates to a host microcontroller via SPI, with a few additional control pins. 

I've made an adapter for an Arduino Pro Mini to connect to the PQ60 form factor board, which will stack with the radio board to be able to control it. 
