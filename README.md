# WUDESIM
## Water Quality Model for Water Distribution Systems 

The first version was developed by Professor Ahmed A. Abokifa. The new version of the Washington University Dead End Simulator, WUDESIM, is coupled with a stochastic demand generator based on a nonhomogeneous Poisson process to simulate residential water demand pulses on fine time scales. 

**exe folder:** The executable files for WUDESIM.

WUDESIM incorporates EPANET programmers' toolkit and considers the advection-dispersion reaction in pipe reactions.

WUDESIM-BAM is a new version of WUDESIM which incorporates EPANET-BAM programmers' toolkit. WUDESIM-BAM considers the advection-dispersion reactionin pipes and incomplete mixing at cross junctions. 


**example folder:** The examples demostrate how to use WUDESIM. 

Including two examples, one is for exectuable file and the other is for toolkit of WUDESIM.

**toolkit folder:** The programmer's toolkit of WUDESIM. 



Using Windows command line to run WUDESIM.exe. The executable can be run directly from the command line and takes four command line arguments: *WUDESIM.exe EPANET.INP EPANET.RPT WUDESIM.INP WUDESIM.RPT*

    EPANET.INP ... Name of theEPANET input file
    EPANET.RPT ... Desired name for the EPANET report file
    WUDESIM.INP ... Name of the WUDESIM input file
    WUDESIM.RPT ... Desired name for the WUDESIM report file

