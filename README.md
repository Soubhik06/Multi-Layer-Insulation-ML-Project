# Multi-Layer-Insulation-ML-Project
This project demonstrates how Genetic Algorithms (GA) can be used to optimize the thickness of multiple insulation layers in order to minimize heat loss.
It’s a practical example of how AI techniques can be applied in thermal engineering to improve energy efficiency.

We use a Genetic Algorithm from the pygad library to search for the optimal configuration of layer thicknesses.

The heat loss equation used is:

𝑄
=
Δ
𝑇
∑
𝐿
𝑖
𝑘
𝑖
Q=
∑
k
i
	​

L
i
	​

	​

ΔT
	​


Where:

𝑄
Q = Heat loss (W/m²)

Δ
𝑇
ΔT = Temperature difference across insulation

𝐿
𝑖
L
i
	​

 = Thickness of layer i (m)

𝑘
𝑖
k
i
	​

 = Thermal conductivity of layer i (W/m·K)
