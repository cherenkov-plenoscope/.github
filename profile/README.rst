|PublicationOptics| |WorkInProgress| |WorkInProgress|

Science :milky_way:
*******************
Cosmic gamma rays are a special probe to investigate sudden cosmic events in the universe. Unlike thermal emission, which ranges from radio to X-rays, cosmic gamma rays are often a direct probe of bursts or other short lived cosmic catastrophes. Today, the timing of cosmic gamma rays is a vivid part of astronomy. Cherenkov telescopes observe the rare gamma rays with energies of several hundred giga electron Volt in large collecting areas exceeding the size of soccer or football fields. Particle detectors on satellites observe the much more abundand gamma rays with energies of about one giga electron Volt in small collecting areas with the size of about a car's windshield. But for better timing, we want to collect the abundand gamma rays with low energies in large collecting areas in order to have large statistics in short amounts of time. This is the goal of the atmospheric Cherenkov plenoscope.

This project explores the feasibility and performance of a Cherenkov plenoscope
to observe cosmic gamma rays with energies as low as one giga electron Volt in
collecting areas as large as several thousand square meters.

The main objectives are to investigate and publish our findings related to:


Optics and light fields :white_check_mark:
    Explore and demonstrate how the optics of a plenoscope and it's perception of
    light fields can be used to overcome the physical limits of existing
    telescopes in order to build larger instruments which can detect cosmic
    gamma rays with lower energies.

Background from cosmic rays :hammer: :wrench:
    Explore the background of cosmic rays in the presence of earth's magnetic field
    which will be visible to any atmospheric Cherenkov instrument capable of
    detecting cosmic gamma rays with energies as low as one giga electron Volt.

Astronomical performance :hammer: :wrench:
    Estimate the response functions of a specific Cherenkov plenoscope designed to
    detect cosmic gamma rays with energies as low as one giga electron Volt.
    Estimate and discuss its sensitivity for astronomical targets in the context of
    timing. This might include: gamma ray bursts, counterparts to mergers seen in
    gravitational waves, timing arrays of pulsars, variability of active galactic
    nuclei.


|MpiHeidelbergLogo| |EthZurichLogo|



Organization :clipboard:
************************
This github organization collects the ideas, drafts and computer programs which
simulate and estimate the performance of the Cherenkov plenoscope to observe
cosmic gamma rays.
The computer simulations have a modular design so that functionalities with
limited scopes are put into their own packages. This organization collects
these individual packages, and libraries.
Having individual packages of limited scope is hoped to ever so slightly
increase the chances for you to reuse this work. Individual packages have their
own READMEs, they have their own unit tests, and they have interfaces which
mostly consist out of types which are natural to the corresponding programming
language.

However, some packages are special to the Cherenkov plenoscope. They bundle the
other packages and use them to perform more complex tasks which are specific
to the simulations of the Cherenkov plenoscope.
The culmination of this is the ``starter_kit`` repository. It collects all the
other packages as submodules and is the place where the computer simulations
for the Cherenkov plenoscope are developed.


.. |EthZurichLogo| image:: https://github.com/cherenkov-plenoscope/.github/blob/main/profile/resources/ethz_logo_black.svg
    :width: 15%
    :target: https://ipa.phys.ethz.ch/

.. |MpiHeidelbergLogo| image:: https://github.com/cherenkov-plenoscope/.github/blob/main/profile/resources/logo_mpi_kernphysik.svg
    :width: 15%
    :target: https://www.mpi-hd.mpg.de/mpi/de/

.. |PublicationOptics| image:: https://github.com/cherenkov-plenoscope/.github/blob/main/profile/resources/mueller2024exploring-optics.jpg
    :width: 33%
    :target: https://www.sciencedirect.com/science/article/pii/S0927650524000100

.. |WorkInProgress| image:: https://github.com/cherenkov-plenoscope/.github/blob/main/profile/resources/work_in_progress_placeholder.svg
    :width: 33%
