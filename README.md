# CISS-Simulator
Simulate and visualize how electron transmission and spin polarization differ as electrons pass through left-handed vs right-handed chiral molecular structures (such as DNA or peptides), capturing the CISS effect.

ciss-sim/
  ciss/
    __init__.py
    geometry.py        # helix coords, left/right, pitch, radius, twist
    hamiltonian.py     # TB + SOC construction
    leads.py           # wide-band self-energies
    transport.py       # transfer matrix / Green’s functions
    sweep.py           # param sweeps + CSV export
  notebooks/
    01_basic.ipynb
    02_parameter_sweeps.ipynb
    03_disorder_decoherence.ipynb
  examples/
    presets.json       # DNA-like, polyproline-like
  tests/
    test_symmetries.py
  README.md  LICENSE  CITATION.cff  environment.yml  pyproject.toml
