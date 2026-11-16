# Creature Simulation

A simple Python Object-Oriented Programming (OOP) simulation demonstrating inheritance, method overriding, and state management through a base `Creature` class and specialized subclasses.

## Features

- **Base `Creature` Class**: Manages core attributes (`name`, `hp`, `attack_power`), basic combat mechanics, health checks (`is_alive()`), and string formatting.
- **`FlyingCreature` Subclass**: Adds an `altitude` attribute, a `fly_to()` movement method, and an overridden aerial `attack()` method.
- **`SwimmingCreature` Subclass**: Adds a `depth` attribute, a `dive_to()` movement method, and an overridden underwater `attack()` method.
- **`FireCreature` Subclass**: Adds a `fire_level` attribute, an `emit_fire()` method, and an overridden fire `attack()` method.
- **Built-in Test Suite**: Includes unit tests in the `__main__` block verifying initialization, damage calculation, overkill prevention (HP floor at `0`), defeat states, and subclass behaviors.

## Requirements

- Python 3.6 or higher (uses f-strings; no external libraries required)

## Usage

Run the script directly from your terminal to execute the simulation and view the test results:

```bash
python creature_simulation.py