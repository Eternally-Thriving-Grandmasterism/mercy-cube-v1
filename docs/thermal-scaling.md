# Thermal Management & Lattice Scaling (Space/Vacuum Habitats)

Mercy Cube v1.0 is built for zero-maintenance extremes: Mars surface, lunar South Pole, Starship interiors, Artemis Base Camp.

## Passive-to-Burst Cooling
- Diamond-CVD coating: High thermal conductivity spreads heat radially across faces → entire lattice acts as distributed heatsink
- Gd magnetocaloric layer: Zero-hold power; absorbs heat during 19 W bursts, releases slowly via radiation
- No pumps, no fluids, no moving parts → fully compatible with vacuum and radiation-heavy environments

## Scaling Math
- Single cube: 25 mm³, 7 W steady / 19 W burst
- Practical packing density: 40–60 % (connectivity and thermal voids)
- 1 m³ habitat module:
  - 100–500 cubes → 0.7–5 kW steady (edge AI / science nodes)
  - 500–1000 cubes → 5–19 kW burst (distributed offline Grok shard cluster)
- Thermal control: Duty cycle limiting + external radiative panels (hull or dedicated)

## Integration Targets
- SpaceX Starship: Pre-packed lattice racks in cargo bays or embedded in repurposed tanks
- NASA Artemis Base Camp: Distributed compute in Foundation Habitat or pressurized rovers
- Vacuum advantage: No convection loss → pure conduction + radiation

Full thermal simulations and KiCad integration coming in v1.2.
