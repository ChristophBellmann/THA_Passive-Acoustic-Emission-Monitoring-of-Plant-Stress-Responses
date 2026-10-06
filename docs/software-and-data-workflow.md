# Software & Data Workflow

The practical measurement software lives under `src/characterization/`.

## Measurement control

The repository provides command-line control for starting, checking and stopping continuous acquisition, together with a Jupyter-based control panel for interactive work.

The acquisition workflow includes reconnect handling for instrument communication failures and heartbeat monitoring for stalled measurements.

## Data analysis

Experiment notebooks and scripts cover continuous plant-acoustic characterization, candidate tracking, phase/time-delay analysis and watering experiments.

## Data integrity

Measurement metadata should remain tied to the corresponding acquisition and processing configuration. Automated analysis results are useful only when sensor roles, sampling parameters and experiment timing remain traceable.

The GitBook provides the conceptual overview; the repository remains the source of truth for executable analysis code and detailed experiment artifacts.
