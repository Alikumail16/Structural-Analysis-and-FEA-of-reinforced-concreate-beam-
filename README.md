# Finite Element Analysis of Reinforced-Concrete Beam with Shape Memory Alloy Under Bending
Overview
design and fea 

This project presents a finite element analysis (FEA) study investigating the structural behavior of reinforced concrete beams strengthened with Shape Memory Alloy (SMA) rods — specifically NiTi (Nitinol) — under bending conditions. The study compares the performance of beams reinforced with traditional steel (400C) against beams incorporating NiTi SMA inserts at the zones of maximum stress.
Objectives

Model and analyze reinforced concrete beams under 3-point and 4-point bending using FEM
Evaluate the effect of NiTi SMA rods on deflection, residual deformation, and stress distribution
Demonstrate the superelastic behavior of NiTi alloy and its structural benefits over conventional reinforcement

Methodology
Materials

Concrete: C20/25 grade
Steel reinforcement: 400C (2Ø12 mm working bars)
SMA inserts: NiTi (Nitinol) rods — 2Ø8 mm, placed at maximum stress zones

Beam Geometry

Dimensions: 140 × 80 × 1200 mm
SMA inserts span the central 120 mm zone (flanked by 540 mm steel sections on each side)

Material Properties (NiTi)
PropertyValueDensity6.45 g/cm³Young's Modulus68.2 GPaPoisson's Ratio0.36Start stress (A→M)407.5 MPaFinish stress (A→M)428.3 MPaMax recoverable strain6%
Loading

Applied force: 218 kN (selected to activate superelastic effect in NiTi rods)
Two loading configurations: 3-point and 4-point bending
Two loading cycles performed to assess residual behavior

Key Results
Deflection
Bending TypeReinforcementMax Deflection (mm)Residual Deflection (mm)3-pointNiTi + 400C18.61.163-pointOnly 400C18.41.524-pointNiTi + 400C15.41.004-pointOnly 400C15.41.37

Residual deflection reduced by 24% under 3-point bending with NiTi rods
Residual deflection reduced by 27% under 4-point bending with NiTi rods

Stress

Maximum stresses in NiTi rods: 408 MPa (within superelastic range)
Residual stresses in NiTi rods were 2.3–4.3% lower than in conventional steel reinforcement across loading cycles

Conclusions

SMA (NiTi) reinforcement significantly reduces residual deflections compared to traditional steel reinforcement
The superelastic effect of NiTi allows structural recovery after loading, preventing permanent deformation
NiTi rods are most effective at zones of maximum stress and are a viable alternative reinforcement strategy for structures operating under significant or repeated loading
The FEM model error compared to experimental values was within 5%, confirming model validity

Tools & Software

FEM Solver: ANSYS 2019 R2
Analysis type: Linear structural analysis
Thermomechanical characterization: Differential Scanning Calorimetry (DSC)

Author
Ali Kumail
References
Key references used in this study include works by Almeida et al. (2020), Ayoub et al. (2004), Bykiv et al. (2020, 2021), Fang et al. (2019), Gholampour & Ozbakkaloglu (2018), Hamid et al. (2018), Menna et al. (2015), Morais et al. (2017), and Zafar & Andrawes (2015).
