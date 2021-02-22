# Red Blood Cell 3D-Surface Triangulation
**Description:** A rough Python implementation of Evans, E. A., and R. Skalak (1980) Red Blood Cell Model. This implementation was developed in October 2019 for a Holographic Tomography application with red blood cell. 

**Colab:** [Click to run the source code on Google Colab.](https://drive.google.com/file/d/1EvKv088ijMo53aoazquB1AYNNe0wLY9R/view?usp=sharing)

# Specs
- **Programming Language:** `Python V3.6.9.`
- **numpy:** `V1.18.5` 
- **matplotlib:** `V3.3.2` 

# Overview
> <img src="https://render.githubusercontent.com/render/math?math=z=\pm D_0 \sqrt{1 - \frac{4(x^2+y^2)}{D_{0}^2}} \left( a_0 + \frac{a_1(x^2+y^2)}{D_{0}^2}+\frac{a_2(x^2+y^2)^2}{D_{0}^4}\right).">

Starting from the above equation for the average unstressed shape of a single Red Blood Cell, according to Evans, E.A., and R. Skalak [1, 1980], I computed the RBC surface and its projection using [NumPy](https://numpy.org/doc/stable/) and [MatplotLib](https://matplotlib.org/contents.html).


![](RBC_Implementation.gif)

# Author 

Created and maintained by [@camponogaraviera][1].

[1]: https://github.com/camponogaraviera

# References

\[1] Evans, E.A., and R. Skalak. 1980. Mechanics and Thermodynamics of Biomembranes. CRCPress, BocaRaton, FL.

\[2] Paul O'Leary, 2014, "Shape of an unstressed RBC according to Evans and Skalak".


# License

This work is licensed under a [Creative Commons Zero Attribution v1.0 Universal](LICENSE) license.
