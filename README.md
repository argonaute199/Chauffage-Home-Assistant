Forks here:

. Presence-Absence (default, this one): [ProdOk]

    - based on Argonaute version
    - different mode names (Presence-Absence, instead of AutoConfort-AutoEco)
    - single Absence mode
    - 'radiateur' switch name instead of 'chauffage'

. Week-Vs-WE: [ProdOk]

    - based on Presence-Absence version
    - support multiple schedules for Presence mode (ex Week & Weekend)
    - tested ok in v.0.24
    - note : multi open-windows sensor still need to group them

. more to come : [Work in progress : 0.25+]

    - based on Week-Vs-WE version
    - support for inverted light switch like SonOff ZBMini/ZBMini2R + diode (inversed On/Off)
    - later : add support for a limited time boost period
    - later : add support for target temperature auto-change option in case of EDF Tempo Red day

Thanks Argonaute for this beautiful work and tuto!

############################################## ORIGINAL README ################################

Home Assistant - Gestion de bout en bout du chauffage

This repository contains the files of a post in HACF french forum.

It is the complete implementation of a heating management system for home assistant:

    Proportional thermostat
    window opening management
    Heating modes (eco, comfort)
    Time zones

Please see https://forum.hacf.fr/t/gestion-de-bout-en-bout-du-chauffage/4897

