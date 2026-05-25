# XJTLU Formula Racing: Full-Stack Engineering and Optimization of the 2026 Season Steering System

This repository documents the complete development lifecycle, mathematical optimization, multi-body dynamics simulation, and hardware implementation of the steering system engineered for the XJTLU Formula Racing 2026 season vehicle. The project establishes a fully digitalized workflow ranging from algorithmic hardpoint optimization to physical manufacturing and cross-functional integration.

## Repository Architecture
The workspace is organized to reflect industrial product data management (PDM) standards:
```text
FSAE-2026-Steering-System/
├── README.md                      # Comprehensive technical overview and deployment guide
├── matlab-optimization/           # Kinematic solver and optimization algorithms
│   ├── steering_optimizer.m       # Main iterative optimization script
│   └── functions/                 # Vector loop and geometric closure helpers
├── cad-modeling/                  # CAD assemblies, manufacturing drawings, and logistics
│   ├── step-assembly/             # Universal STEP files for full system inspection
│   ├── engineering-drawings/      # Production-ready 2D PDFs with GD&T constraints
│   └── bill-of-materials.csv      # Component procurement and mass tracking ledger
├── adams-simulation/              # Multi-body dynamics validation workspace
│   ├── simulation_config.md       # Boundary conditions and kinematic parameters
│   └── plots/                     # Derived curves (Ackermann error, Bump Steer)
└── docs/                          # Technical documentation
    └── steering_design_report.pdf # Comprehensive engineering design report
