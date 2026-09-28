# Makarand A. Kulkarni, Ph.D. — Portfolio Website
> **Chief Product Officer | Climate & AgriTech | AI/ML | Parametric Insurance**

Personal portfolio website and interactive decision-support application showcase for **Makarand A. Kulkarni, Ph.D.** (Chief Product Officer, Atmospheric Scientist, and Climate Risk Specialist).

---

## 🌟 Four Core Domain Pillars
1. 🌤️ **Climate & Environment**: Climate risk, forecasting, environmental metrics, spatial weather analytics.
2. 🍃 **ESG & Carbon**: Dairy ESG, carbon accounting, Scope 1–3 footprinting, IPCC AR6 stress testing.
3. 📈 **Risk Analytics**: PMFBY agricultural underwriting, parametric index design, reinsurance treaty pricing.
4. 📖 **Research & Teaching**: International publications (15+ peer-reviewed papers), academic experience, university lectures.

---

## 🚀 Bundled Interactive Applications (`projects/`)
All four applications run purely client-side with zero backend dependencies using standard HTML5, CSS3, JavaScript, Plotly.js, and KaTeX:

1. **Enterprise Dairy Decarbonization & Climate Risk Dashboard** (`projects/dairy-esg/index.html`)
   - Scope 1, 2, and farm-level Scope 3 baseline GHG inventory accounting (IPCC AR6 GWP).
   - THI heat stress modeling on crossbred, buffalo, and indigenous dairy breeds.
   - Simulation of 2030 decarbonization levers with Marginal Abatement Cost (MAC) curves.

2. **PMFBY Crop Insurance Portfolio & Tail Risk Analyzer** (`projects/crop-risk-analyzer/index.html`)
   - Vectorized Box-Muller Monte Carlo yield shock simulation (1,000–5,000 runs) across Insurance Units (IUs).
   - Hierarchical spatial risk pooling (IU &rarr; District &rarr; Cluster) capturing geographical risk offsets.
   - Tail risk quantification: Expected Burn Rates, CV, and P₉₀ / P₉₅ Value at Risk (VaR).

3. **PMFBY Underwriting Analytics Platform & Cluster Builder** (`projects/pmfby-analyzer/index.html`)
   - Scheme records across 77 notified districts in Maharashtra &amp; Chhattisgarh (2018–2025).
   - Granular gross premium, subsidy sharing (Farmer/State/Center), and statutory burn rates.
   - Custom District Cluster Builder with real-time portfolio recalculation.

4. **Non-Proportional XL Reinsurance Pricing Simulator** (`projects/xl-reinsurance/index.html`)
   - Non-proportional treaty pricing for excess of loss layers ($C \text{ xs } D$).
   - Stochastic draws (Normal, Lognormal, Gamma) and continuous layer band expansion.
   - Burning cost pricing with standard deviation risk loading ($\bar{Y} + \lambda \cdot \sigma$), ROL %, and Exceedance Probability (EP) curves.

---

## 💻 Local Testing & Deployment
To view locally:
```bash
# Python simple server
python -m http.server 8003
```
Open `http://localhost:8003/index.html` in your web browser.

To deploy to GitHub Pages:
1. Push this repository to GitHub under `portfolio-website` (or `<username>.github.io`).
2. Go to **Settings > Pages > Branch: main / root**.
3. Live portfolio URL: `https://makkulkarni.github.io/portfolio-website/`
