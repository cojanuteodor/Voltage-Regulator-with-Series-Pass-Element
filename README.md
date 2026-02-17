# Voltage Regulator with Series Pass Element


## Specifications
- Adjustable output voltage: 2.5 V – 5 V  
- Input voltage range: 9 V – 10 V  
- Load resistance: 250 Ω  
- Maximum output current: 0.4 A (current limiting)  
- Thermal protection: series pass transistor limited to 100 °C  
- Thermal drift: < 2 mV/°C  
- Operating temperature range: 0 °C to 70 °C  
- Minimum open-loop voltage gain of error amplifier: ≥ 200  
- LED indicators for input and output voltage presence  

## Design Overview
The regulator is based on a linear series pass topology, where the output voltage is controlled by an error amplifier that compares a reference voltage with a feedback fraction of the output voltage. The series pass transistor operates in the linear region to regulate the output voltage under varying load and input conditions.

Main functional blocks:
- Reference voltage generator  
- Error amplifier (high open-loop gain)  
- Series pass element (BJT or MOSFET in SMD package)  
- Current limiting and thermal protection circuit  
- LED indicators for Vin and Vout  

## Implementation
- Technology: SMT & PCB  
- PCB size: 40 mm × 40 mm  
- Substrate: FR4, double-layer  
- Components: SMD 0805 passives, SMD transistors (SOT-23 / DPAK)  
- CAD Tools: OrCAD Capture & PCB Editor (Lite)  
- Simulation: PSPICE  

## Project Files
- Schematic and simulation files (PSPICE)  
- PCB layout (TOP/BOTTOM layers, solder mask, silk screen, mechanical layer)  
- Gerber files (RS-274X) and Excellon drill file  
- Bill of Materials (BOM)  
- Design documentation and calculations  

## Testing and Validation
The circuit was verified through:
- DC operating point analysis  
- Load regulation and line regulation simulations  
- Thermal behavior analysis of the series pass transistor  
- Functional testing of current limiting and thermal protection  
- Verification of output voltage range for N = 5  

## Notes
- All passive components use standard values and SMD 0805 packages.  
- Semiconductor devices are selected from standard catalogs.  
- The PCB layout follows IPC standards (IPC-2221A, IPC-7527, IPC-A-610).  



