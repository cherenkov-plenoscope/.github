|PublicationOptics| |WorkInProgress| |WorkInProgress|

|MpiHeidelbergLogo| |EthZurichLogo|

This project explores the feasibility and performance of a Cherenkov plenoscope
to observe cosmic gamma rays with energies as low as one giga electron Volt in
collecting areas as large as several thousand square meters.

Organization
************
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
