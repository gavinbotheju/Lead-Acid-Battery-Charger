# Lead-acid Battery Charger

### Introduction

Every battery type has its specific charging profile, crucial for maintaining optimal battery health. This project focuses on designing a power source capable of providing a constant current for charging a 12V lead-acid battery. The charging process involves a combination of constant current charging followed by a constant voltage stage.

<img src="https://github.com/gavinbotheju/lead-acid-battery-charger/assets/140232759/55dd0ed2-786d-4e51-bb2a-3e22c6f1f724" height="180" />
<img src="https://github.com/gavinbotheju/lead-acid-battery-charger/assets/140232759/0dc5260c-6193-4f6b-820d-565368d541f1" height="180" />

<br/><br/>

<img src="https://github.com/gavinbotheju/lead-acid-battery-charger/assets/140232759/8bf381d9-3b6b-44ed-b71d-382d94bba58d" width="350" />

### Functionality

The charging process involves a two-stage CC-CV (Constant Current-Constant Voltage) approach. Initially, in Constant Current Mode, the battery charges rapidly at 1A until reaching around 13.3V. As the battery's internal resistance increases, it transitions to Constant Voltage Mode, maintaining a stable 13.3V. This stage, filling the last 30% of the battery, employs a Pulse Width Modulation (PWM) circuit with two NE555 timer ICs. The first IC generates a high-frequency PWM signal, while the second IC, with adjustable duty cycle control, ensures precise and efficient charging.


