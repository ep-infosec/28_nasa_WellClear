![](docs/DAIDALUS.jpeg "")

**Current version of DAIDALUS v2 is available from [https://github.com/nasa/daidalus](https://github.com/nasa/daidalus)**
========

Detect and AvoID Alerting Logic for Unmanned Systems
========

This repository includes a prototype implementation written in Java and
C++ of DAIDALUS (Detect and Avoid Alerting Logic for Unmanned Systems).
DAIDALUS is a reference implementation of a detect and avoid concept
intended to support the integration of Unmanned Aircraft Systems into
civil airspace.
The repository also includes definitions in Matlab of a family of
well-clear violation volumes and the formal specification
of DAIDALUS core algorithms in the Prototype Verification System ([PVS](http://pvs.csl.sri.com)).

DAIDALUS is a
reference implementation of the detect and avoid (DAA) functional
requirements  described in
Appendix G of DO-365, the Minimum Operational Performance Standards (MOPS)
for Unmanned Aircraft Systems (UAS)  developed by RTCA
Special Committee 228 (SC-228). The current software release implements

*  detection logic,
*  alerting logic based on hazard and non-hazard volumes, and
*  multi-level instantaneous and kinematic maneuver guidance.

### Documentation

A draft of user guide is available at https://nasa.github.io/WellClear. 

Example programs [`DaidalusExample.java`](DAIDALUS/Java/src/DaidalusExample.java) and 
[`DaidalusExample.cpp`](DAIDALUS/C++/src/DaidalusExample.cpp) illustrate the main 
functional capabilities of DAIDALUS in Java and C++, respectively.

For technical information about the definitions and algorithms in this
repository, visit https://shemesh.larc.nasa.gov/fm/DAIDALUS.

### Current Release

The release in this repository is DAIDALUSv1.0.2.
**The current version of DAIDALUS v2 is available from [https://github.com/nasa/daidalus](https://github.com/nasa/daidalus).**

### License

The code in this repository is released under NASA's Open Source
Agreement.  See the directory [`LICENSES`](LICENSES); see also the copyright notice at the end of this file. 

### Contact

[Cesar A. Munoz](http://shemesh.larc.nasa.gov/people/cam) (cesar.a.munoz@nasa.gov), NASA Langley Research Center.

### Logo

The DAIDALUS logo was designed by 
[Mahyar Malekpour](http://shemesh.larc.nasa.gov/people/mrm/publications.htm#ETC), NASA Langley Research Center.

### Copyright Notice

Copyright 2016 United States Government as represented by the Administrator of the National Aeronautics and Space Administration. All Rights Reserved.

No Warranty: THE SUBJECT SOFTWARE IS PROVIDED "AS IS" WITHOUT ANY WARRANTY OF ANY KIND, EITHER EXPRESSED, IMPLIED, OR STATUTORY, INCLUDING, BUT NOT LIMITED TO, ANY WARRANTY THAT THE SUBJECT SOFTWARE WILL CONFORM TO SPECIFICATIONS, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR FREEDOM FROM INFRINGEMENT, ANY WARRANTY THAT THE SUBJECT SOFTWARE WILL BE ERROR FREE, OR ANY WARRANTY THAT DOCUMENTATION, IF PROVIDED, WILL CONFORM TO THE SUBJECT SOFTWARE. THIS AGREEMENT DOES NOT, IN ANY MANNER, CONSTITUTE AN ENDORSEMENT BY GOVERNMENT AGENCY OR ANY PRIOR RECIPIENT OF ANY RESULTS, RESULTING DESIGNS, HARDWARE, SOFTWARE PRODUCTS OR ANY OTHER APPLICATIONS RESULTING FROM USE OF THE SUBJECT SOFTWARE.  FURTHER, GOVERNMENT AGENCY DISCLAIMS ALL WARRANTIES AND LIABILITIES REGARDING THIRD-PARTY SOFTWARE, IF PRESENT IN THE ORIGINAL SOFTWARE, AND DISTRIBUTES IT "AS IS."

Waiver and Indemnity: RECIPIENT AGREES TO WAIVE ANY AND ALL CLAIMS AGAINST THE UNITED STATES GOVERNMENT, ITS CONTRACTORS AND SUBCONTRACTORS, AS WELL AS ANY PRIOR RECIPIENT.  IF RECIPIENT'S USE OF THE SUBJECT SOFTWARE RESULTS IN ANY LIABILITIES, DEMANDS, DAMAGES, EXPENSES OR LOSSES ARISING FROM SUCH USE, INCLUDING ANY DAMAGES FROM PRODUCTS BASED ON, OR RESULTING FROM, RECIPIENT'S USE OF THE SUBJECT SOFTWARE, RECIPIENT SHALL INDEMNIFY AND HOLD HARMLESS THE UNITED STATES GOVERNMENT, ITS CONTRACTORS AND SUBCONTRACTORS, AS WELL AS ANY PRIOR RECIPIENT, TO THE EXTENT PERMITTED BY LAW.  RECIPIENT'S SOLE REMEDY FOR ANY SUCH MATTER SHALL BE THE IMMEDIATE, UNILATERAL TERMINATION OF THIS AGREEMENT.
