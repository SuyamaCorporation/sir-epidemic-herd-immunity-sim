# SIR Epidemic Herd Immunity Spread Simulation

A grid-based SIR (Susceptible, Infected, Recovered) epidemic model where disease spreads between neighboring cells. Adjust R₀, vaccination rate, and recovery time to observe how herd immunity emerges. A live population curve chart tracks S/I/R proportions over time with the herd immunity threshold marked as a dashed line.

## Features

- 80×80 grid simulation with four states: Susceptible, Infected, Recovered, Vaccinated
- Adjustable R₀ (1.0–5.0), vaccination rate (0–80%), and recovery time (3–30 steps)
- Live herd immunity threshold calculation and display (1 − 1/R₀)
- Real-time S/I/R population curve chart with threshold line
- Play/pause/step controls and instant reset
