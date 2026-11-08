# SolarShade - development roadmap

**Status:** Planned work only. None of the boxes are marked completed. Estimates are rough.

## Product-level acceptance criterion

A deterministic demo produces plausible shadows that match reference test cases.

## Estimated work breakdown

| Step | Milestone | Estimated hours | Observable outcome |
|---|---|---:|---|
| 1 | Implement date/time and solar angles | 10 | Reference-tested azimuth/elevation calculations |
| 2 | Build basic 3D roof and obstacles | 10 | Editable scene demo |
| 3 | Implement shadow and exposure estimator | 12 | Numerical fixtures plus visual inspection |
| 4 | Create scenario comparison UI | 9 | Two alternatives compared reproducibly |
| 5 | Add export and save | 7 | Local JSON project and chart export |
| 6 | Tests and user guidance | 10 | Documented accuracy limitations and setup |
| | **Total estimated** | **58** | |

## Detailed milestones

### 1. Implement date/time and solar angles (10 estimated hours)

- [ ] Deliverable: Reference-tested azimuth/elevation calculations.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 2. Build basic 3D roof and obstacles (10 estimated hours)

- [ ] Deliverable: Editable scene demo.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 3. Implement shadow and exposure estimator (12 estimated hours)

- [ ] Deliverable: Numerical fixtures plus visual inspection.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 4. Create scenario comparison UI (9 estimated hours)

- [ ] Deliverable: Two alternatives compared reproducibly.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 5. Add export and save (7 estimated hours)

- [ ] Deliverable: Local JSON project and chart export.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 6. Tests and user guidance (10 estimated hours)

- [ ] Deliverable: Documented accuracy limitations and setup.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

## QA and release gates

- [ ] A real runnable implementation exists, with verified setup commands in `README.md`.
- [ ] Automated tests pass in a clean environment and failures are actionable.
- [ ] Only fabricated, original, openly licensed, or otherwise authorized sample data is published.
- [ ] No passwords, API keys, secrets, customer records, or employer/client confidential artifacts appear in repository history.
- [ ] A source-linked change log and actual progress notes distinguish finished work from plans.
- [ ] The GitHub history preserves authentic work and authorship; do **not** manufacture or backdate commits.

## Parking lot and risks

- Technical: Visibility approximations and solar conventions require numerical benchmarks and boundary tests.
- Commercial hypothesis (not validated): Advanced analysis/report exports and design-software adapters.
- Beyond MVP: defer paid extensions and hosted features until the underlying product works.
