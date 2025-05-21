# FAF-NEKTAR-PBL-SEM4
Design of The Domain Specific Languages

## Name of the Project: NEKTAR - Network KiT for Augmented Reality

### Links over components of the project
1. [Back-end Server Repository](https://github.com/alexandru-bujor/DSL)
2. [Front-end React Repository](https://github.com/Darzu-Catalin/NEKTAR_FE)
3. [iOS Application](https://github.com/AlexDandy77/NEKTAR-Application)
4. [Overleaf Report](https://ru.overleaf.com/read/qnqkspbcxrkf#dff4d0)

## The Team:
The project titled "NEKTAR - Visualizing the Networks with Augmented Reality" was developed by students Alexei Pavlovschii, Andrei Bobeica, Alexandru Bujor, Cătălin Dârzu, and Mihai Mustea from the Technical University of Moldova.

## Project Description
It proposes a structured, text-based Domain-Specific Language (DSL) to describe network topologies, with an additional feature for transforming Cisco Packet Tracer topologies into simplified DSL-syntax description and React flow topology. 

The grammar enforces a strict hierarchy of elements—networks, devices, interfaces, and links—ensuring consistency and error checking during both manual editing and automated conversion. A custom lexer identifies tokens such as IP addresses, numeric bandwidth values, and keywords (e.g., “device,” “network”), which the parser then assembles into a tree-like representation. 

Testing scenarios confirm that typical network configurations, including coordinates and link properties, are accurately preserved and translated. The project’s current capabilities not only simplify version-controlling and collaboration for network configurations but also pave the way for integrating these textual descriptions with emerging technologies. 

## Main Components:
The solution consists of two main parts - Web-based IDE and Native iOS application. Users can design, save and manage topologies for their further visualization in the Application using Augmented Reality.
