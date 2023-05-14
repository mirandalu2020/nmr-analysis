# NMR Peak Detection in Python

This repository provides a Python implementation for detecting peaks in NMR (Nuclear Magnetic Resonance) data. The goal is to identify and locate the peaks in an NMR spectrum, enabling further analysis and interpretation of the chemical compounds present in the sample.

## Table of Contents
- Introduction
- Requirements
- Usage
- Example
- Contributing

## Introduction 

Introduction
NMR spectroscopy is a powerful analytical technique used to study the chemical structure, composition, and dynamics of molecules. NMR spectra typically exhibit peaks that correspond to specific atomic nuclei within a molecule. These peaks provide valuable information about the types of atoms present, their chemical environment, and the molecular connectivity.

Peak detection in NMR spectra involves identifying the peaks and determining their positions, intensities, and other characteristics. This information can be used for various purposes, such as compound identification, quantification, and structural elucidation.

This repository provides a Python script that utilizes signal processing techniques to detect peaks in NMR data. The script applies a combination of filtering, baseline correction, and peak finding algorithms to extract the peaks from the input NMR spectrum. The process involved including Fourier transform and best-fit data to a normal curve

## Requirements
To use the NMR peak detection script, you need to have the following installed:

Python 3.x
NumPy
SciPy
Matplotlib
