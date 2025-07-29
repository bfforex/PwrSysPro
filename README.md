# PwrSysPro

**Advanced Transformer Sizing Tool**

PwrSysPro is a comprehensive web-based application designed for electrical engineers and professionals to accurately calculate transformer sizing requirements, electrical parameters, and associated system components according to NEC standards.

## Features

### Core Functionality
- **Transformer Sizing**: Calculates optimal transformer size based on load requirements with built-in safety factors
- **Multi-Phase Support**: Handles both single-phase and three-phase electrical systems
- **Load Type Optimization**: Applies appropriate safety factors for different load types:
  - Motor loads (1.25x safety factor)
  - Mixed loads (1.15x safety factor)
  - Lighting loads (1.1x safety factor)
  - Standard loads (1.0x safety factor)

### Advanced Calculations
- **Temperature Derating**: Automatic adjustment for ambient temperatures above 40°C
- **Voltage Drop Analysis**: Primary and secondary cable sizing with configurable voltage drop limits
- **Fault Current Calculation**: Determines available fault current and required KAIC ratings
- **OCPD Sizing**: Calculates primary and secondary overcurrent protection device requirements per NEC
- **Cable Sizing**: Determines appropriate conductor sizes for both primary and secondary circuits
- **Efficiency Analysis**: Calculates transformer efficiency based on loading conditions

### System Parameters
- **Voltage Systems**: Supports various primary and secondary voltage configurations
- **Conductor Materials**: Copper and aluminum conductor options
- **Transformer Types**: Dry-type and oil-filled transformer calculations with appropriate impedance values
- **Distance Calculations**: Handles both metric and imperial units for circuit distances
- **Standard Sizing**: Uses industry-standard transformer sizes (15 kVA to 5000+ kVA)

### Technical Specifications
- **Impedance Modeling**: Accurate transformer impedance calculations based on size and type
- **Current Calculations**: Full load current for both primary and secondary circuits
- **Power Factor Considerations**: Adjustable power factor settings for accurate kVA calculations
- **NEC Compliance**: All calculations follow National Electrical Code requirements

## Technology Stack
- **Frontend**: HTML5 with advanced JavaScript calculations
- **Language**: Primarily HTML (72,553 bytes)
- **Deployment**: Web-based application

## Usage
The tool provides an intuitive interface for entering system parameters and automatically calculates all relevant electrical values needed for transformer specification and system design.

## Repository Information
- **Repository**: bfforex/PwrSysPro
- **Version**: 1.0
- **Created**: Recently established
- **License**: Open source
- **Issues**: 1 open issue

## Contributing
This is a public repository welcoming contributions from the electrical engineering community. Feel free to submit issues, feature requests, or pull requests to improve the tool's functionality.

## Files Structure
The main application is contained in `pwrsyspro V1.0.html`, which includes all the calculation logic and user interface components.

---

*Note: This tool is designed to assist with electrical calculations but should not replace professional engineering judgment. Always verify calculations and consult local electrical codes and standards.*
