Experiment: high precision measurement of energy loss of electron beam in water.

Delivering reference data for electrons in liquid water below 100 keV down to 1KeV would be the main goal
(e.g. energy loss, scattering).

This is clearly innovative, but with high risk of failure... Probably several groups have already tried
something (Berkeley, Sherbrooke, Notre Dame, NASA/Houston, etc.).

The challenge is really at low energies, data do not exist for the liquid phase
see for example the work of 2026 attached (various models are listed in Table 1, and resulting stopping powers
in Fig 12
the only reference data, from ICRU90, stop at 1 keV and nothing exists below such energy).



Strategy:

- impinging electron beam on various thicknesses of liquid water at various conditions of pressure/temperature
- measure with high precision energy loss distributions as a function of thickness.



Possible help:

L. Braby is another (cool) expert on the topic, @ Texas A&M

https://engineering.tamu.edu/nuclear/profiles/braby-leslie.html



Beam:

Jlab UITF beam from 7 MeV down to 500 KeV at 1% precision level

Proposal and feasibility assessment:

- [LaTeX source](proposal.tex) and [compiled PDF](proposal.pdf).
- The proposal distinguishes electron kinetic energy near 1 keV from a 1 keV energy-loss signal.
- The beam range and meaning of 1% precision above remain planning inputs to confirm with UITF.
- Build with Meson, Ninja, and a TeX installation providing latexmk and pdflatex:

```sh
meson setup build
meson compile -C build
```

The generated PDF is `build/proposal.pdf`. To refresh the tracked copy, run:

```sh
cp build/proposal.pdf proposal.pdf
```

All PDFs, including the reference papers, are stored using Git LFS. Install Git LFS before cloning;
in an existing checkout, use `git lfs install --local` and `git lfs pull` to retrieve the PDF contents.


  codex resume 01a1c63d-4953-7392-bfcf-577dddfad527

