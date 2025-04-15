# StellarBrace: EMG-Controlled Robotic Elbow Orthosis

**Developed at Tecnológico de Monterrey - Campus Ciudad de México**  
**Team Members**:  
- Jesús Melchisedec Vásquez López  
- Ariadna Laurent Cienfuegos  
- Ángel Manuel Salinas López  
- Joel Yedra Valdespino  

## Project Overview
StellarBrace is an innovative robotic orthosis designed to assist individuals with motor impairments (particularly age-related muscle weakness) in elbow flexion/extension. The system interprets muscle activation through EMG signals and responds with proportional mechanical assistance via a microcontroller-driven actuation system.

**Award**: 1st Place in Bioinstrumentation at Tec de Monterrey's BioHack 2023

## Technical Implementation
### Core Systems Integration
- **Bioinstrumentation**:  
  - EMG signal acquisition  
  - Custom signal conditioning (bandpass filtering 20-500Hz, amplification)  
  - Noise reduction algorithms  

- **Embedded Control**:  
  - ESP32-based actuation control  
  - PWM-driven motor output  
  - Safety interlocks and fault detection  

- **Mechanical Design**:  
  - Lightweight (under 400g) 3D-printed exoskeleton  
  - Ergonomic joint alignment  
  - Adjustable arm interface  

## Development Highlights
- Achieved TRL2 prototype maturity  
- Implemented real-time response  
- Cost-effective solution   

## Key Features
| System Component | Implementation Details |
|------------------|------------------------|
| **EMG Processing** | Custom PCB |
| **Signal Processing** | Envelope detection algorithm |
| **Mechanical Design** | SolidWorks 360-optimized linkage system |
