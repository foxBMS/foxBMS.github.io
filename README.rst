######
foxBMS
######

foxBMS is a free, open and flexible development environment to design battery
management systems. It is the first modular open source BMS development
platform.

The foxconda environment: This environment provides all the tools necessary
to generate the documentation, compile the code for the MCUs and flash the
generated binaries on the MCUs (e.g., ``Python``, ``git``, ``GCC``). foxconda
can be downloaded from
`iisb-foxbms.iisb.fraunhofer.de/foxbms <https://iisb-foxbms.iisb.fraunhofer.de/foxbms/>`_.

The starting point to get foxBMS is the foxBMS repository at
https://github.com/foxBMS/foxbms, which
contains all files for the foxBMS project.

foxBMS Repository
=================

- In ``foxbms\documentation`` the configuration of the doxygen documentation
  for the primary and secondary MCU can be found.
- The software for the MCUs is found in ``foxbms\embedded-software``. This
  includes the Hardware Abstraction Layer (HAL), the real-time operating system
  FreeRTOS and the BMS application itself.
- The layout and schematic files for the foxBMS hardware are found in the
  ``foxbms\hardware``.
- The build toolchain and other tools related to foxBMS are found in
  ``foxbms\tools``.

A generated version of the Sphinx documentation can be found at
`docs.foxbms.org <https://docs.foxbms.org>`_. It explains the structure of the
foxBMS hardware, how to install the foxconda environment and how to use
foxconda to compile and flash the sources.

----

`foxbms.org <https://foxbms.org/>`_
