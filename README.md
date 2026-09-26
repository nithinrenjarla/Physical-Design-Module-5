# Physical-Design-Module-5
# SKY130 Physical Design – Routing, DRC, Parasitic Extraction.

# Overview
This module provides an overview of the major stages involved in the physical design flow using the SKY130 technology and OpenLane-based tools. It focuses on the practical implementation and verification of the routing and physical design processes.

The module covers the following key topics:

- Global routing and detailed routing techniques

- Maze routing using Lee’s Algorithm

- Intra-layer and inter-layer routing methodologies

- Routing topology optimization and connectivity management

- Preprocessed route guides and their role in detailed routing

- TritonRoute and its application in automated routing

- Design Rule Checking (DRC) for physical layout verification

- Verification of wire width, spacing, and via-spacing requirements

- Parasitic extraction and analysis

- Generation and interpretation of Standard Parasitic Exchange Format (SPEF) files

- OpenLane-based synthesis and routing results

- Verification of the complete physical design flow

- Analysis of routing results and identification of potential design-rule violations

Overall, this module provides practical knowledge of the routing, verification, and parasitic extraction stages required to transform a synthesized design into a physically valid layout using SKY130 and OpenLane.

# Tools and Technologies

| **Tool / Technology** | **Purpose** |
|---|---|
| **OpenLane** | Automated RTL-to-GDSII physical design flow |
| **SKY130** | Open-source 130 nm semiconductor process technology |
| **TritonRoute** | Detailed routing and design-rule-aware routing |
| **OpenROAD** | Physical design implementation and optimization |
| **OpenSTA** | Static Timing Analysis (STA) |
| **Magic** | Layout viewing, DRC, and physical verification |
| **LEF** | Library Exchange Format containing physical library information |
| **DEF** | Design Exchange Format containing physical design information |
| **SPEF** | Standard Parasitic Exchange Format for extracted parasitic data |
| **Linux / Ubuntu** | Execution environment for physical design tools |
| **Oracle VM VirtualBox** | Virtual machine environment for running Linux-based tools |
| **GitHub** | Version control, documentation, and project repository management |

# Log in
Sign up for free
You said:

Overview
This module covers the major stages involved in the physical design flow using the SKY130 technology and OpenLane-based tools.

The work includes:

Global and detailed routing
Maze routing using Lee's Algorithm
Design Rule Checking (DRC)
Wire-width and via-spacing verification
Parasitic extraction
SPEF generation
TritonRoute
Preprocessed route guides
Intra-layer and inter-layer routing
Routing topology optimization
Connectivity handling
OpenLane routing and synthesis results
Physical design flow verification.modify above information and give

ChatGPT said:
Here is a polished and more formal version of your module overview:

Module Overview – Physical Design Flow



Overview
This module provides an overview of the major stages involved in the physical design flow using the SKY130 technology and OpenLane-based tools. It focuses on the practical implementation and verification of the routing and physical design processes.

The module covers the following key topics:

Global routing and detailed routing techniques

Maze routing using Lee’s Algorithm

Intra-layer and inter-layer routing methodologies

Routing topology optimization and connectivity management

Preprocessed route guides and their role in detailed routing

TritonRoute and its application in automated routing

Design Rule Checking (DRC) for physical layout verification

Verification of wire width, spacing, and via-spacing requirements

Parasitic extraction and analysis

Generation and interpretation of Standard Parasitic Exchange Format (SPEF) files

OpenLane-based synthesis and routing results

Verification of the complete physical design flow

Analysis of routing results and identification of potential design-rule violations

Overall, this module provides practical knowledge of the routing, verification, and parasitic extraction stages required to transform a synthesized design into a physically valid layout using SKY130 and OpenLane.

This version is suitable for a lab manual, project report, internship report, or academic documentation.



You said:

Tools and Technologies
Tool / Technology	Purpose
OpenLane	Automated RTL-to-GDSII physical design flow
SKY130	Open-source 130 nm semiconductor process technology
TritonRoute	Detailed routing and design-rule-aware routing
OpenROAD	Physical design implementation and optimization
OpenSTA	Static Timing Analysis (STA)
Magic	Layout viewing and physical verification
LEF	Library Exchange Format containing physical library information
DEF	Design Exchange Format containing physical design information
SPEF	Standard Parasitic Exchange Format for extracted parasitic data
Linux / Ubuntu	Execution environment for the physical design tools
Oracle VM VirtualBox	Virtual machine environment used to run the Linux-based flow
GitHub	Version control and documentation of the workshop work.covert as github repo table to keep in my repo.

ChatGPT said:
Here is a clean GitHub README-style table you can directly add to your repository:

Tools and Technologies


