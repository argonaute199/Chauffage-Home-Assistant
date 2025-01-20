Forks here:

. [Old] Presence-Absence: [ProdOk]

    - based on Argonaute version
    - different mode names (Presence-Absence, instead of AutoConfort-AutoEco)
    - single Absence mode
    - 'radiateur' switch name instead of 'chauffage'

. [Actual] Week-Vs-WE: [ProdOk]

    - based on Presence-Absence version
    - support multiple schedules for Presence (or Absence) modes (ex Week & Weekend temp targets)
    - support for inverted relay (ex SonOff ZBmini+diode)
    - tested ok in 0.27
    - note: multi open-windows sensor still need to group them

. [More to come] [Work in progress : 0.28+]

    - based on Week-Vs-WE version 0.27
    - add support for adjustable temperature for frost protection mode
    - add support for multi-heater in a same room / for one thermostat
    - later: add support for a limited time boost period
    - later: add support for target temperature auto-change option in case of EDF Tempo Red day
    - later: delay so every Thermostat doesn't start at the same moment (load optimization)
    - maybe: humidity threshold not to be exceeded (auto-boost)
    - maybe: develop an option to accept optional laod shedding during peak demand, as a civic act (Voltalis like)

Thanks Argonaute for this beautiful work and tuto!

############################################## ORIGINAL README ################################

Home Assistant - Gestion de bout en bout du chauffage

This repository contains the files of a post in HACF french forum.

It is the complete implementation of a heating management system for Home Assistant:

    Proportional thermostat
    Window opening management
    Heating modes (eco, comfort)
    Time zones

Please see https://forum.hacf.fr/t/gestion-de-bout-en-bout-du-chauffage/4897

