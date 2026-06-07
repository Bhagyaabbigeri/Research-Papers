# 📄 Research Papers & Presentations
### Bhagyashree Reddy | Computer Science Engineering | VTU, CPGS Kalaburagi

---

## 🚀 QLEAP: Quantum-Entangled Lattice with Entanglement-Aware AI Protocol for Ultra-Secure Deep-Space Communication

**Author:** Bhagyashree Reddy  
**Department:** Computer Science Engineering  
**Institution:** Visvesvaraya Technological University (VTU), Regional Centre Kalaburagi, India  
**Event:** VTU National Quantum Students' Summit & Conference 2026 (NQSS), VTU Belagavi  
**Track:** Track 3 — Space Technology  
**Award:** 🏆 Best Innovation Idea in Space Technology  

---

## 📌 Problem Statement
Classical deep-space links suffer latency (24 min to Mars), interception risk, and decoherence. Existing QKD systems (e.g., Micius) are limited to single LEO–ground hops. QLEAP proposes a multi-layer orbital entanglement relay using AI-driven Bell-state correction and Lagrange-point quantum relay nodes (LQRNs) — enabling provably secure, near-zero-latency planetary communication.

---

## 🎯 Objectives
- Establish multi-hop entanglement chains: LEO → L1/L2 → deep space
- AI-driven Bell-state classifier for real-time decoherence correction
- Quantum-secure key rate at >10 Mbps via BB84 + E91 hybrid
- Validate photon-loss models for 500,000 km+ baselines

---

## 💡 Key Innovation
| Feature | Description |
|--------|-------------|
| **LQRNs** | First system to place quantum memory nodes at Lagrange points — zero station-keeping, gravitationally stable relay |
| **ABSE** | First ML-based autonomous Bell-state timing engine for inter-node fidelity maximization |
| **QPath** | Fidelity as routing cost metric — paradigm shift from distance/latency-based space networking |
| **Dual-DOF** | Polarization + OAM encoding → 4× throughput on single channel |

---

## 🏗️ System Architecture
Ground Station → LEO QKD Satellite → LQRN @ L1/L2 → Deep Space Probe
↓                  ↓                   ↓               ↓
SPDC Source      Entangled Photon     Rb Atomic        Quantum RX
Quantum TX/RX    Pair Generator       Ensemble         + Clock Sync
ISRO/NASA DSN    600–800 km orbit     Memory Node      Mars/L2/Beyond

---

## 📊 Experimental Results
| Metric | Result |
|--------|--------|
| Fidelity after AI correction | **>0.97** |
| Secure key rate LEO–L1 | **~10 Mbps** |
| Clock sync jitter | **<1 ps** |
| ABSE fidelity improvement | **~34% vs passive relay** |
| QPath link recovery | **<2 ms on node failure** |
| Throughput gain | **4× over single-DOF Micius-class** |

---

## 🔬 Methodology
1. Ground station generates Bell-state photon pairs via SPDC; uplinks one photon to LEO QKD satellite
2. LEO satellite relays photon to LQRN at L1/L2; stored in Rb atomic ensemble (coherence >1s)
3. ABSE runs Bell-state tomography; if fidelity <0.95, triggers entanglement purification protocol
4. LQRN performs entanglement swapping → direct ground-to-probe entanglement; QPath reroutes on failure; BB84+E91 delivers final quantum key

---

## 🛠️ Tools & Technologies
- **Simulation:** Qiskit, QuTiP, Python 3.11
- **Trials:** 10⁶ Monte Carlo photon-loss simulations
- **Measurement:** BSM via HOM interferometry + SPADs at 1550 nm
- **Data acquisition:** Photon coincidence at 10 MHz; ABSE latency <50 µs/cycle

---

## 🌍 Applications
- **ISRO Gaganyaan / DRDO:** Quantum-secure crew and strategic satellite communications
- **Planetary exploration:** Secure telemetry + sub-ps clock sync for Mars rovers and deep-space probes

---

## 🔮 Future Work
- **Near-term:** Sub-orbital balloon testbed (30 km) to validate ABSE latency
- **Long-term:** Upgrade LQRN storage to Eu³⁺:Y₂SiO₅ crystals (>6 hr coherence); interface QPath with ISRO QCS constellation for global orbital quantum mesh

---

## 📎 View Poster
[📄 View Full Poster (HTML)](https://github.com/Bhagyaabbigeri/Research-Papers/blob/32bae83f1a20982ebae62e1d66a57ff70b82893f/QLEAP_poster_presentation.pdf)

---

## 📬 Contact
- **Email:** bhagyashreeabbigeri7@gmail.com
- **LinkedIn:** [linkedin.com/in/bhagyashree-reddy](https://linkedin.com/in/bhagyashree-reddy)
- **GitHub:** [github.com/Bhagyaabbigeri](https://github.com/Bhagyaabbigeri)

---
*© 2026 Bhagyashree Reddy — VTU, CPGS Kalaburagi*
