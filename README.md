# HFrisk-Op-Amp
A collections of some Ngspice models of simple op-amps I've designed for fun.

CurrentCopyingOpAmp - An op-amp that doesn't have an intermediate gain increasing stage but rather aims to just amplify the current of the input differential pair. Works pretty good up to 10kHz so could be used for sound applications.

CommonSourceIntermediateOpAmp - An op-amp that uses a common source amplifier as it's intermediate gain increasing stage. Rings badly if used with feedback. Will have to investigate the ringing furter. 

SingleStageOpAmp - A very simple single stage op-amp. Does have pretty good frequency response but has low current output i.e. high output impedence. 

To run: 
1. Have Ngspice installed
2. In this directory, type "ngspice CurrentCopyingOpAmp.cir" (or wichever op-amp you want to run)