# Modern Strain Gage Technology — Companion Notebooks

Runnable Jupyter notebooks for the book **_Modern Strain Gage Technology: From Analog to AI_** by Michael J. Bower. Each notebook accompanies one chapter (64 of the book's 65 chapters have one): it reproduces the chapter's figures and worked examples, and is written to be a starting point you can extend for your own strain-measurement and machine-learning work.

> **One-click, no install:** click a **Open In Colab** badge below to run any notebook in your browser (free). Or run locally (see *Local setup*).

## How to use
- **In Colab (recommended):** click the badge for a chapter and run the cells top to bottom; figures render inline. Colab already includes every library the notebooks use. The first code cell carries a commented-out `pip install` line for other environments.
- **Locally:** clone the repo, create an environment, `pip install -r requirements.txt` (it includes JupyterLab), then `jupyter lab` and open a notebook.
- Every notebook is self-contained, seeds its random number generators for reproducibility, and ends with a **"Where to take this next"** section of extension exercises.

## Notebooks by chapter

### Volume I (Chapters 1–34)

**Part I — Listening to Materials: Why Measurement Matters**

| Ch | Notebook | Run |
|---:|----------|-----|
| 1 | [Engineering Accountability](notebooks/ch01_engineering_accountability.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch01_engineering_accountability.ipynb) |
| 2 | [Modern Liability](notebooks/ch02_modern_liability.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch02_modern_liability.ipynb) |

**Part II — From Intuition to Instrument: A History of Strain Measurement**

| Ch | Notebook | Run |
|---:|----------|-----|
| 3 | [Elasticity Before Electronics](notebooks/ch03_elasticity_before_electronics.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch03_elasticity_before_electronics.ipynb) |
| 4 | [Electricity Finds Deformation](notebooks/ch04_electricity_finds_deformation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch04_electricity_finds_deformation.ipynb) |
| 5 | [Birth of the Resistance Strain Gage](notebooks/ch05_birth_of_the_resistance_strain_gage.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch05_birth_of_the_resistance_strain_gage.ipynb) |
| 6 | [A Global Instrument](notebooks/ch06_a_global_instrument.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch06_a_global_instrument.ipynb) |
| 7 | [The Culture of Measurement](notebooks/ch07_culture_of_measurement.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch07_culture_of_measurement.ipynb) |
| 8 | [War, Aviation, and the Acceleration of Truth](notebooks/ch08_war_aviation_acceleration.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch08_war_aviation_acceleration.ipynb) |
| 9 | [Strain Gages and Murphy's Law](notebooks/ch09_murphys_law.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch09_murphys_law.ipynb) |
| 10 | [From Analog Ritual to Digital Reality](notebooks/ch10_analog_to_digital.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch10_analog_to_digital.ipynb) |
| 11 | [Intelligent Measurement and the AI Transition](notebooks/ch11_intelligent_measurement.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch11_intelligent_measurement.ipynb) |

**Part III — The Language of Deformation: Stress and Strain**

| Ch | Notebook | Run |
|---:|----------|-----|
| 12 | [Motion](notebooks/ch12_motion.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch12_motion.ipynb) |
| 13 | [Deformation and Strain](notebooks/ch13_deformation_and_strain.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch13_deformation_and_strain.ipynb) |
| 14 | [Stress](notebooks/ch14_stress.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch14_stress.ipynb) |
| 15 | [Stress–Strain Relationships](notebooks/ch15_stress_strain_relationships.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch15_stress_strain_relationships.ipynb) |
| 16 | [The Stress-Strain Curve](notebooks/ch16_stress_strain_curve.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch16_stress_strain_curve.ipynb) |
| 17 | [Mohr's Circle](notebooks/ch17_mohrs_circle.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch17_mohrs_circle.ipynb) |
| 18 | [Shear Stress and Strain](notebooks/ch18_shear_stress_and_strain.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch18_shear_stress_and_strain.ipynb) |
| 19 | [Thermal Effects on Strain](notebooks/ch19_thermal_effects.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch19_thermal_effects.ipynb) |
| 20 | [Fatigue and Cyclic Loading](notebooks/ch20_fatigue.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch20_fatigue.ipynb) |

**Part IV — The Translator: The Strain Gage**

| Ch | Notebook | Run |
|---:|----------|-----|
| 21 | [The Electrical Resistance Strain Gage: Why It Won](notebooks/ch21_electrical_resistance_strain_gage.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch21_electrical_resistance_strain_gage.ipynb) |
| 22 | [Resistance of a Conductor](notebooks/ch22_resistance_of_a_conductor.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch22_resistance_of_a_conductor.ipynb) |
| 23 | [The Bonded Foil Strain Gage](notebooks/ch23_bonded_foil_strain_gage.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch23_bonded_foil_strain_gage.ipynb) |
| 24 | [Strain Gage Characteristics](notebooks/ch24_strain_gage_characteristics.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch24_strain_gage_characteristics.ipynb) |

**Part V — Reading the Signal: Measuring Strain**

| Ch | Notebook | Run |
|---:|----------|-----|
| 25 | [Before Digital: Galvanometers, Bridges, and Magnetic Tape](notebooks/ch25_before_digital.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch25_before_digital.ipynb) |
| 26 | [The Signal Chain: From Resistance Change to Bridge Output](notebooks/ch26_wheatstone_bridge_signal_chain.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch26_wheatstone_bridge_signal_chain.ipynb) |
| 27 | [Bridge Configurations and Selection](notebooks/ch27_offset_nonlinearity.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch27_offset_nonlinearity.ipynb) |
| 28 | [Signal Conditioning: From Bridge Output to Readable Data](notebooks/ch28_signal_conditioning.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch28_signal_conditioning.ipynb) |
| 29 | [Shunt Calibration: Verifying the Measurement System](notebooks/ch29_shunt_calibration.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch29_shunt_calibration.ipynb) |
| 30 | [Noise, Grounding, and EMI: Protecting the Signal](notebooks/ch30_noise_grounding_emi.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch30_noise_grounding_emi.ipynb) |
| 31 | [Modern Data Acquisition: From Analog Signal to Digital Record](notebooks/ch31_modern_data_acquisition.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch31_modern_data_acquisition.ipynb) |
| 32 | [Dynamic Measurement: When Strain Changes Fast](notebooks/ch32_dynamic_measurement.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch32_dynamic_measurement.ipynb) |
| 33 | [Shock, Transient, and Fatigue Measurement](notebooks/ch33_shock_transient_fatigue.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch33_shock_transient_fatigue.ipynb) |
| 34 | [Telemetry and Wireless Strain Measurement: Cutting the Wire](notebooks/ch34_telemetry.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch34_telemetry.ipynb) |

### Volume II (Chapters 35–65)

**Part VI — The Art of the Test: Experimental Methods**

| Ch | Notebook | Run |
|---:|----------|-----|
| 35 | [Planning a Strain Measurement Program](notebooks/ch35_planning.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch35_planning.ipynb) |
| 36 | [Gage Placement and Structural Testing](notebooks/ch36_rosette_analysis.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch36_rosette_analysis.ipynb) |
| 37 | [Fatigue Measurement Programs: The Arithmetic of Damage](notebooks/ch37_fatigue_measurement.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch37_fatigue_measurement.ipynb) |
| 38 | [Residual Stress Measurement: The Stress That Stays Behind](notebooks/ch38_residual_stress.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch38_residual_stress.ipynb) |

**Part VII — Instruments of Force: Strain Gage Based Transducers**

| Ch | Notebook | Run |
|---:|----------|-----|
| 39 | [The Transducer Idea: Engineering Strain into Measurement](notebooks/ch39_transducer_idea.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch39_transducer_idea.ipynb) |
| 40 | [The Spring Element: Designing the Elastic Foundation](notebooks/ch40_spring_element_design.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch40_spring_element_design.ipynb) |
| 41 | [Spring Element Materials: The Modulus Problem and How to Solve It](notebooks/ch41_spring_element_materials.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch41_spring_element_materials.ipynb) |
| 42 | [Gage and Adhesive Selection: The Precision Specification](notebooks/ch42_gage_adhesive_selection.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch42_gage_adhesive_selection.ipynb) |
| 43 | [Completing the Measurement: Compensation, Balance, and Protection](notebooks/ch43_completing_the_measurement.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch43_completing_the_measurement.ipynb) |
| 44 | [The Instruments: Load Cells, Pressure Transducers, Torque Meters, and Multi-Axis Load Cells](notebooks/ch44_instruments_load_cells.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch44_instruments_load_cells.ipynb) |

**Part VIII — How Well Do We Know? Measurement Uncertainty**

| Ch | Notebook | Run |
|---:|----------|-----|
| 45 | [Uncertainty Fundamentals](notebooks/ch45_uncertainty_fundamentals.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch45_uncertainty_fundamentals.ipynb) |
| 46 | [Sources of Uncertainty in Strain Measurement](notebooks/ch46_sources_of_uncertainty.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch46_sources_of_uncertainty.ipynb) |
| 47 | Installation, Environmental, and Cumulative Uncertainty | *no notebook* |
| 48 | [Uncertainty Propagation](notebooks/ch48_uncertainty_propagation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch48_uncertainty_propagation.ipynb) |
| 49 | [Calibration and Traceability](notebooks/ch49_calibration_traceability.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch49_calibration_traceability.ipynb) |

**Part IX — From Data to Insight: Machine Learning**

| Ch | Notebook | Run |
|---:|----------|-----|
| 50 | [When Data Became Too Large to Listen To](notebooks/ch50_when_data_became_too_large.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch50_when_data_became_too_large.ipynb) |
| 51 | [From Physics to Features: Preparing Strain Data for Learning](notebooks/ch51_physics_to_features.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch51_physics_to_features.ipynb) |
| 52 | [Linear Models: The First Step Toward Intelligence](notebooks/ch52_linear_models.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch52_linear_models.ipynb) |
| 53 | [Nonlinear Models: Learning What Physics Doesn't Capture Easily](notebooks/ch53_nonlinear_models.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch53_nonlinear_models.ipynb) |
| 54 | [Ensemble Methods: Random Forests and Gradient Boosting](notebooks/ch54_ensemble_methods.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch54_ensemble_methods.ipynb) |
| 55 | [Neural Networks: From Architecture to Learning](notebooks/ch55_neural_networks.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch55_neural_networks.ipynb) |
| 56 | [Anomaly Detection and Unsupervised Learning](notebooks/ch56_anomaly_detection.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch56_anomaly_detection.ipynb) |
| 57 | [Deep Learning for Sequential Strain Data](notebooks/ch57_deep_learning_sequential.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch57_deep_learning_sequential.ipynb) |
| 58 | [Sensor Fusion: From Local Strain to Global Understanding](notebooks/ch58_sensor_fusion.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch58_sensor_fusion.ipynb) |
| 59 | [Case Studies in Machine Learning with Strain Gages](notebooks/ch59_ml_case_studies.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch59_ml_case_studies.ipynb) |
| 60 | [Uncertainty, Validation, and Trust in AI-Based Measurement](notebooks/ch60_uncertainty_in_ai.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch60_uncertainty_in_ai.ipynb) |
| 61 | [Real-Time Systems: Embedded AI and Edge Measurement](notebooks/ch61_real_time_systems.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch61_real_time_systems.ipynb) |
| 62 | [Digital Twins and Adaptive Structures](notebooks/ch62_digital_twins.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch62_digital_twins.ipynb) |
| 63 | [The Machine That Feels: Strain Sensing in Robots and Humanoids](notebooks/ch63_robotics.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch63_robotics.ipynb) |
| 64 | [What AI Still Cannot Do](notebooks/ch64_what_ai_cannot_do.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch64_what_ai_cannot_do.ipynb) |
| 65 | [The Future of Intelligent Measurement](notebooks/ch65_future.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mike-bower/modern-strain-gage-technology-notebooks/blob/main/notebooks/ch65_future.ipynb) |

## Local setup
```bash
git clone https://github.com/mike-bower/modern-strain-gage-technology-notebooks.git
cd modern-strain-gage-technology-notebooks
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## License
The notebook **code** is released under the [MIT License](LICENSE). The **book** itself — its text and figures — is a separate copyrighted work, (c) 2026 Michael J. Bower, all rights reserved.

---
*Companion notebooks for* Modern Strain Gage Technology: From Analog to AI *by Michael J. Bower, published in two volumes: Volume I (Chapters 1–34) and Volume II (Chapters 35–65). Chapter 47 has no notebook; the other 64 chapters each have one.*
