# Heat Exchanger Correlations for Hydrogen Aviation

This repository contains the computational fluid dynamics (CFD) research, poster, and project report investigating heat exchanger performance and empirical correlations for future liquid hydrogen powered turbofan engines.

The research was conducted at the **Whittle Laboratory, Department of Engineering, University of Cambridge** as part of the **King's Summer Research Programme (KSRP)** in collaboration with **King's College, Cambridge**.

---

## Abstract

Future hydrogen-powered jet engines require compact, low-pressure-drop heat exchangers to heat gaseous fuel prior to combustion. These aerospace applications necessitate tube bank designs with wide transverse spacings (e.g., $X_t^* = 6$), which fall far outside the valid geometric limits of existing empirical correlations in literature. 

Using 2D Unsteady Reynolds-Averaged Navier-Stokes (URANS) CFD simulations in Siemens Star-CCM+, this study demonstrates that extrapolating standard correlations (such as Gaddis & Gnielinski) overpredicts performance by nearly an order of magnitude. Dedicated piecewise log-linear correlations for the Stanton number ($St$) and friction factor ($f$) are derived for $X_t^* = 6$ geometries, identifying an optimal operating design point at $Re_d \approx 1,250$.

---

## Key Deliverables

* **Project Poster:** [`Poster`](./Dil_Patel_KSRP_Poster.pdf) — High-level summary presented at the KSRP research symposium.
* **Full Research Report:** [`Report`](./Dil_Patel_HX_Correlations_Report.pdf) — Full academic write-up detailing the validation, multi-lane domain studies, temperature/velocity scenes, and derived equations.

---

## Author & Acknowledgements

* **Author:** Dil H. H. Patel (King's College, University of Cambridge)
* **Supervisors:** Dr. Z. Raduev & Mr. K. P. Bartsch (Whittle Laboratory)
* **Funding & Support:** Supported by King's College, Cambridge through the philanthropic generosity of Lord Sainsbury and Peter Bennett, and the Department of Engineering, University of Cambridge.
