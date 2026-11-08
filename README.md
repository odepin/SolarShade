# SolarShade

> Browser-based geometric sun and shadow visualizer.

**Current state:** Documentation starter / proposed product. The presence of this README does **not** mean the software has been implemented, deployed, used. Update this status to reflect real work.

## What it is

SolarShade is a proposed specialist software tool for Small solar installers, architectural students, and retrofitting professionals. A quick shading study can require heavier CAD tools than a small installer needs. The intended differentiation is: A narrow, explainable 3D shading viewer with offline fixture geometry and time-of-day comparisons.

## Intended users and use cases

- Illustrate a chimney shadow on a fictional roof
- Compare exposure at two solar times
- Confirm sun-angle calculations against known references

## Planned features

- Create simple roofs and obstruction blocks from editable geometry
- Calculate solar azimuth and elevation for declared test coordinates and dates
- Visualize time-step shadows and panel exposure estimates
- Compare orientation, tilt, and obstruction alternatives
- Export reproducible project JSON and assumption-tagged charts

## Proposed technology

TypeScript, Three.js, Vite, Vitest

These technologies are *planned*, not a claim that dependencies have already been installed or code has been written. Revise this section when actual implementation decisions are made.

## Proposed architecture

- Solar position and coordinate calculations
- Basic 3D geometry and ray intersection
- Local project model and scenario controls
- CSV/PNG export modules

See [TECHNICAL_PLAN.md](TECHNICAL_PLAN.md) for technical boundaries and acceptance tests.

## Running locally

**Not yet runnable.** This package contains documentation templates, not software. When a functioning implementation is available, replace this paragraph with tested prerequisites, install instructions, a verified executable command, and a reproducible example using `Generic demonstration coordinates and fictional roof geometry.`

## Data boundaries and exclusions

Professional structural assessment, full yield bankability forecasts, or recording private residential addresses. All public examples should use Generic demonstration coordinates and fictional roof geometry.

## Known limitations / validation risks

Visibility approximations and solar conventions require numerical benchmarks and boundary tests.

## Development roadmap

Work is broken into estimated, not-yet-completed milestones in [ROADMAP.md](ROADMAP.md). They are *planning estimates*, not an assertion that development has begun or that work will definitely be performed.

## Business direction

Potential commercial extensions: Advanced analysis/report exports and design-software adapters. 

## Contributing and licensing

License: [Mozilla Public License 2.0](LICENSE) (`MPL-2.0`). The distribution contains the complete license text. Any future source files can include the SPDX identifier `MPL-2.0` and the Exhibit A notice where appropriate. Rights in contributions and project ownership must be verified before licensing.

