# awesome-hardware-tools

A curated list of awesome open source hardware tools.

* Categorized
* Alphabetical (per category)
* Requirements
    * link should be to source code repository
	* open source projects only
	* working projects only (not WIP/rusty)
* One tag line sentence per project.

## Compiler Frameworks

* [act](https://github.com/asyncvlsi/act)
  * Asynchronous circuit compiler tools
* [amaranth](https://github.com/amaranth-lang/amaranth)
  * Python based hardware design framework
* [bsc](https://github.com/B-Lang-org/bsc)
  * Compiler, simulator, and tools for the Bluespec Hardware Description Language
* [calyx](https://github.com/cucapra/calyx)
  * Intermediate language and infrastructure for building compilers that generate custom hardware accelerators
* [chisel](https://github.com/chipsalliance/chisel3)
  * Scala based hardware description language
* [circt](https://github.com/llvm/circt)
  * Circuit IR Compilers and Tools
* [circuitgraph](https://github.com/circuitgraph/circuitgraph)
  * Tools for working with circuits as graphs in python
* [clash](https://github.com/clash-lang/clash-compiler)
  * Haskell to VHDL/Verilog/SystemVerilog compiler
* [coreir](https://github.com/rdaly525/coreir)
  * LLVM-style hardware compiler with first class support for generators
* [dfiant](https://github.com/DFiantHDL/DFiant)
  * Dataflow Hardware Descripition Language
* [firrtl](https://github.com/chipsalliance/firrtl)
  * Intermediate Representation for RTL
* [halide](https://github.com/halide/Halide)
  * Language for fast, portable data-parallel computation
* [halide-to-hardware](https://github.com/StanfordAHA/Halide-to-Hardware)
  * Hardware generator combining halide and coreir
* [hdlconvertor](https://github.com/Nic30/hdlConvertor)
  * Verilog/VHDL parser preprocessor and code generator for C++/Python based on ANTL4
* [livehd](https://github.com/masc-ucsc/livehd)
  * Infrastructure for live interactive synthesis and simulation
* [llhd](https://github.com/fabianschuiki/llhd)
  * Intermediate representation for digital circuit descriptions
* [magma](https://github.com/phanrahan/magma/)
  * Python based hardware design language
* [matchlib](https://github.com/NVlabs/matchlib)
  * SystemC/C++ library of commonly-used hardware functions and components that can be synthesized by most commercially-available HLS tools into RTL
* [matchclib_connections](https://github.com/hlslibs/matchlib_connections)
  * SystemC library implementing latency-insensitive channels for use by High-Level synthesis tools.
* [myhdl](https://github.com/myhdl/myhdl)
  * Python baed hardware description and verification language
* [panda](https://github.com/ferrandi/PandA-bambu)
  * High level synthesis (HLS) C/C++ framework
* [pipelinec](https://github.com/JulianKemmerer/PipelineC)
  * C-like hardware description language (HDL) with automatic pipelining
* [pygears](https://github.com/bogdanvuk/pygears)
  * Python based hardware design framework
* [pymtl3](https://github.com/pymtl/pymtl3)
  * Python hardware generation, simulation, and verification framework
* [pyrtl](https://github.com/UCSBarchlab/PyRTL)
  * Python integrated design and soimulation framework
* [pyverilog](https://github.com/PyHDI/Pyverilog)
  * Python design toolkit for Verilog HDL
* [rohd](https://github.com/intel/rohd)
  * Dart based framework for describing and verifying hardware
* [silice](https://github.com/sylefeb/Silice)
  * Language that simplifies prototyping and writing algorithms on FPGA architectures
* [spinalhdl](https://github.com/SpinalHDL/SpinalHDL)
  * Scala based HDL
* [spydrnet](https://github.com/byuccl/spydrnet)
  * Framework for analyzing and transforming Verilog netlists
* [surelog](https://github.com/chipsalliance/Surelog)
  * SystemVerilog IEEE 2017 Pre-processor, Parser, Elaborator, UHDM Compiler
* [sv-parser](https://github.com/dalance/sv-parser)
  * SystemVerilog IEEE 1800-2017 parser library
* [sv2v](https://github.com/zachjs/sv2v)
  * SystemVerilog to Verilog conversion
* [uhdm](https://github.com/chipsalliance/UHDM)
  * Unversal object model for IEEE SystemVerilog designs
* [verible](https://github.com/chipsalliance/verible)
  * Suite of SystemVerilog developer tools, including a parser, style-linter, and formatter
* [verilogger](https://github.com/PyHDI/veriloggen)
  * Mixed-Paradigm Hardware Construction Framework
* [verik](https://github.com/frwang96/verik)
  * Kotlin based hardware description language
* [xls](https://github.com/google/xls)
  * Google framework for hardware synthesis

## Build Systems

* [bazelhdl](https://github.com/hdl/bazel_rules_hdl)
  * Bazel based hdl build system
* [bender](https://github.com/pulp-platform/bender)
  * Dependency management tool for hardware projects.
* [chipyard](https://github.com/ucb-bar/chipyard)
  * Agile RISC-V SoC Design Framework.
* [cocoon](https://github.com/pku-dasys/cocoon)
  * An infrastructure for integrated EDA
* [edalize](https://github.com/olofk/edalize)
  * An abstraction library for interfacing EDA tools.
* [f4fpga](https://github.com/SymbiFlow/f4pga-arch-defs)
  * Architecture definitions of FPGA hardware
* [fusesoc](https://github.com/olofk/fusesoc)
  * Package manager and build abstraction tool for FPGA/ASIC development.
* [hammer](https://github.com/ucb-bar/hammer)
  * Agile physical design component part of UC Berkeley Chipyard framework.
* [hwtBuildsystem](https://github.com/Nic30/hwtBuildsystem)
  * Library of utils for interaction with the vendor tools.
* [legoHDL](https://github.com/c-rus/legoHDL)
  * Command line HDL package manager and development tool.
* [mflowgen](https://github.com/mflowgen/mflowgen)
  * Modular flow specification and build-system generator for ASIC and FPGA design-space exploration.
* [siliconcompiler](https://github.com/siliconcompiler/siliconcompiler)
  * Build system that automates translation from source code to silicon.

## Generators

* [bag](https://github.com/ucb-art/BAG_framework)
  * Berkeley analog generator
* [esp](https://github.com/sld-columbia/esp)
  * Design platform for heterogeneous SoC architecture and IP
* [fabulous](https://github.com/FPGA-Research-Manchester/FABulous)
  * FPGA fabric generator
* [fftgenerator](https://github.com/ucb-bar/FFTGenerator)
  * Berkeley FFT chisel based generator
* [garnet](https://github.com/StanfordAHA/garnet)
  * CGRA generator
* [gemmini](https://github.com/ucb-bar/gemmini)
  * Berkeley spatial array generator
* [lake](https://github.com/StanfordAHA/lake)
  * Generator for synthesizable memory modules
* [litex](https://github.com/enjoy-digital/litex)
  * Framework for FPGA and soc development
* [openfasoc](https://github.com/idea-fasoc/OpenFASOC)
  * Fully-Autonomous SoC Synthesis using Customizable Cell-Based Synthesizable Analog Circuits
* [openfpga](https://github.com/lnis-uofu/OpenFPGA)
  * FPGA IP Generator
* [openram](https://github.com/VLSIDA/OpenRAM)
  * Static random access memory (SRAM) compiler.
* [prga](https://github.com/PrincetonUniversity/prga)
  * Princeton python based FPGA generator
* [pymtl3-net](https://github.com/cornell-brg/pymtl3-net)
  * Parameterizable OCN (on-chip network) generator
* [revenoc](https://github.com/aignacio/ravenoc)
  * Configurable HDL NoC (Network-On-Chip) generator
* [rggen](https://github.com/rggen/rggen)
  * Configuration and status register generator
* [rocket](https://github.com/chipsalliance/rocket-chip)
  * Rocket chip chisel based generator
* [spiral](https://github.com/spiral-software/spiral-software)
  * FFT generator
* [systemrdl](https://github.com/SystemRDL/systemrdl-compiler)
  * Generic compiler front-end for Accellera's SystemRDL 2.0 register description language
* [kaktus2dev](https://github.com/kactus2/kactus2dev)
  * Graphical EDA tool based on the IP-XACT standard

## Board Design

* [boardview](https://github.com/whitequark/kicad-boardview)
  * Reads KiCAD PCB layout files and writes ASCII Boardview files
* [datasheet-scrubber](https://github.com/idea-fasoc/datasheet-scrubber)
  * Utility that scrubs through large sets of PDF datasheets/documents in order to extract key circuit information
* [kicad](https://github.com/KiCad/kicad-source-mirror)
  * Board design framework
* [skidl](https://github.com/devbisme/skidl)
  * Python module for electronic design
* [xschem](https://github.com/StefanSchippers/xschem)
  * Schematic editor for VLSI/Asic/Analog custom designs, netlist backends for VHDL, Spice and Verilog

## Synthesis

* [abc](https://github.com/berkeley-abc/abc)
  * System for Sequential Logic Synthesis and Formal Verification
* [lsoracle](https://github.com/lnis-uofu/LSOracle)
  * Famework built on EPFL logic synthesis libraries.
* [lstools](https://github.com/lsils/lstools-showcase)
  * Showcase examples for EPFL logic synthesis libraries
* [mockturtle](https://github.com/lsils/mockturtle)
  * C++ logic network library
* [yosys](https://github.com/YosysHQ/yosys)
  * Yosys Open SYnthesis Suite

## ASIC Layout

* [align](https://github.com/ALIGN-analoglayout/ALIGN-public)
  * Automatic layout generator for analog circuits
* [dreamplace](https://github.com/limbo018/DREAMPlace)
  * Deep learning toolkit-enabled VLSI placement
* [gds3d](https://github.com/trilomix/GDS3D)
  * Reads GDSII layout and renders in 3D.
* [gdsfactory](https://github.com/gdsfactory/gdsfactory)
  * Python package to generate GDS layouts.
* [gdstk](https://github.com/heitzmann/gdstk)
  * Gdstk (GDSII Tool Kit) is a C++/Python library for creation and manipulation of GDSII and OASIS files.
* [gdspy](https://github.com/heitzmann/gdspy)
  * Python module for creating GDSII stream files, usually CAD layouts.
* [klayout](https://github.com/KLayout/klayout)
  * Layout viewer
* [magic](https://github.com/RTimothyEdwards/magic)
  * VLSI Layout Tool
* [magical](https://github.com/magical-eda/MAGICAL)
  * Machine Generated Analog IC Layout
* [netgen](https://github.com/RTimothyEdwards/netgen)
  * LVS tool for comparing SPICE or verilog netlists
* [openlane](https://github.com/The-OpenROAD-Project/OpenLane)
  * Automated ASIC flow scripts baed on openroad, yosys, magic, netgen.
* [openroad](https://github.com/The-OpenROAD-Project/OpenROAD)
  * Complete RTL2GDS platform
* [phidl](https://github.com/amccaugh/phidl)
  * Python GDS layout and CAD geometry creation

## FPGA Layout

* [nextpnr](https://github.com/YosysHQ/nextpnr)
  * FPGA place and route tool
* [vtr](https://github.com/verilog-to-routing/vtr-verilog-to-routing)
  * FPGA place and route tool

## Formal Verification

* [boolector](https://github.com/boolector/boolector)
  * SMT solver for the theories of fixed-size bit-vectors, arrays and uninterpreted functions.
* [cvc5](https://github.com/cvc5/cvc5)
  * SMT automatic theorem prover
* [ilang](https://github.com/PrincetonUniversity/ILAng)
  * Princeton modeling and Verification Platform for SoCs using ILAs
* [pono](https://github.com/upscale-project/pono)
  * Extensible SMT-based model checker implemented in C++.
* [sby](https://github.com/YosysHQ/sby)
  * Front-end for Yosys-based formal verification flows.
* [z3](https://github.com/Z3Prover/z3)
  * Microsoft research theorem prover.

## Simulation and Analysis

* [anasysmod](https://github.com/sgherbst/anasymod)
  * Framework for FPGA emulation of mixed-signal systems
* [cocotb](https://github.com/cocotb/cocotb)
  * Coroutine based cosimulation library for writing VHDL and Verilog testbenches in Python
* [ghdl](https://github.com/ghdl/ghdl)
  * VHDL 2008/93/87 simulator.
* [icarus](https://github.com/steveicarus/iverilog.git)
  * Verilog IEEE-1364 simulator
* [libsystemctlm-soc](https://github.com/Xilinx/libsystemctlm-soc)
  * SystemC/TLM-2.0 Co-simulation framework
* [msdsl](https://github.com/sgherbst/msdsl)
  * Automatic generation of real number models from analog circuits
* [ngspice](http://ngspice.sourceforge.net/)
  * Spice simulator
* [opensta](https://github.com/The-OpenROAD-Project/OpenSTA)
  * Signoff quality STA engine used by OpenRoad
* [opentimer](https://github.com/OpenTimer/OpenTimer)
  * High perormance static timing analysis
* [qemu](https://github.com/qemu/qemu)
  * Generic and open source machine & userspace emulator and virtualizer
* [qucs](https://github.com/Qucs/qucs)
  * Itegrated circuit simulator with Graphical User Interface.
* [pact](https://github.com/peaclab/PACT)
  * Thermal Simulator
* [pyuvm](https://github.com/pyuvm/pyuvm)
  * SystemVerilog UVM written in Python
* [svreal](https://github.com/sgherbst/svreal)
  * Synthesizable real number library in SystemVerilog, supporting both fixed- and floating-point formats
* [verilator](https://github.com/verilator/verilator)
  * SystemVerilog simulator and lint system.
* [vunit](https://github.com/VUnit/vunit)
  * Unit testing framework for VHDL/SystemVerilog
* [xyce](https://github.com/Xyce/Xyce)
  * Parallel spice simulatiom engine from Sandia national labs.

## Waveform viewers

* [gtkwave](https://github.com/gtkwave/gtkwave)
  * GTK+ based VCD wave viewer
* [konata](https://github.com/shioyadan/Konata)
  * Instruction pipeline visualizer for Gem5
* [puselview](https://github.com/sigrokproject/pulseview)
  * Qt-based LA/scope/MSO GUI for sigrok
* [sigrok](https://github.com/sigrokproject)
  * Portable, cross-platform, sinal analysis software suite (logic analyzers, scopes, multimeters, and more)
* [sigrok-cli](https://github.com/sigrokproject/sigrok-cli)
  * Command line interface for sigrok
* [simview](https://github.com/pieter3d/simview)
  * Text-based SystemVerilog design browser and waveform viewer
* [sootty](https://github.com/Ben1152000/sootty)
  * Command-line tool for displaying vcd waveforms

## Benchmark Circuits

* [epfl-benchmarks](https://github.com/lsils/benchmarks)
  * Combinational Benchmark Suite for logic synthesis
* [bsg_pipeclean_suite](https://github.com/bespoke-silicon-group/bsg_pipeclean_suite)
  * Collection of designs used to stress test new CAD flows
* [corescore](https://github.com/olofk/corescore)
  * Benchmark for FPGAs and their synthesis/P&R tools
* [rdf-2019](https://github.com/ieee-ceda-datc/RDF-2019)
  * IEEE CEDA eda benchmark flow
* [opdb](https://github.com/PrincetonUniversity/OPDB)
  * Princeton design benchmark generators

## Documentation

* [graphviz](https://github.com/xflr6/graphviz)
  * Python library for graph cration and rendering in DOT language
* [pcbdraw](https://github.com/yaqwsx/PcbDraw)
  * Convert KiCAD board into 2D drawing suitable for pinout diagrams
* [pinion](https://github.com/yaqwsx/Pinion)
  * Generate interactive Diagrams for your PCBs
* [pinout](https://github.com/j0ono0/pinout)
  * Python package that generates hardware pinout diagrams as SVG images
* [sphinx](https://github.com/sphinx-doc/sphinx)
  * Document builder
* [symbolator](https://github.com/kevinpt/symbolator)
  * HDL symbol generator
* [wavedrom](https://github.com/wavedrom/wavedrom)
  * Digital timing diagram rendering engine
* [wavedrompy](https://github.com/wallento/wavedrompy)
  * Python comptabled Wavedrom module

## Other Awesome Lists

* [ben-marshall](https://github.com/ben-marshall/awesome-open-hardware-verification)
  * Hardware verification
* [clin99](https://github.com/clin99/awesome-eda)
  * EDA projects
* [delftopenhardware](https://github.com/delftopenhardware/awesome-open-hardware)
  * Open hardware materials
* [hdl](https://github.com/hdl/awesome)
  * Hardware description resources
* [pkuzjx](https://github.com/pkuzjx/eda-collection)
  * Open source EDA resources
* [drom](https://github.com/drom/awesome-hdl)
  * HDL languages
* [mattvenn](https://github.com/mattvenn/awesome-opensource-asic-resources)
  * ASIC resources
