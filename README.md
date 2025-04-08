# fBmSky

**fBmSky** generates astronomical cirrus maps using fractional Brownian motion (fBm).  
Ideal for testing source extraction, confusion limits, or training ML models, it allows control over structure, beam smoothing, and noise to simulate far-infrared sky backgrounds.

Note from author - The code itself generates a randomm gaussian field which at large scales appears to mimic cirrusy structure quite nicely. However, the pixel scale will need to be adjusted after the fact to represent a map that is physically accurate. The current model outputs can be scaled as necessary, though I don't believe there is a functionality that can be added for spectral/temperature adjustments to be made or considered by the fBm software. There is currently no way to for example; extract a power spectrum from a reference image and then apply to the random field.

---

- 2D fractional Brownian motion generator
- Customizable Hurst exponent for spatial structure
- Gaussian smoothing to simulate telescope beams
- Log-normal transformation for realistic emission profiles
- Optional observational noise addition
- Clean (relatively), modular Python codebase

---

## Requirements

- Python 3.7+
- numpy
- matplotlib
- scipy

Install dependencies with:

```bash
pip install numpy matplotlib scipy
