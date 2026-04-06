# astronomy_fun

A collection of astronomy notebooks and experiments.

## Artemis II Trajectory Tracker

Fetches real-time ephemeris data from NASA's JPL Horizons system to track and visualize the Artemis II mission trajectory.

- Queries the Orion spacecraft (`-1024`) and Moon positions relative to Earth
- Computes live telemetry: mission elapsed time, distance to Earth/Moon, and speed
- Calculates the closest lunar approach
- Renders a 2D mission map (matplotlib) and an interactive 3D visualization (Plotly)

### Setup

```bash
pip install numpy matplotlib astropy astroquery scipy plotly
```

### Usage

Open `artemis_ii_tracking.ipynb` and run all cells. The notebook pulls live data, so results update with each run.