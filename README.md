# Bachelor-thesis
Development of a spatial audio binaural presentation system based on MPEG-H.

Summary

This project aims to implement an efficient algorithm for measuring head impulse
responses, known as HRIR (Head-Related Impulse Response), which have been
acquiring an important role in the area of acoustics, spatial and three-dimensional sound in
recent years.

The HRIR specifies how the reception of a sound wave (parameterized by its
source location) is filtered before it reaches the listener’s eardrum. The HRIRs
constitute for each position and for each listener a pair of filters corresponding to each ear.
Due to factors of ear physiology, head shape, source-to-ear distances, and more factors detailed below, the HRIRs measured from a given listener are unique to that listener and their
respective ears.

The project focuses primarily on the last stage offered by the MPEG-H audio
standard, in its third part, binaural sound reproduction. Binaural sound, in its 3D
development part, is characterized by representing a sound that is spatially identified in a
three-dimensional area by the listener, with adapted headphones. The implementation of
this project is also inspired by the Ambisonic system, which aims to reproduce the sound
in loudspeakers in such a way that the listener can locate the sound in a 3D space. To
carry out the measurement algorithm, the MATLAB program is used, which has favorable
characteristics for digital signal processing. In addition, filtering is performed through a plugin in the digital audio workstation (DAW) program, REAPER.

Measurements are taken from 7 positions corresponding to a 7.1 loudspeaker layout, from a
given listener. In total, the HRIRs of 10 volunteers (listeners) are measured, in addition to
that of an acoustic dummy, which would amount to a total of 77 measurements. At the same
time, all the measurements are cross-checked to answer the following questions: Is there a
general head that is more adaptive to the others? Does the sound identification
work best for the HRIRs own to the listener?.
Promises are fulfilled. It is found that by applying the HRIRs corresponding to each listener,
the best result is obtained, due to the factors described above. At the same time, due to
physiological reasons, there is an ear shape that gives convincing results with its HRIRs
applied to the other listeners, and others that do not convince with the results obtained.

Keywords:

Head-Related Impulse Response (HRIR) - Spatial sound - Three-dimensional sound - Binaural
sound - MPEG-H - MATLAB - REAPER - Digital Audio Workstation(DAW) - Ambisonic
System - 7.1 loudspeaker layout
