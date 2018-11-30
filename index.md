---
title:
layout: default
---

# Introducing
OperatorFabric is an open source framework written in Java, that makes it easy to write software for coordination.

# The well named OperatorFabric (AKA OpFab || OF)
OperatorFabric therefore exists to facilitate and improve cooperation between Operators on the basis of industrial processes (whatever their business, by the way)!
- Operator represents human being ... let's say operating in control room
- Fabric, from a modern digital perspective, is used as a metaphor to illustrate the idea of a simple work for building softwares

When we started this project it felt kind of natural to call it OperatorFabric (given what it does, allowing the building of a coordination system between operators).  Then with time operatorfabric got its shortname: OpFab (I guess I don’t need to explain).
And in the end, in emails and presentations and such, we started referring to it with an even smaller form: OF.

# Open source
OperatorFabric is part of the [LF Energy Foundation](http://www.lfenergy.org), 
a project of The Linux Foundation that supports open source innovation projects within the energy and electricity sectors.

OpFab is in an open source framework licensed under the [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/).
The source code is hosted on GitHub in those repositories:
- [of-core](https://github.com/bdotest/of) contains all the core features
- [of-core](https://github.com/bdotest/of) contains all the core features

# Features
Powsybl provides IIDM (iTesla Internal Data Model), a complete grid model (substations, voltage levels, AC and DC lines,
two and three windings transformers, generators, loads, shunt and static VAR compensators...). The grid model can be
extended with extensions to complete the modelling of the equipments. It also provides importers and exporters for several
common exchange formats ([Entso-E CIM/CGMES](https://www.entsoe.eu/digital/common-information-model/cim-for-grid-models-exchange/),
[UCTE-DEF](https://cimug.ucaiug.org/Groups/Model%20Exchange/UCTE-format.pdf)...).

Powsybl provides several API for power systems' simulations and analysis (power flow computations, security analysis,
remedial action simulations, short circuits computations, sensitivity computations, time domain simulations...). These
simulations can run either on a personal computer or on a server, but they can also run on a supercomputer like in the
[iTesla](http://www.itesla-project.eu) project with [Curie](http://www-hpc.cea.fr/en/complexe/tgcc-curie.htm) supercomputer.
The separation of the simulation API and the implementations allows developers to provide their own implementation.

Powsybl is available as a command line tool or in a complete desktop application, based on the GSE (Grid Study Environment)
project. The GSE project is part of the powsybl framework. It provides a JavaFX UI to help developers writing desktop
applications based on the powsybl framework. The GSE is fully customizable and extendable with plugins. All the features
of powsybl are also exposed as web services.
