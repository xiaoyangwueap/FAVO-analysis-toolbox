Matlab Toolbox For
Frequency-Dependent AVO Analysis
List of codes in ‘main’ file
Code names instructions
attenuation_main This function calculates the variation of 1/Q with water saturation by
calling the subroutine avo_rp, which is used to calculate the elastic
constant at a certain frequency using Chapman et al. (2002) model
with wood's formula, which is used to calculate the elastic moduli of
mixture.
avo_rp This function calculate the frequency dependent lame constant and
density for multi-fluid mixture when changing porosity and water
saturation by combining Chapman et al.(2002) model with Wood's
formula.
cwt1d This function applies the continuous wavelet transform to a 1D
discrete-time signal x from files using modified Morlet wavelet.
cwt2d This function computes spectra of 2D .sgy format seismic signal
using the continuous wavelet transform.
cwt3d_layer This function computes horizontal layer spectra of 3D .sgy format
seismic data using the short-time Fourier transform.
dispersion_main This function calculates the variation of 1/Q with water saturation by
calling the subroutine avo_rp.m, which is used to calculate the elastic
constant at a certain frequency using Chapman et al.(2002) model
with wood's formula, which is used to calculate the elastic moduli of
mixture.
draw_sgywaveform This function is used to draw the waveform of a .sgy file generated
from Seismic Unix; the .sgy file contains one CDP gather.
draw_suwaveform This function draws the waveform of a .su file generated from
Seismic Unix; the .su file contains one CDP gather data.
favo_interpolate This script is used to interpolate pre-stack data with different trace
interval to the equal interval.
favo_spwv This function computes the frequency dependent AVO attribute using
spwv spectral decomposition method.
fft_spectra This function computes the spectra of four traces from a .sgy file with
Fast Fourier Transform to help analyze the dominant frequency and
bandwidth.
freqcurve This function is used to calculate frequency curve for a single trace at
a temporal position.
1
freqgather offset2angle ppcomd ppcomds ricker sgyimage spectral_balance_p
oststack
spectral_balance_p
restack
spwv1d spwv2d spwv3d_layer stft1d stft2d stft3d_layer vel_interpolate wv1d This function is used to calculate spectral amplitude at a series of
frequency (frequency gather) along a layer for post-stack seismic
data.
This function transform offset to
% incident angle through velocities which is stored in infile.
This script calculates the reflectivity and phase at a known porosity
and water saturation with Chapman et al.(2002) model. Wood's
formula is used to estimate the elastic moduli of the mixture fuilds.
This script scans the reflectivities and phases at a series of porosities
and water saturation with Chapman et al. (2002) model and Wood's
formula. The result (reflectivity and phase) is saved in two files at the
same directory.
This function generates ricker wavelet. It can also be used to generate
other wavelet which is defined in aniseis.
This function reads and displays the image of a iso-frequency section
after spectral decomposition. It can also be used to display several
iso-frequency sections in the same colorscale.
This function generates the balanced spectral amplitude for post-
stack data. the value of time horizon is stored in a data file.
This function generates the balanced spectral amplitude for prestack
CMP gather.
This function computes the smoothed pseudo Wigner-ville transform
of a 1D discrete-time signal x.
This function computes spectra of 2D .sgy format seismic signal
using the smoothed pseudo Wigner-Ville transform.
This function computes horizontal layer spectra of 3D .sgy format
seismic data using the short-time Fourier transform. The .sgy data
can be cut to a small volume that only contains the data of the
horizontal layer.
This function computes the short-time Fourier transform of a 1D
discrete-time signal x.
This function computes spectra of 2D .sgy format seismic signal
using the short-time Fourier transform.
This function computes horizontal layer spectra of 3D .sgy format
seismic data using the short-time Fourier transform.
This function is used to interpolate scattering velocities at un-uniform
interval to uniform interval with linear interpolation.
This function applies the Wigner-Ville transform to an 1D discrete-
time signal x.
