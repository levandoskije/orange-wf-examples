# Point Spectrum Examples
-------
The spectrum of points is a simpler file to generate for this equipment.

There are 3 possible file types:

 - Raw files, with extension \*.gsf
 - Spectra files, with extension \*.txt
 - Standard files, with extension \*.txt

## How to open these files?

### 1. RAW files

It is the least processed file for equipment, so it is necessary to do the entire mathematical process.
There are benefits to this approach, as in this case you can have access to all measurements.
In some cases, it can be important to access SNR from all points, so with raw files you can do this.

How to open?

- To open these files you need to have **3 files in the same folder**, for example to open the second harmonic (O2A)

  - "file name" O2A raw.gsf -> * Interferogram of amplitude *
  - "file name" O2P raw.gsf -> * Phase Interferogram *
  - "file name" .html -> * File with measurement information *

- Open with ***Multifile***, when selecting the file "*[...] O2A raw.gsf*" or "*[...] O2P raw.gsf*" you need to select a specific reader, to raw files, needs to be **"*NeaSPEC raw files (\*. gsf)* "**

- After opening the interferogram files, it is necessary to apply a Fourier Transform, for that it is necessary to use the *** Interferogram for Spectrum *** widget, there are some settings available to users, such as Zero fill factor and what type of apodization you want to use. But you can just live by default if you don't want to change.

### 2. Spectra files

### 3. Standard files