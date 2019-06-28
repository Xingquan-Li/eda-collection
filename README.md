# EDA-Collection
This is a collection of traditional electronic design automation surveys, courses, open source tools and books.

## Table of contents
 - [Books and Surveys]
 - [Courses and Tutorials]
 - [Open Source Tools (code available)]
 - [Open Access Tools (binary only)]

## Books and Surveys
### Overview
 - ICCAD 2015 Session 3D [From EDA to DA: Can We Evolve Beyond Our E-Roots?](https://www.mpassociates.com/events/proceedings.aspx?id=196--3-D)
 - DAC-2015 [DA Perspective Challenge](https://vlsicad.ucsd.edu/DAPerspectiveChallenge/competing-proposals.html)
 - CCC Visioning Activity 2014 [Extreme Scale Design Automation](https://cra.org/ccc/visioning/visioning-activities/2014-activities/extreme-scale-design-automation/)
### Synthesis
 - 2003 [Synthesis and Optimization of Digital Circuits](https://si2.epfl.ch/~demichel/publications/mcgraw/)
### Placement
 - 2015 [Progress and Challenges in VLSI Placement Research](http://doi.org/10.1109/jproc.2015.2478963)
### Routing

## Courses and Tutorials
 - Rob A. Rutenbar, [VLSI CAD Part I: Logic](https://www.coursera.org/learn/vlsi-cad-logic) and [VLSI CAD Part II: Layout](https://www.coursera.org/learn/vlsi-cad-layout)
 - Sung Kyu Lim, [ECE6133: Physical Design Automation of VLSI Systems](http://limsk.ece.gatech.edu/course/ece6133/)
 - David Z. Pan, [EE 382V: VLSI Physical Design Automation](http://users.ece.utexas.edu/~dpan/EE382V_PDA/)
 - Sanjit A. Seshia, [EECS 219C: Formal Methods: Specification, Verification, and Synthesis](https://people.eecs.berkeley.edu/~sseshia/219c/)
 - Chung-Kuan Cheng, [CSE245: Computer Aided Circuit Simulation and Verification](https://cseweb.ucsd.edu/classes/wi15/cse245-a/)
 - Gogul Ilango's notes [ASIC Design](https://gogul09.github.io/asic-design)

## Open Source Tools (code available)
### ASIC Flow
 - [OpenRoad](https://theopenroadproject.org/) (UCSD)
   - *Aim to develop open-source tools that achieve autonomous, 24-hour layout implementation.*
 - [Rsyn](https://github.com/RsynTeam/rsyn-x) (FURG)
   - *An Extensible Physical Synthesis Framework.*
 - [Qflow](http://opencircuitdesign.com/qflow/)
   - *A Digital Flow using Open Source EDA Tools.*
 - [gEDA](http://www.geda-project.org/)
   - *A full GPL'd suite and toolkit for electronics design, including schematic capture, attribute management, bill of materials (BOM) generation, netlisting into over 20 netlist formats, analog and digital simulation, and printed circuit board (PCB) layout.*
 - [Automata to Routing](https://github.com/jackwadden/Automata-to-Routing) (University of Virginia)
   - *An open-source toolchain to design and evaluate island style spatial automata processing architectures.*

### FPGA Flow
 - [VTR](https://github.com/verilog-to-routing/vtr-verilog-to-routing) (Toronto)
   - *An **CAD flow** tool for FPGA including ODIN-II, abc, vpr-place, vpr-route.*
 - [RapidWright](https://github.com/Xilinx/RapidWright.git) (Xilinx)
   - *Provide Vivado Interface for users to build customized FPGA implementations.*
   - Similar projects: [Torc](https://github.com/torc-isi/torc), [RapidSmith](http://rapidsmith.sourceforge.net/), and [RapidSmith2](https://github.com/byuccl/RapidSmith2)
 - [FPGA CAD Framework](https://github.com/EliasVansteenkiste/FPGA-CAD-Framework) ()
   - *A Java framework focused on rapid prototyping of new CAD algorithms for FPGA compilation.*
 - [Rebit](https://code.google.com/archive/p/rebit/)
   - *A low level configuration analysis and for the debugging and validation of the bitstream files of architectures that exploit dynamic partial reconfiguration on Xilinx FPGAs.*
 - [Sdaccel-chisel-integration](https://github.com/necst/sdaccel_chisel_integration)
   - *A wrapper in Chisel for using RTL kernels into SDAccel 2017.1.*
 - [hCODE](https://github.com/hCODE-FPGA/hCODE/tree/master/lib) (Kumamoto University)
   - *A tool to simplify the creation, sharing, and software integration of FPGA hardware accelerators.*
 - [IceStorm](http://www.clifford.at/icestorm/)
   - *Aims at reverse engineering and documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.*
 - [DATuner](https://github.com/cornell-zhang/datuner) (Cornell, PKU)
   - *A parallel bandit-based approach for autotuning FPGA compilation.*
 - [nextpnr](https://github.com/YosysHQ/nextpnr)
   - *A vendor neutral, timing driven, FOSS FPGA place and route tool.*

### High-level Synthesis
 - [LegUp](http://legup.eecg.utoronto.ca/) (Toronto)
   - *A **high-level synthesis** tool to improve C to Verilog synthesis without building an infrastructure from scratch.*
 - [GAUT](http://www.gaut.fr/) (Université Bretagne Sud)
   - *A high-level synthesis tool from algorithm to hardware architecture.*
 - [FCUDA](https://github.com/adsc-hls/fcuda) (ADSC High Level Synthesis Team)
   - *A source-to-source transformation framework that takes CUDA kernels with FCUDA annotation pragmas as input and produces a synthesizable C code.*
 - [PandA](https://panda.dei.polimi.it/) (Politecnico di Milano)
   - *A usable framework that will enable the research of new ideas in the HW-SW Co-Design field.*

### DSL and IR
 - [HeteroCL](https://github.com/cornell-zhang/heterocl) (Cornell, UCLA)
   - *A Multi-Paradigm Programming Infrastructure for Software-Defined Reconfigurable Computing.*
 - [FIRRTL](https://github.com/freechipsproject/firrtl) (Berkeley)
   - *An intermediate representation (IR) for digital circuits designed as a platform for writing circuit-level transformations.*


### Logic Synthesis
 - [ABC](https://github.com/berkeley-abc/abc) (Berkeley)
   - *A sequential logic synthesis and formal verification tool.*
 - [LLDHL](https://github.com/errordeveloper/llhdl)
   - *A logic synthesis and manipulation infrastructure for FPGAs.*
 - [Yosys](https://github.com/YosysHQ/yosys)
   - *A framework for Verilog RTL synthesis.*
 - [Icarus Verilog](https://github.com/steveicarus/iverilog)
   - *A Verilog simulation and synthesis tool compiling source code written in Verilog (IEEE-1364) into some target format.*

### Placement
 - [DREAMPlace](https://github.com/limbo018/DREAMPlace) (UT Austin)
   - *A GPU-accelerated analytical placement tool.*
 - OpenROAD [RePlAce](https://github.com/abk-openroad/RePlAce) (UCSD)
   - *A global placement tool with advancing solution quality and routability validation.*
 - [arachne-pnr](https://github.com/YosysHQ/arachne-pnr) (MIT)
   - *A place and route tool for FPGAs.*
 - Qflow [Graywolf](https://github.com/rubund/graywolf) (Yale)
   - *A placement tool in VLSI design and used together with qflow.*

### Routing
 - Qflow [Qrouter](http://opencircuitdesign.com/qrouter/)
   - *A detailed router based on the standard Lee maze router algorithm.*
 - [FGR](http://vlsicad.eecs.umich.edu/BK/FGR/) (UMich)
   - *A global router based on Lagrange Multipliers and won the 1st place in ISPD 2007 contest.*
 - [BoxRouter](https://www.cerc.utexas.edu/utda/download/BoxRouter.htm) (UT Austin)
   - *A global router for ultimate routability and won the 2nd place in ISPD 2007 contest.*
 - [NTHU-Route](http://www.cs.nthu.edu.tw/~tcwang/nthuroute/) (NTHU)
   - *A fast and stable global router and won the 1st place in ISPD 2008 contest.*
 - [FastRoute](http://home.engineering.iastate.edu/~cnchu/FastRoute.html) (Iowa State)
   - *A global routing tool for VLSI back-end design.*
 - [FLUTE](http://home.eng.iastate.edu/~cnchu/flute.html) (Iowa State)
   - *A very fast and accurate technique for rectilinear Steiner minimal tree (RSMT) construction.*

### Logic Simulation
 - [Verilator](https://www.veripool.org/wiki/verilator)
   - *A fast free Verilog/SystemVerilog simulator.*
 - [GHDL](https://github.com/ghdl/ghdl)
   - *An open-source simulator for the VHDL language.*
 - [Tkgate](https://github.com/bnoordhuis/tkgate)
   - *A digital circuit editor and simulator with a Tcl/Tk-based interface.*

### Timing Analysis
 - [OpenTimer](https://github.com/OpenTimer/OpenTimer) (UIUC)
   - *A High-Performance Timing Analysis Tool for VLSI Systems.*
 - OpenROAD [OpenSTA](https://github.com/abk-openroad/OpenSTA)
   - *A gate level static timing verifier.*

### Physical Verification
 - [Magic](http://opencircuitdesign.com/magic/)
   - *A VLSI layout editor, extraction, and DRC tool.*
 - [Netgen](http://opencircuitdesign.com/netgen/)
   - *A circuit netlist comparison (LVS) and netlist conversion tool*

### PDK and IP
 - [FreePDK](https://www.eda.ncsu.edu/wiki/FreePDK) (NC State)
   - *An open-source, Open-Access-based PDK for the 45nm technology node and the Predictive Technology Model.*
 - POSH [OpenFPGA](https://github.com/LNIS-Projects/OpenFPGA) (Utah)
   - *A **FPGA IP generator** using XML-based architecture description including three parts: FPGA-Verilog, FPGA-SPICE, FPGA-Bitstream.*
 - [OpenRAM](https://github.com/mguthaus/OpenRAM) (UCSC)
   - *An open-source memory compiler for VLSI circuits.*
 - [LibreCores](https://www.librecores.org/)
   - *A digital hardware design community for creating and distributing IP cores in the open source spirit*

### Parser
 - Verilog Parser [verilog-parser](https://github.com/ben-marshall/verilog-parser)
   - *A parser for the IEEE 1364-2001 verilog standard.*
 - Verilog Parser [pyverilog](https://pypi.org/project/pyverilog)
   - *A hardware design processing toolkit for Verilog HDL including verilog parser, dataflow analyzer, control-flow analyzer and code generator.*
 - Verilog Parser [hdlparse](https://kevinpt.github.io/hdlparse/)
   - *A simple package implementing a rudimentary parser for VHDL and Verilog.*
 - Liberty Parser [1](https://github.com/eclufsc/libertyParser)
 - Sdc Parser [1](https://github.com/dalance/sdc-parser)
 - Sdc Parser [2](https://www.synopsys.com/community/interoperability-programs/tap-in.html)
 - Lef/Def Parser [1](https://github.com/RazKarapetyan/LEF-DEF-parser)
 - Lef Parser [2](https://github.com/trimcao/lef-parser)
 - Lef/Def Parser [3](https://projects.si2.org/openeda.si2.org/projects/lefdef/)


## Open Access Tools (binary only)
### ASIC Flow
 - [DATC Robust Design Flow](https://github.com/jinwookjungs/datc_robust_design_flow) (IEEE CEDA)

### FPGA Flow

### High-level Synthesis
 - [FuseSoC](https://github.com/olofk/fusesoc/blob/master/doc/fusesoc.adoc)
   - *A package manager and a set of build tools for HDL code.*

### Placement
 - [ePlace](http://vlsi-cuda.ucsd.edu/~ljw/ePlace/index.html) (UCSD)
   - *An electrostatics based placer using Nesterov's method.*
 - [NTUplace](http://eda.ee.ntu.edu.tw/w04/download/ntuplace.php) (NTU)
   - *A ratio partitioning based placer for large-scale mixed-size designs.*
 - [FastPlace](http://vlsicad.eecs.umich.edu/BK/Slots/cache/www.public.iastate.edu/~nataraj/FastPlace.html) (Iowa State)
   - *An Analytical Placer for Large-scale VLSI Circuits.*
 - [mPL6](http://cadlab.cs.ucla.edu/cpmo/) (UCLA)
   - *Constrained placement by multilevel optimization.*
 - [Dragon](http://vlsicad.eecs.umich.edu/BK/Slots/cache/er.cs.ucla.edu/Dragon/) (UCLA)
   - *A fast, effective standard-cell placement tool for both variable-die and fixed-die ASIC design.*
 - [Capo](http://vlsicad.eecs.umich.edu/BK/PDtools/Capo/) (UMich)
   - *A fast and high-quality routability-driven placer for standard-cell ASICs.*

### Parser
 - Liberty Parser 
   - [1](https://metacpan.org/pod/Liberty::Parser)


