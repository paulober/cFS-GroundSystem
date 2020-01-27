# Core Flight System : Framework : Tool : Ground System

This repository contains NASA's Lab Ground System (cFS-GroundSystem), which is a framework component of the Core Flight System.

This lab application is a non-flight utility ground system to interact with the cFS. It is intended to be located in the `tools/cFS-GroundSystem` subdirectory of a cFS Mission Tree.  The Core Flight System is bundled at https://github.com/nasa/cFS (which includes cFS-GroundSystem as a submodule), which includes build and execution instructions.

See Guide-GroundSystem.txt for more information.

## Version Notes

- 2.1.4: DEVELOPMENT
  - Finish conversion to python 3
  - cmdutil now accepts --word as alias to --long
  - See https://github.com/nasa/cFS-GroundSystem/pull/54
- 2.1.3: DEVELOPMENT
  - Minor updates to work with python 3
  - No longer compatible with python 2.7
  - Note issue #50 is to update the related documentation 
  - See https://github.com/nasa/cFS-GroundSystem/pull/47
- 2.1.2: DEVELOPMENT
  - Minor updates (see https://github.com/nasa/cFS-GroundSystem/pull/39)
- 2.1.1: DEVELOPMENT
  - Minor updates (see https://github.com/nasa/cFS-GroundSystem/pull/36)
- **2.1.0 OFFICIAL RELEASE**:
  - Minor updates (see https://github.com/nasa/cFS-GroundSystem/pull/26)
  - Released as part of cFE 6.7.0, Apache 2.0
- **2.0.90a OFFICIAL RELEASE**:
  - Released as part of cFE 6.6.0a, Apache 2.0

## Known issues

As a lab application, extensive testing is not performed prior to release and only minimal functionality is included.

## Getting Help

For best results, submit issues:questions or issues:help wanted requests at https://github.com/nasa/cFS.

Official cFS page: http://cfs.gsfc.nasa.gov