Tools and Technologies
Tool / Technology	Purpose
OpenLane	Automated RTL-to-GDSII physical design flow
SKY130	Open-source 130 nm semiconductor process technology
TritonRoute	Detailed routing and design-rule-aware routing
OpenROAD	Physical design implementation, optimization, and routing
OpenSTA	Static Timing Analysis (STA) for timing verification
Magic	Layout visualization, design-rule checking, and physical verification
LEF	Library Exchange Format containing physical library and cell information
DEF	Design Exchange Format containing physical design and layout information
SPEF	Standard Parasitic Exchange Format containing extracted parasitic data
Linux / Ubuntu	Operating system environment for executing the physical design flow
Oracle VM VirtualBox	Virtual machine environment used to run the Linux-based EDA tools
GitHub	Version control, project documentation, and storage of design files and results

Technology Stack
RTL Design
    ↓
OpenLane
    ↓
OpenROAD
    ↓
Placement & Optimization
    ↓
TritonRoute
    ↓
Detailed Routing
    ↓
Magic / DRC
    ↓
Parasitic Extraction
    ↓
SPEF
    ↓
OpenSTA
    ↓
Timing & Physical Verification
    ↓
GDSII



You said:

repo table

ChatGPT said:
If you mean a simple table to put directly in your GitHub repository README, use this:

Tools and Technologies Repository Table


S.No.	Tool / Technology	Purpose
1	OpenLane	Automated RTL-to-GDSII physical design flow
2	SKY130	Open-source 130 nm semiconductor process technology
3	TritonRoute	Detailed routing and design-rule-aware routing
4	OpenROAD	Physical design implementation and optimization
5	OpenSTA	Static Timing Analysis (STA)
6	Magic	Layout viewing, DRC, and physical verification
7	LEF	Physical library and cell information
8	DEF	Physical design and layout information
9	SPEF	Extracted parasitic data
10	Linux / Ubuntu	Environment for running the physical design tools
11	Oracle VM VirtualBox	Virtual machine environment for Linux-based tools
12	GitHub	Version control, project documentation, and repository management



You said:

no, like |**tool**| like these.

ChatGPT said:
Got it — you want the raw Markdown table format with | separators, suitable for directly pasting into your GitHub README.md.

| **Tool / Technology** | **Purpose** |
|---|---|
| **OpenLane** | Automated RTL-to-GDSII physical design flow |
| **SKY130** | Open-source 130 nm semiconductor process technology |
| **TritonRoute** | Detailed routing and design-rule-aware routing |
| **OpenROAD** | Physical design implementation and optimization |
| **OpenSTA** | Static Timing Analysis (STA) |
| **Magic** | Layout viewing, DRC, and physical verification |
| **LEF** | Library Exchange Format containing physical library information |
| **DEF** | Design Exchange Format containing physical design information |
| **SPEF** | Standard Parasitic Exchange Format for extracted parasitic data |
| **Linux / Ubuntu** | Execution environment for physical design tools |
| **Oracle VM VirtualBox** | Virtual machine environment for running Linux-based tools |
| **GitHub** | Version control, documentation, and project repository management |



You said:

Introduction
Physical Design is an important stage in the VLSI design flow where the synthesized circuit is converted into a physical layout that can be fabricated on silicon.

In this module, the SKY130 technology and OpenLane-based physical design flow are explored with a focus on routing and post-routing analysis. The module covers global and detailed routing, maze routing using Lee's Algorithm, Design Rule Checking (DRC), wire-width and via-spacing verification, parasitic extraction, SPEF generation, and detailed routing using TritonRoute.

The practical work also covers route-guide preprocessing, intra-layer parallel routing, inter-layer sequential routing, connectivity handling, routing topology optimization, and inspection of OpenLane-generated synthesis and routing results.

The objective of this module is to understand how routing is performed while satisfying physical design rules, maintaining connectivity, and preparing the design for post-layout timing and physical verification

ChatGPT said:
Here is a polished GitHub README-ready Introduction in the same style:

## Introduction

Physical Design is a crucial stage in the VLSI design flow, where the synthesized circuit is transformed into a physical layout suitable for fabrication on silicon.

This module explores the **SKY130 technology** and the **OpenLane-based physical design flow**, with a primary focus on routing and post-routing analysis. It covers **global routing, detailed routing, maze routing using Lee's Algorithm, Design Rule Checking (DRC), wire-width and via-spacing verification, parasitic extraction, SPEF generation, and detailed routing using TritonRoute**.

The practical work also includes **route-guide preprocessing, intra-layer parallel routing, inter-layer sequential routing, connectivity management, routing topology optimization, and analysis of OpenLane-generated synthesis and routing results**.

The main objective of this module is to understand how routing is performed while satisfying physical design rules, maintaining proper connectivity, minimizing routing issues, and preparing the design for **post-layout timing analysis and physical verification**.



You said:

no modify the information

ChatGPT said:
Understood — you want the information itself modified/rephrased, not just formatted. Here is a revised version with different wording while keeping the same technical meaning:

## Introduction
Physical design is a fundamental stage in the VLSI design process, where the synthesized circuit is transformed into a physical layout suitable for implementation on silicon. It involves arranging the circuit components and establishing the required interconnections while satisfying various physical and manufacturing constraints.

