# Optical Computing Publication Trends

This project analyzes the evolution of **optical / photonic computing research** over time using data from the OpenAlex API.

Construct multiple baselines to understand how optical computing hype and trends have evolved over time:

- Absolute publication counts
- Normalized vs all publications
- Normalized vs CS + Electrical Engineering
- Normalized vs optical publications
- Constrained optical baseline within CS/EE

---

## 📊 Key Results

### Optical Computing Publications (Raw)
![Raw](figures/optPubvsTime.png)

---

### Normalized vs All Publications
![All](figures/optPubvsTimeBaselineAll.png)

---

### Normalized vs Electrical Engineering
![EE](figures/optPubvsTimeEEBaseline.png)

---

### Normalized vs CS + Electrical Engineering
![CS_EE](figures/optPubvsTimeEECSBaseline.png)

---

### Normalized vs Optical Publications
![Optical](figures/optPubvsTimeOptBaseline.png)

---

### Normalized vs Optical within CS/EE (Constrained Baseline)
![Constrained](figures/optPubvsTimeEECSOptBaseline.png)

---

## 🧠 Interpretation

- **1980s–1990s:** Early wave of optical computing (free-space, correlators, analog systems)
- **2000s:** Decline as electronic computing dominates / IT Bubble
- **2015–present:** Resurgence driven by:
  - Silicon photonics
  - DC Demand results in SFP
  - AI Demand drives DC Demand
  - Neuromorphic photonics
  - Optical AI / accelerators


---

## 🛠 Methodology

### Data Source
- OpenAlex API

### Optical Computing Query
Constructed from a union of:
- modern terms (photonic computing, silicon photonics)
- historical terms (optical information processing, correlators)
- AI-related terms (photonic neural networks, reservoir computing)

### Baselines
1. **All publications**
2. **Computer Science + Engineering**
3. **Optical publications (keyword-based)**
4. **Optical within CS/EE (topic-constrained)**

