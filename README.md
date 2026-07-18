# NTC Thermistor Temperature Sensor Measurement & Modeling

**Author:** Ravan Jafarov (Student ID: 12255135)  
**Course:** Capstone Design 2 – Measurement Engineering Laboratory | **Instructor:** Prof. Dae Yu Kim  
**Institution:** BEU-INHA Dual Degree Diploma Program, Inha University  

## Objective
To characterize an NTC (Negative Temperature Coefficient) thermistor, implement a voltage divider circuit for temperature measurement, and extract/compare thermistor model parameters using the Steinhart–Hart and Beta models.

## Contents
- `Report Ravan Jafarov.pdf`: Full laboratory report, including Arduino code for ADC reading, Steinhart-Hart and Beta model calculations, and experimental results.

## Key Findings
- **NTC Behavior:** Confirmed that resistance decreases steadily as temperature increases (e.g., finger heating test dropped resistance from 9500 Ω to 7700 Ω).
- **Steinhart-Hart Model:** Utilizes three constants (A, B, C) derived from calibration points (0°C, 25°C, 50°C) to accurately fit the R-T curve over a wide temperature range.
- **Beta Model:** A simpler two-point exponential approximation that performed slightly better in the specific narrow high-temperature range tested (body temperature).
- **Body Temperature Measurement:** Both models underestimated the true thermometer value (36.7°C), yielding 34.43°C (Steinhart-Hart, 2.27°C error) and 34.77°C (Beta, 1.93°C error). This highlights the importance of proper thermal coupling and target-range calibration.
- **Conclusion:** The experiment successfully demonstrated thermistor-based temperature sensing principles, mathematical modeling, and the practical limitations of sensor calibration in real-world environments.
