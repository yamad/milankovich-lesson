# Milankovich Cycles and frequency analysis

These are files that support a lesson intended for high school students that
frames the frequency analysis of waves in the context of Milankovich cycles
and paleoclimatology.

The idea is to allow students to work with real climate data, explore that
data in R, and learn about how frequency analyis (here, Fourier transforms)
are used in real-world science.

This repository includes the R code, the data, and some commentary. I haven't,
unfortunately, carefully written up the final lesson plan.

The lesson tracks the approach taken in Hays, Imbrie, and Shackleton's 1976
paper. The paper uses frequency analysis of climate records to show that the
three Milankovich frequencies are most prominent. The work essentially ended a
long-standing debate about whether Milankovich cycles play a role in climate.

The R code makes frequency spectra from orbital simulations and climate
records allowing users to play with the key data and analysis themselves. It
also demonstrates the well-known "100,000-year problem", where the spectra
suggest that the 100,000-year cycle is the most influential for climate even
though it has the smallest effect on solar energy reaching Earth.

Hays, Imbrie, and Shackleton. 1976. Variations in the Earth's Orbit: Pacemaker
of the Ice Ages. Science 194:4270, 1121--1132.