This module focuses on the physical design flow using the SKY130 technology and OpenLane-based tools, with particular emphasis on routing and post-routing analysis. The major areas covered include global routing, detailed routing, maze routing using Lee’s Algorithm, Design Rule Checking (DRC), wire-width and via-spacing checks, parasitic extraction, SPEF generation, and detailed routing using TritonRoute.

The practical activities further explore route-guide preprocessing, intra-layer and inter-layer routing techniques, connectivity management, routing topology optimization, and the analysis of synthesis and routing results generated by OpenLane.

The objective of this module is to develop a clear understanding of the routing process, ensure that physical design rules and connectivity requirements are satisfied, and perform the necessary post-layout analysis for timing and physical verification.

# 1. Routing
Routing is a critical stage in the physical design process that establishes the required physical interconnections between standard cells, pins, and other circuit elements. The routing paths must be created while maintaining proper connectivity and adhering to the technology-specific design rules and physical constraints.

The major stages and activities involved in routing include:

- Global Routing – Determines the overall routing paths and allocates routing resources across different regions of the layout.

- Fast Routing – Generates routing solutions efficiently while considering connectivity and available resources.

- Detailed Routing – Creates precise physical wire connections while satisfying spacing, width, and via-related constraints.

- Design-Rule-Aware Routing – Ensures that the generated routes comply with the manufacturing and layout rules of the target technology.

- Connectivity Verification – Confirms that all required electrical connections are correctly established and that no unintended disconnections are present.

# 1.1 Route
The routing stage establishes physical connections between the input and output pins of the design through the available metal layers. It uses routing tracks and interconnect resources to connect components such as buffers, flip-flops, standard cells, and other circuit elements while maintaining the required design rules and connectivity.

Figure 1 – Routing Layout

III

# 2. Maze Routing – Lee's Algorithm
Maze routing is a grid-based routing method used to determine a feasible connection between a source and destination while avoiding obstacles present in the routing area. Lee's Algorithm systematically explores the routing grid and assigns distance values to the accessible cells until the destination is reached.

The main steps of Lee's Algorithm are:

- Source Initialization – The routing process begins at the specified source point.

- Grid Expansion – Neighboring cells are explored progressively from the source.

- Distance Assignment – Each reachable cell is assigned a distance value based on its position from the source.

- Destination Search – The expansion continues until the destination point is reached.

- Path Backtracking – The route is reconstructed by tracing back through cells with decreasing distance values to obtain a valid minimum-distance path.

Figure 2 – Maze Routing Using Lee's Algorithm

IIII

# 3. Design Rule Checking
Design Rule Checking (DRC) is an essential verification step in the physical design process. It checks whether the physical layout complies with the manufacturing and geometric rules specified by the selected semiconductor technology. DRC helps identify layout violations that could affect manufacturability or circuit reliability.

Common design rules include:

- Minimum Wire Width – Ensures that metal traces meet the required minimum width.

- Minimum Spacing – Verifies that sufficient distance is maintained between adjacent metal features.

- Via Spacing – Checks that vias are placed with the required minimum separation.

- Metal Enclosure – Ensures that vias and contacts are adequately enclosed by the surrounding metal layer.

- Layer-Specific Restrictions – Verifies that each metal and routing layer follows its corresponding technology rules.

- Connectivity Constraints – Confirms that the physical connections are correctly established without unintended shorts or open connections.

# 3.1 DRC Clean Layout
A DRC-clean layout is a physical layout in which no violations of the defined design rules are detected. Achieving a DRC-clean result indicates that the layout satisfies the relevant geometric and manufacturing constraints and can proceed to subsequent stages of physical verification.

Figure 3 – DRC Clean Layout

IIII

# 4. DRC – Via Spacing

Vias establish electrical connections between different metal layers in the layout.

Maintaining the required spacing between adjacent vias and nearby metal features is important to satisfy fabrication rules and avoid unwanted electrical shorts.

Figure 4 – Via Spacing

IIII

# 5.Parasitic Extraction

Once the routing stage is completed, the physical interconnections introduce unwanted parasitic components into the design.

Parasitic extraction is performed to determine these effects and understand their impact on circuit performance. The extracted information mainly includes:

- Resistance (R) of interconnects
  
- Capacitance (C) between wires and layers
  
- Propagation and interconnect delay

- Coupling effects between nearby signal nets

The extracted parasitic data is then used during post-layout timing analysis to obtain more realistic timing results and verify the performance of the final design.

Figure-5 – Parasitic Extraction

IIII

# 6.7. OpenLane Physical Design Flow
OpenLane automates several stages of the RTL-to-GDSII physical design flow.

A simplified flow is:

```text
RTL
 ↓
Synthesis
 ↓
Floorplanning
 ↓
Power Planning
 ↓
Placement
 ↓
CTS
 ↓
Routing
 ↓
DRC / LVS
 ↓
Parasitic Extraction
 ↓
Timing Analysis
 ↓
GDSII
```





