# Extraction Spec

Framework: `anabelian_reconstruction`

Required constants:

- `kappa_reconstruction`
- `sigma_sections`
- `kappa_compact`
- `rho_rigidity`
- `anabelian_lock`
- `eps_coh`
- stitch key `sigma_star_can`

All constants are extracted from explicit formulas in `artifacts/constants_extraction_inputs.json`, promoted into the registry and stitch files, then consumed by the closure guard.
