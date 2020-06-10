# gempy_to_gimli
Create geological models in GemPy and transfer them to pyGIMLI &amp; vice versa

Geological models are created with GemPy (currently v.2.2.2). An arbitrary 2D-section-geometry is taken from GemPy and transferred into a piecewise linear complex using pyGIMLI, which can then be used to calculate physical forward responses, run inversions or do general FE modelling stuff.

The goal is to integrate the geological modelling and geophysical inversion process by incorporating a GemPy model as 'a-priori' information to constrain the usually underdetermined inversion problem. 
This opens up potentials to combine data-driven geophysical modelling with the power of implicit modelling to reach the goal of obtaining subsurface models that both fit geophysical data and comply with previous geological knowledge.
