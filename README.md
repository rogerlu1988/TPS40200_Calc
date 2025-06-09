# TPS40200 Compensation Calculator

An interactive web-based calculator for tuning compensation networks in **TPS40200-based buck converters**. This tool helps engineers design stable, efficient voltage-mode control loops by computing compensation zero, pole, and crossover frequencies.

### 🔗 Live Demo
👉 [Use the calculator](https://rogerlu1988.github.io/TPS40200_Calc/)

---

## ✨ Features

- 📐 **Compensation Network Calculator**  
  Compute Type-II compensation zero and pole frequencies using R5, C7, and C6 values.

- ⚡ **Switching Frequency Input**  
  Suggests crossover, zero, and pole targets based on switching frequency.

- 🔄 **Auto-Tuning Guide**  
  Based on best practices from the TPS40200 datasheet, including LC resonance, ESR effects, and amplifier bandwidth limits.

- 🎯 **Additional Calculators**
  - LC Filter Resonance Frequency
  - ESR Zero Frequency
  - Switching Frequency (from Rt and Ct)
  - Soft-Start Time Estimator (from CSS)

- 📊 **Bode Plot** *(Coming soon)*  
  Visual gain/phase plot support for control loop design.

---

## 📷 Schematic Reference

![TPS40200 Schematic](tps40200_schematic.png)

---

## 📁 Project Structure
