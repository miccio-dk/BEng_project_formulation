# Table of contents

* Abstract
* Introduction
  * Rationale
  * Problem formulation
  * System description
* Problem analysis
  * Requirements specification
    * Functional requirements
    * Non functional requirements
    * Use cases
  * Theoretical principles
    * Time-of-flight estimation
    * Position estimation
    * CAN Bus
  * Risk management
  * Milestone plan
* Design and implementation
  * Hardware
    * Devices setup
    * DecaWave module
    * Microcontroller
    * Sensors
  * Software
    * Project structure
      * Building environment
      * Tools
    * Hardware abstraction layer
      * ISP
      * EEPROM
      * UART
      * Timers (SCT, MRT, RIT, SysTick)
      * Real-time Clock
      * Watchdog
      * Internal temperature sensor
      * CRC and Flash signature engines
    * Software modules
      * decaWave module
      * Configuration manager
      * Command line interface
      * Time tracking
      * System self-test
    * UAVCAN
      * Protocol
      * Library
        * Drivers port
    * Processes
      * UAVCAN node
      * Sensor reading
      * Position estimator and publisher
      * Idle task
* Testing
  * Hardware tests
  * Software tests
  * Acceptance tests
* Conclusion
  * Product conclusion
  * Process conclusion
  * Possible improvements
* Literature
* Appendices
  * Glossary
  * End-user manual
  * Further material
    * Source code
    * Repository commit logs
    * Matlab scripts
    * Data and pictures from tests
    * Production files
    * Bill of materials
  
