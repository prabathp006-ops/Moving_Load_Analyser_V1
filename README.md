Moving Load Analyzer (Jupyter Notebook)
This program simulates the effect of a moving vehicular load on a simply supported beam. It calculates critical shear forces and bending moments as the load traverses the span.

1. 🚗 Moving Load Simulation: Load moves from the left support to the right support.

2. 📍 Load Positioning: Defined by the distance from the left support to the leftmost wheel load.

3. 📝 Inputs
	3.1 - Span length in m
	3.2 - Point of interest in m (location on span where critical forces are to be evaluated)
	3.3 - Load array in kN (wheel loads)
	3.4 - Spacing array in m

4. 📤 Outputs
	4.1 - Maximum bending moment(kN-m) and corresponding wheel load position
	4.2 - Maximum shear force(kN) and corresponding wheel load position
	4.3 - Maximum bending moment(kN-m) at point of interest and corresponding wheel load position
	4.4 - Maximum shear force(kN) at point of interest and corresponding wheel load position

5. 🔧 Notes
	5.1 - All dimensional inputs (span length, spacing list) must be rounded to the nearest 0.1 meters.

