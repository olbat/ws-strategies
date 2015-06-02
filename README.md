Guide de Raid Wildstar
======================

Les Archives Génétiques
-----------------------

### 1er étage
- [Trashs](ga/trashs_1.md)
- [Mini-Bosses](ga/mini_bosses_1.md)
- [Boss: Expérience X-89](ga/x89.md)
- [Boss: Kuralak la Profanatrice](ga/kuralak.md)

### 2ième étage
- Trashs
- [Mini-Bosses](ga/mini_bosses_2.md)
- Boss: Prototypes technophages
- Boss: Phagegueule
- Boss: Convergence néophage

### Final
- Mini-Bosses
- Boss: Ohmna la Terriphage


About
=====

Overview
--------
This is a draft of a _French_ guide for Wildstar's Raids.

__Note__: the guide's files are used to generate BBCode hosted on [an external forum](http://www.guilde-lunae.fr/viewtopic.php?f=27&t=257): there is chances this guide will be bugfixed directly on the forum (no update in the repository).


Convert the Markdown guide files to a BBCode one
------------------------------------------------
### with Docker
1. [Install Docker](https://docs.docker.com/installation/#installation)
2. Pull the image containing the runtime environment: `docker pull olbat/ws-strategies`
3. Run the script: `docker run -v $(pwd):/src olbat/ws-strategies`

### without Docker
1. [Install Ruby runtime environment](https://www.ruby-lang.org/en/documentation/installation/)
2. Run: `for f in */*.md; do ./md2bb < $f > ${f%.md}.bb; done`
