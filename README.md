# Gravity Garden

**Place stars. Watch gravity do the rest.**

[Live Demo](https://tortured-metaphor.github.io/Gravity-Garden)

## Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Place a star | Click | Tap |
| Place a giant star (10x mass) | Double-click | Double-tap |
| Place a zero-velocity star | Right-click | Long-press |
| Zoom in/out | Scroll wheel | Pinch |
| Apply directional force | — | Tilt device |

### HUD

- **Trails** — adjust trail fade length
- **Speed** — simulation timestep multiplier
- **Clear** — remove all stars
- **Star count** — displayed at the end of the bar

## Physics

- Newtonian gravity: F = Gm1m2 / r²
- Velocity Verlet integration
- Gravitational softening to prevent singularities
- Momentum-conserving merges on collision
- Velocity cap to keep the system bounded

## License

MIT
