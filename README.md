# Physically Unclonable Functions for Hardware Security

## About this fork

This repository is a fork of an existing project exploring the use of
Physically Unclonable Functions (PUFs) for hardware security applications.

The purpose of this fork is to review and study different PUF architectures,
with a focus on understanding their practical implementation characteristics
and trade-offs.

## Overview

Physically Unclonable Functions (PUFs) provide a hardware-based fingerprint that
can be used for device identification and protection against cloning or
counterfeiting.

This project examines two commonly used PUF structures:

- Ring Oscillator PUF
- Butterfly PUF

The implementations are primarily targeted for FPGA-based evaluation.

## Repository Structure

- `ring_oscillator_PUF/` – Ring Oscillator PUF implementation
- `butterfly_PUF/` – Butterfly PUF implementation
- `README.md` – Project overview and notes

## Notes

This fork is intended for educational and exploratory purposes.
All original implementation credit belongs to the upstream authors.


# Physically-Unclonable-Functions-for-Hardware-Security
PUF is a digital Fingerprint used to prevent semi-conductor device designs of a particular company to be stolen, copied or remade by the Foundry or any other company. This project was to analyze which out of Ring or Butterfly PUFs work the best for Hardware Security. THe PUFs were tested on an FPGA to analyze the hardware area consumed, resouce utilization and pwer consumed.

THese are basically functions added to the main code of the design, to generate random results each time the desig is copied, making ti impossible ot decode the actual design of the device.
