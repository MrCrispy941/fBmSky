# fBmSky

**fBmSky** generates astronomical cirrus maps using fractional Brownian motion (fBm).  
Ideal for testing source extraction, confusion limits, or training ML models, it allows control over structure, beam smoothing, and noise to simulate far-infrared sky backgrounds.

---

## 🌠 Features

- 2D fractional Brownian motion generator
- Customizable Hurst exponent for spatial structure
- Gaussian smoothing to simulate telescope beams
- Log-normal transformation for realistic emission profiles
- Optional observational noise addition
- Clean, modular Python codebase

---

## 🧪 Requirements

- Python 3.7+
- numpy
- matplotlib
- scipy

Install dependencies with:

```bash
pip install numpy matplotlib scipy
