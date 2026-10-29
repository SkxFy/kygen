# Kygen

Kygen is a procedural universe simulator written in C.

It generates astronomical systems from seeds and simulates their behavior using simplified physical models.

## Philosophy

- **Determinism:** The same seed and configuration should produce reproducible results.
- **Physical consistency:** Randomness establishes initial conditions, while physical models determine derived properties and behavior.
- **Separation of concerns:** Generation, simulation, and rendering remain independent.
- **Pragmatism:** Use approximations where detailed physical simulation is impractical.
- **Simplicity:** Favor straightforward implementations over unnecessary abstractions.

## Status

Kygen is in early development.

The first milestone is a deterministic star system with physically derived properties, simplified orbital motion, and interactive visualization.

## Technology

- C17
- CMake
- raylib
