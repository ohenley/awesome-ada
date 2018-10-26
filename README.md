# Awesome Ada [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome resources and other links related to the Ada programming language.

## OS/Kernel
- [marte_os](https://marte.unican.es/) - MaRTE OS is a Hard Real-Time Operating System for embedded applications that follows the Minimal Real-Time POSIX.13 subset. It provides an easy to use and controlled environment to develop Multi-Thread Real-Time applications. 
- [muen](https://muen.codelabs.ch/) - An x86/64 Separation Kernel for High Assurance

## Frameworks

#### GUI
- [gnoga](https://sourceforge.net/projects/gnoga/) - The GNU Omnificent GUI for Ada
- [claw](http://www.rrsoftware.com/html/prodinf/claw/claw.htm) - CLAW, a High Level, Portable, Ada 95 Binding for Microsoft Windows : ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `binding to OS`
- [gtkada](http://libre.adacore.com/libre/tools/gtkada/) - Ada graphical toolkit based on Gtk3 components : ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `binding to 3rd party`

### 3D

- [globe_3d](https://globe3d.sourceforge.io/) - GL Object Based Engine for 3D
- [orka](https://github.com/onox/orka) - The OpenGL 4.6 Rendering Kernel in Ada 2012

### Web
- [aws](https://github.com/AdaCore/aws) - AWS is a complete framework to develop Web based applications in Ada.
- [awa](https://github.com/stcarrez/ada-awa) - Ada Web Application is a framework to build a Web Application in Ada 2012. The framework provides several ready to use and extendable modules that are common to many web application. This includes the login, authentication, users, permissions, managing comments, tags, votes, documents, images.
- [matreshka](http://forge.ada-ru.org/matreshka) - Matreshka is an Ada framework to develop information systems.  It consists
of five major components: League, XML processor, Web framework, SQL access,
and the Modeling framework.

### Unit Test
- [ahven](http://ahven.stronglytyped.org/) - Ahven is a simple unit test library and framework for the Ada programming
lanugage.  It is loosely modelled after JUnit and some ideas from AUnit.
- [aunit](http://libre.adacore.com/tools/aunit/) - Ada unit testing framework

### Logging
- [alog](https://www.codelabs.ch/alog/) - Alog is a stackable logging framework for Ada

## Libraries

### Algorithm, containers and protocols
- [libadacrypt](	https://github.com/cforler/Ada-Crypto-Library) - This is a crypto library for Ada with a nice API and is written for the i386 and x86_64 hardware architecture
- [simple_components](http://www.dmitry-kazakov.de/ada/components.htm) - Implementation of various algorythn, containers or protocols
- [pragmarc](http://pragmada.x10hosting.com/pragmarc.htm) - PragmAda Reusable Components (PragmARCs) from PragmAda S/W Engineering
- [booch95](https://sourceforge.net/projects/booch95/) - The Ada 95 Booch components are a port of Grady Booch's C++ components.
- [gnatcoll](http://libre.adacore.com/tools/gnat-component-collection) - GNAT Component Collection from Adacore
- [ada_id](https://github.com/anthony-arnold/AdaID) - Simple Ada library for generating UUIDs

### Parsers/scanners
- [aflex_ayacc](http://thiberlog.free.fr/) - Ada95 scanner and parser generators
- [adacontrol](http://www.adalog.fr) - Ada constructs lint tool
- [opentoken](http://stephe-leake.org/ada/opentoken.html) - Lexical analyser and parser for the Ada language

### Format reader/writer
- [ini_file_manager](https://sourceforge.net/projects/ini-files) - The Ini file manager consists of a package, Config, which can read and modify informations from various configuration files known as "ini" files.
- [adayaml](https://github.com/yaml/AdaYaml) - experimental YAML 1.3 implementation in Ada https://ada.yaml.io/
- [json_ada](https://github.com/onox/json-ada) - An Ada 2012 library for parsing JSON
- [xmlada](https://github.com/AdaCore/xmlada) - The XML/Ada toolkit
- [xml_ez_out](http://www.mckae.com/xmlEz.html) - Library for emitting XML from Ada programs
- [excel_writer](http://excel-writer.sourceforge.net) - Create Excel files with basic formats
- [generic_image_decoder](http://gen-img-dec.sourceforge.net/) - Multi-format image decoder library for Ada
- [zip_ada](http://unzip-ada.sourceforge.net/) - Zip-Ada is a programming library for dealing with the Zip compressed archive file format.

### Network
- [anet](https://www.codelabs.ch/anet/) - Anet is a networking library for the Ada programming language.
- [adasockets](http://www.rfc1149.net/devel/adasockets.html) - IPv4 socket library (TCP, UDP, and multicast)
- [adhcp](https://codelabs.ch/adhcp/index.html) - ADHCP is an implementation of the DHCP protocol in Ada

## Applications

## Web
- [ironsides](http://ironsides.martincarlisle.com) - Authoritative DNS server verified by SPARK/Ada

### Generators
- [adabrowse](http://home.datacomm.ch/t_wolf/tw/ada95/adabrowse) - HTML generator for Ada95 library unit specs
- [coldframe](https://github.com/simonjwright/coldframe) - ColdFrame generates Ada framework code and documentation from UML models

### Package/Build
- [gprbuild](http://docs.adacore.com/live/wave/gprbuild/html/gprbuild_ug/gprbuild_ug.html) - Adacore multi-language software build tool
- [ravenadm](https://github.com/jrmarino/ravenadm) - Administration tool for Ravenports http://www.ravenports.com
- [alire](https://github.com/alire-project/alire) - A catalog of ready-to-use Ada libraries plus a command-line tool (alr) to obtain, compile, and incorporate them into your own projects. It aims to fulfill a similar role to Rust's cargo or OCaml's opam
- [synth](https://github.com/jrmarino/synth) - Next D/Ports build tool for live systems (Alternative for Portmaster and Portupgrade tools)

## Bindings

- [adacurses](http://invisible-island.net/ncurses/ncurses-Ada95.html) - Ada95 bindings for ncurses
- [florist](https://www.cs.fsu.edu/~baker/florist.html) - POSIX Ada binding, IEEE Standards 1003.5(b,c)
- [sdlada](https://github.com/Lucretia/sdlada) - Ada 2012 bindings to SDL 2
- [pcsc_ada](http://www.codelabs.ch/pcscada) - PCSC/Ada provides a thick Ada binding to PC/SC-middleware. The library
allows programs written in Ada to communicate with smart cards using the
SCard API.
- [lua_ada](https://github.com/AdaCore/ada-lua) - Ada binding for Lua
- [adabase](http://jrmarino.github.io/AdaBase/) - Thick database bindings for MySQL, PostgreSQL and SQLite written in Ada.
- [apq_base](http://www.ravenports.com/catalog/bucket_F2/apq-base/standard/) - APQ is a database interface library written in Ada95
- [cuda_ada](https://codelabs.ch/cuda-ada/index.html) - CUDA/Ada is an Ada binding to NVIDIA’s CUDA parallel computing platform and programming model
- [dbus_ada](https://codelabs.ch/dbus-ada/index.html) - The D_Bus/Ada library provides an Ada binding to the D-Bus message bus system.




