---
layout: "page"
title: Hands on SDR
---
There is a [downloadable](/assets/pdf/TwoDaySDR_U19_Outline.pdf) summary of the course.


You don't even need to have a radio to get started with SDR. Try our 
[free Guide](/assets/pdf.WebSdr.pdf to getting started with SDR to find out more.

### Technology Focus
Modern radio systems now rely on digital signal processing for more and more functions in both 
the transmitter and the receiver. This technolgy enbles wireless interconnectivity for a diverse 
range of produces and services from satellite communications, to mobile phones and the internet of 
things. Furthermore it shows how RF functionality has never been more accessible. This short course 
uses supplied hardware and software to illustrate the key concepts and convert theory to practice. 
During the course students complete a QPSK radio link; digits to RF and back to illustrate core 
concepts of SDR. There was a preview of some of the ideas in this course given at the April 2018 
ARMMS conference in Oxford.  A_NewGoldenAgeOfRadio.pdf

Course Objective and Who should Attend
This is a course focusing on understanding and applying key principles of digital radio concepts. 
It is for product developers wanting to exploit new radio ideas as well as established engineers 
looking to better understand the interface between digital signals and analogue RF hardware. The 
course builds on common enginerring fundaments to understand the principles of discrete and 
continuous time signals. Then, using the software and hardware provided, the objective is to 
demonstrate a QPSK modulated transmitter, receive and decode the signals. Along the way students 
will learn the details of the various steps, observe fundamental DSP concepts as well as apprciate 
how modern highly integrated RF ICs make it staight forward to apply to this to a huge range of 
possible applications.

## Day 1
After a brief introduction and familiarisation with the hardware and software, students will build 
a basic FM broadcast receiver to observe the practical issues of bandwidth, sampling rate, sample 
rate conversion and filtering. These topics are then developed further as individual modules for 
the remaining day. Items covered include aliased signals, dynamic range as well as fundamentals 
of digital filters, interpolation, decimation and resampling.

## Day 2
Building from day 1, the development of a QPSK modulated transmitter and corresponding receiver 
is investigated. Using GRC the DSP aspects of the Tx are developed showing the signal progression 
from digits to symbols via constellation mapping, then interpolation and application to the Pluto 
hardware to create an RF signal. Similarly, the key stages of the Rx are simulated in GRC, 
illustrating timing recovery, matched filtering and channel adaption. The software supports 
interfaces to both the Tx and Rx of Pluto, so that using an RF loop back cable, both can be 
combined to complete a digits to RF and back again radio link.

----

All the lectures and experiments are supported by prepared files that are provided for the course. 
These are data files for the various applications as well as a PDF of a presentation given to show 
the key points from the various hands on experimental sections.