# SolarShade - technical plan

**Planning document, not an implementation report.**

## Product objective

A narrow, explainable 3D shading viewer with offline fixture geometry and time-of-day comparisons.

## Intended system boundary

- **Input:** Generic demonstration coordinates and fictional roof geometry.
- **Processing stages:** Solar position and coordinate calculations; Basic 3D geometry and ray intersection; Local project model and scenario controls; CSV/PNG export modules.
- **Output:** A deterministic demo produces plausible shadows that match reference test cases.
- **Runtime / build stack (tentative):** TypeScript, Three.js, Vite, Vitest
- **Explicitly excluded:** Professional structural assessment, full yield bankability forecasts, or recording private residential addresses.

## Functional modules

- Create simple roofs and obstruction blocks from editable geometry
- Calculate solar azimuth and elevation for declared test coordinates and dates
- Visualize time-step shadows and panel exposure estimates
- Compare orientation, tilt, and obstruction alternatives
- Export reproducible project JSON and assumption-tagged charts

## Demonstration and acceptance cases

**Test 1:** Illustrate a chimney shadow on a fictional roof

**Test 2:** Compare exposure at two solar times

**Test 3:** Confirm sun-angle calculations against known references

## Safety, privacy, and provenance

1. Keep example datasets fictional, self-created, or appropriately licensed.
2. Run locally for the initial prototype; do not collect data on actual third parties.
3. Document origin and versions of external specifications and dependencies.
4. Exclude production credentials; put environment variable *names* only in `.env.example` if required later.
5. Do not make certification, legal compliance, professional safety, or performance guarantees without independent validation.

## Engineering unknowns and constraints

Visibility approximations and solar conventions require numerical benchmarks and boundary tests.

## Release definition

A first release requires a runnable prototype, verified README instructions, automated tests tied to the three demonstrations, the full LICENSE file, and an honest public GitHub development history. The roadmap estimates are hypotheses until reviewed during implementation.
