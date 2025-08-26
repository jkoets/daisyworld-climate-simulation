# Daisyworld Climate Simulation - User Manual

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [World Generation](#world-generation)
4. [Interface Overview](#interface-overview)
5. [Controls and Tools](#controls-and-tools)
6. [Understanding the Displays](#understanding-the-displays)
7. [Tips and Strategies](#tips-and-strategies)
8. [Troubleshooting](#troubleshooting)

---

## Introduction

Welcome to the Daisyworld Climate Simulation! This educational tool demonstrates how life and climate interact to create a self-regulating system. Based on James Lovelock's Gaia Theory, this simulation shows how simple daisies of different colors can regulate a planet's temperature through their albedo (reflectivity) properties.

### What You'll Learn
- How feedback loops work in climate systems
- The concept of planetary self-regulation
- The relationship between albedo and temperature
- Climate tipping points and system limits

---

## Getting Started

### System Requirements
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Screen resolution of at least 1024x768 recommended

### Launching the Simulation
1. Open the HTML file in your web browser
2. The world generation screen will appear automatically
3. Configure your planet and click "Start Simulation"

---

## World Generation

When you start the simulation, you'll see the World Generation modal with these options:

### Land Coverage (10-90%)
- **Low (10-30%)**: Ocean world with small islands
- **Medium (40-60%)**: Balanced land and water
- **High (70-90%)**: Continental world with inland seas

*Effect*: More land provides more space for daisies to grow and regulate temperature.

### Continent Size (Tiny to Huge)
- **Tiny**: Many small islands
- **Small**: Archipelagos and island chains
- **Medium**: Moderate-sized continents
- **Large**: Major landmasses
- **Huge**: Supercontinents

*Effect*: Larger continents create more uniform climate zones.

### Island Frequency (None to Very High)
- Controls the number of isolated landmasses
- Islands can develop unique daisy populations

*Effect*: Islands create pockets of isolated evolution.

### Initial Daisy Density (0-50%)
- **0%**: Bare planet (daisies must be painted manually)
- **10-20%**: Sparse coverage (recommended for beginners)
- **30-50%**: Dense coverage (immediate climate effects)

*Effect*: Higher density shows immediate temperature regulation.

### Buttons
- **🎲 Regenerate**: Create a new random world with current settings
- **✅ Start Simulation**: Begin with the displayed world

---

## Interface Overview

### Main Display Area

#### World Canvas
- Shows the planet surface (100x50 grid)
- Blue areas: Ocean (daisies cannot grow here)
- Brown areas: Bare land
- Colored areas: Different daisy types

#### Temperature Overlay
- Toggle with "Show Temperature" button
- Blue: Cold areas (< 10°C)
- Green: Optimal areas (15-30°C)
- Yellow/Orange: Warm areas (30-40°C)
- Red: Hot areas (> 40°C)

#### Graph Display
Shows three real-time metrics:
- **Red Line**: Global average temperature
- **Cyan Line**: Total daisy population
- **Yellow Line**: Solar input level

---

## Controls and Tools

### Top Control Bar

#### Show Temperature / Hide Temperature
Toggles between normal view and temperature overlay.

#### Pause / Resume
Stops or continues the simulation without resetting.

#### Reset World
Restarts the current world configuration.

#### New World
Opens the world generation modal.

#### Brush Size (1-5)
Controls the painting tool radius.

### Daisy Painter Panel

#### Daisy Palette
Eight daisy types from white to black:
1. **White** (Albedo: 0.9) - Reflects most heat
2. **Light Gray** (Albedo: 0.75)
3. **Gray** (Albedo: 0.6)
4. **Medium Gray** (Albedo: 0.5)
5. **Dark Gray** (Albedo: 0.4)
6. **Darker Gray** (Albedo: 0.3)
7. **Very Dark** (Albedo: 0.15)
8. **Black** (Albedo: 0.05) - Absorbs most heat

#### Eraser Tool
Removes daisies, leaving bare ground.

### Geosphere Controls

#### Continental Drift (0-100)
- Speed of tectonic movement
- Higher values = more dynamic landmasses

#### Volcanic Activity (0-100)
- Frequency of new land formation
- Can create new islands from ocean

#### Erosion (0-100)
- Rate of land wearing away
- Coastal areas erode into ocean

### Atmosphere Controls

#### Solar Input (0-100)
- **Critical Control**: Amount of heat from the sun
- Simulates increasing solar luminosity
- Start low (50-70) for stable conditions

#### Cloud Albedo (0-100)
- Reflectivity of clouds
- Higher = more cooling effect

#### Greenhouse Effect (0-100)
- Atmospheric heat retention
- Higher = warmer planet

### Biosphere Controls

#### Growth Rate (0-100)
- How quickly daisies reproduce
- Higher = faster spreading

#### Mutation Rate (0-100)
- Chance of daisies changing color
- Higher = more adaptation

#### Thermal Tolerance (0-100)
- Temperature range for daisy survival
- Higher = daisies survive extreme temperatures

---

## Understanding the Displays

### Information Panel

#### Global Temp
- Current average planetary temperature
- Optimal range: 15-30°C
- Daisies die below 5°C or above 40°C

#### Total Daisies
- Number of daisy tiles on the planet
- Maximum possible = land tiles available

#### Planet Albedo
- Average reflectivity (0.0 = black, 1.0 = white)
- Higher albedo = cooler planet

#### Time
- Simulation cycles elapsed
- Use for tracking long-term trends

### Reading the Graph

The graph shows the last 200 time units:

#### Temperature Trends
- **Rising**: Planet warming (need more white daisies)
- **Falling**: Planet cooling (need more black daisies)
- **Oscillating**: System finding balance

#### Population Dynamics
- **Crashes**: Temperature exceeded tolerance
- **Booms**: Optimal conditions reached
- **Stability**: Successful regulation

---

## Tips and Strategies

### For Beginners

1. **Start Simple**
   - Use default settings
   - Begin with 40% land coverage
   - Set initial daisy density to 20%

2. **Observe First**
   - Watch for 100-200 cycles before adjusting
   - Note which daisy colors dominate
   - Check temperature overlay regularly

3. **Make Small Changes**
   - Adjust one control at a time
   - Change by 10-20 points maximum
   - Wait to see effects

### Advanced Experiments

1. **Test Regulation Limits**
   - Slowly increase solar input
   - Find the tipping point
   - Try to recover from collapse

2. **Create Extreme Worlds**
   - All white or all black daisies
   - Very high greenhouse effect
   - Minimal land coverage

3. **Island Evolution**
   - High island frequency
   - Watch isolated populations
   - Compare different islands

### Classroom Challenges

1. **Stability Challenge**
   - Maintain 22.5°C for 500 cycles
   - Use any controls necessary

2. **Recovery Challenge**
   - Start with extreme conditions
   - Restore habitable temperature

3. **Prediction Challenge**
   - Set specific parameters
   - Predict the outcome
   - Test and compare

---

## Troubleshooting

### Common Issues

#### Simulation Won't Start
- Refresh the browser
- Check JavaScript is enabled
- Try a different browser

#### All Daisies Die Immediately
- Lower solar input
- Increase thermal tolerance
- Check temperature isn't extreme

#### Temperature Runaway
- Too much solar input
- Reduce greenhouse effect
- Add more appropriate daisies

#### No Temperature Regulation
- Need mix of daisy colors
- Increase daisy density
- Check land coverage is sufficient

### Performance Tips

- Close other browser tabs
- Reduce brush size for painting
- Pause while adjusting multiple controls

---

## Keyboard Shortcuts

While not implemented in current version, these would be useful additions:
- **Space**: Pause/Resume
- **T**: Toggle temperature
- **R**: Reset world
- **N**: New world
- **1-8**: Select daisy type
- **E**: Eraser tool

---

## Educational Notes

### Key Concepts Demonstrated

1. **Negative Feedback**
   - White daisies cool hot planets
   - Black daisies warm cool planets

2. **Positive Feedback**
   - Initial changes amplify
   - Can lead to runaway effects

3. **Emergence**
   - Simple rules create complex behavior
   - No central control needed

4. **Resilience**
   - System recovers from disturbances
   - Has limits to adaptation

### Real-World Connections

- Ice-albedo feedback in polar regions
- Forest effects on local climate
- Cloud formation and cooling
- Greenhouse gases and warming
- Biodiversity and stability

---

## Credits

Based on the original Daisyworld model by James Lovelock and Andrew Watson (1983), demonstrating the Gaia hypothesis. Inspired by SimEarth (1990) by Maxis.

---

## Version History

- v1.0: Initial release with core features
- World generation system
- Temperature regulation
- Multiple control parameters
- Real-time graphing

---

*End of User Manual*