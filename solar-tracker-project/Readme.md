# Dual-Axis Solar Tracking System

## Project Overview
This project involves the design, construction, and implementation of a **Dual-Axis Solar Tracker** to optimize solar energy collection. The tracker dynamically adjusts the solar panel's position to follow the sun's path, maximizing energy capture and improving efficiency over static solar panels.

The system uses **Light Dependent Resistors (LDRs)** to detect sunlight intensity and control **stepper motors** to adjust the solar panel's position. This dual-axis tracker ensures that the panel remains perpendicular to the sun, providing greater energy generation.

## Objectives
- **Maximize Solar Energy Efficiency**: Track the sun across both horizontal (azimuth) and vertical (elevation) axes to improve solar panel energy absorption.
- **Energy Storage**: Utilize rechargeable **lithium-ion batteries** to store collected solar power for use later.
- **Cost-Effective & Simple**: Design a simple, affordable, and efficient solar tracking system suitable for various applications.

## How It Works
1. **Light Detection**: Four LDRs are placed on the solar panel to measure the intensity of sunlight from different directions.
2. **Panel Adjustment**: When the sun's light is stronger on one side, the system uses this information to rotate the solar panel along both the X and Y axes to keep it aligned with the sun.
3. **Energy Storage**: The collected solar energy is stored in lithium-ion batteries for later use.
4. **Load Driving**: The stored energy is then used to power devices like LEDs, DC fans, or other small electronics.

## Features
- **Dual-Axis Tracking**: Adjusts both horizontally (azimuth) and vertically (elevation) for maximum sunlight exposure.
- **Real-time Tracking**: The system adjusts the solar panel position continuously based on the changing sun position.
- **Energy Storage**: Energy is stored during the day and can be used later at night.
- **High Efficiency**: Increases solar panel efficiency by 30%–60% compared to stationary panels.

## Performance & Results
- The tracking system has been tested against static panels and single-axis trackers, showing improved current generation throughout the day.
- A comparison graph of current and voltage values at different times of the day demonstrates the superior performance of the tracking panel.

## Future Scope
- **Further Expansion**: Integration of Z-axis and rotation around the X and Y axes for more precise sun tracking.
- **Floating Solar Farms**: Utilize the cooling effect of water to improve the performance of solar panels.
- **Building-Integrated Solar Panels**: Incorporate solar technology into building structures.
- **Solar Fabrics**: Develop wearable fabrics that generate solar power.
- **Solar Noise Barriers**: Implement solar panels along roads and highways to reduce noise pollution and generate energy.

## Installation Instructions
1. **Assemble Components**: Connect the LDRs, stepper motors, microcontroller, and battery management circuit according to the provided circuit diagram.
2. **Install Software**: Upload the controller code to the microcontroller using an Arduino IDE or compatible software.
3. **Positioning**: Install the solar panel in an area with unobstructed access to sunlight.
4. **Power Up**: Ensure the battery is charged and the system is ready to track the sun.

## Conclusion
The Dual-Axis Solar Tracking System was successfully designed and tested, demonstrating significant improvements in energy efficiency compared to static and single-axis solar tracking systems. This technology has the potential to reduce dependence on fossil fuels, decrease environmental pollution, and provide a sustainable energy solution for the future.