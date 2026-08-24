# Awesome Photonics with stars

> A curated list of awesome resource for photonic engineers, physicists and hobbyists

Most tools in this list are written or have a python interface, which require some basic knowledge of python. If you are new to python you can find many [books](https://jakevdp.github.io/PythonDataScienceHandbook/index.html), [YouTube videos](https://www.youtube.com/c/anthonywritescode) and [courses](https://github.com/joamatab/practical-python) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2022-04-28 available online.
If you are new to Git and Python I recommend reading this [article](https://lightlab.readthedocs.io/en/latest/_static/gettingStarted/index.html)

## Contents

<!-- toc -->

* [layout](#layout): define the geometrical shapes that guide the light.
* [simulation](#simulation): simulate how photons propagate, and optimize the geometrical shapes
* [lab automation](#lab-automation): Control instruments in the lab
* [data analysis](#data-analysis)
* [visualization](#visualizatio)
* [electronics](#electronics)
* [other links](#other-links)

<!-- tocstop -->

## layout

* [klayout](https://github.com/KLayout/klayout) ⭐ 1,182 | 🐛 217 | 🌐 C++ | 📅 2026-08-23 - layout viewer with python API
  * [siepic-tools](https://github.com/lukasc-ubc/SiEPIC-Tools) ⭐ 266 | 🐛 82 | 🌐 Python | 📅 2025-10-10 - code driven PCells and GUI driven layouts.
  * [KQcircuits](https://github.com/iqm-finland/KQCircuits) ⭐ 199 | 🐛 11 | 🌐 Python | 📅 2026-06-18 - Quantum circuits pdk.
  * [kfactory](https://github.com/gdsfactory/kfactory) ⭐ 65 | 🐛 13 | 🌐 Python | 📅 2026-08-24
  * [siepic-ebeam-pdk](https://github.com/lukasc-ubc/SiEPIC_EBeam_PDK) ⭐ 29 | 🐛 1 | 🌐 Logos | 📅 2024-10-14
  * [zero-pdk](https://github.com/lightwave-lab/zeropdk) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2023-01-23 - klayout pure python pdk.
  * [klayout cross-section in python](https://github.com/gdsfactory/klayout_pyxs) ⭐ 19 | 🐛 8 | 🌐 Python | 📅 2026-07-01 - Port from ruby to python to xsection macro
  * [flayout](https://github.com/flaport/flayout/) ⭐ 13 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-10-25
  * [spicex: netlist extraction](https://github.com/fsitok/spicex) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2019-01-31
  * [simplify polygons](https://github.com/fsitok/klayout-simplify) ⭐ 7 | 🐛 1 | 📅 2022-12-20
  * [xsection, klayout-ipc, klayout-gadgets, lytest, lymask](https://github.com/atait?tab=repositories)
  * [gds3xtrude](https://codeberg.org/tok)
  * [klayout python](https://github.com/shamil777/KLayout-python)

* [gdsfactory](https://gdsfactory.github.io/gdsfactory/) [code](https://github.com/gdsfactory/gdsfactory) ⭐ 1,017 | 🐛 124 | 🌐 Python | 📅 2026-08-21 - includes plugins to other tools.
  * [skywater130](https://gdsfactory.github.io/skywater130) and [code](https://github.com/gdsfactory/skywater130) ⭐ 58 | 🐛 30 | 🌐 Python | 📅 2026-08-20
  * [ubcpdk](https://gdsfactory.github.io/ubc) and [code](https://github.com/gdsfactory/ubc) ⭐ 35 | 🐛 16 | 🌐 Python | 📅 2026-08-07
  * [gplugins](https://gdsfactory.github.io/gplugins)
  * [gf180](https://gdsfactory.github.io/gf180)
  * [vtt](https://gdsfactory.github.io/vtt)

* [gdstk](https://github.com/heitzmann/gdstk) ⭐ 495 | 🐛 52 | 🌐 C++ | 📅 2026-07-24 - faster than gdspy (from same author)
  * [pyphotonics](https://github.com/rohanku/pyphotonics) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2022-07-09

* [qiskit-metal](https://github.com/Qiskit/qiskit-metal) ⭐ 425 | 🐛 29 | 🌐 Jupyter Notebook | 📅 2026-08-11 - IBM superconducting based qubits.

* [gdspy based tools](https://github.com/heitzmann/gdspy) ⚠️ Archived
  * [phidl](https://github.com/amccaugh/phidl) ⭐ 234 | 🐛 4 | 🌐 Python | 📅 2025-08-08 - made for superconducting detectors
    * soen-pdk [docs](https://pages.nist.gov/SOEN-PDK/) and [code](https://github.com/usnistgov/SOEN-PDK) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2021-07-24
  * [picwriter](https://github.com/DerekK88/PICwriter) ⭐ 53 | 🐛 9 | 🌐 Python | 📅 2024-02-05
  * [BerkeleyPhotonicsGenerator](https://github.com/BerkeleyPhotonicsGenerator/BPG) ⭐ 37 | 🐛 31 | 🌐 Python | 📅 2024-08-09
  * [Ayar cell generator](https://github.com/AyarLabs/ACG) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2020-06-01

* shapely based tools
  * [gdshelpers](https://github.com/HelgeGehring/gdshelpers) ⭐ 126 | 🐛 9 | 🌐 Python | 📅 2022-05-25 - includes superconducting detectors.
  * [dphox](https://github.com/solgaardlab/dphox) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2022-07-14 - includes 3D MEMs structures

* [masque](https://mpxd.net/code/jan/masque)

* [klamath](https://mpxd.net/code/jan/klamath)

* [nazca](https://nazca-design.org/download/)

* layout viewers
  * [GDS3D](https://github.com/trilomix/GDS3D/) ⭐ 266 | 🐛 17 | 🌐 C++ | 📅 2024-08-20
  * [GDS2WebGL](https://github.com/s-holst/GDS2WebGL) ⭐ 61 | 🐛 5 | 🌐 Python | 📅 2020-08-23
  * [kweb](https://github.com/gdsfactory/kweb) ⚠️ Archived
  * [klayout](https://www.klayout.de/) - Best open source layout viewer.

## simulation

* mode solver:

  * Finite Element
    * [elmer](https://github.com/elmercsc/elmerfem) ⭐ 1,674 | 🐛 79 | 🌐 Fortran | 📅 2026-08-24
    * [jax-fem](https://github.com/deepmodeling/jax-fem) ⭐ 741 | 🐛 27 | 🌐 Python | 📅 2026-08-20
    * [ngsolve](https://github.com/NGSolve/ngsolve) ⭐ 575 | 🐛 22 | 🌐 C++ | 📅 2026-08-17
    * [femwell](https://helgegehring.github.io/femwell/)
    * [palace](https://awslabs.github.io/palace/stable/)

  * Finite Difference
    * [tidy3d](https://github.com/flexcompute/tidy3d) ⭐ 360 | 🐛 86 | 🌐 Python | 📅 2026-08-07 Mode solver is open source
    * [EMpy](https://github.com/lbolla/EMpy) ⭐ 228 | 🐛 3 | 🌐 Python | 📅 2026-08-24
    * [khronos](https://github.com/facebookresearch/Khronos.jl) ⚠️ Archived
    * [philsol](https://github.com/philmain28/philsol) ⭐ 45 | 🐛 2 | 🌐 Python | 📅 2026-03-17 - Allows bends.
    * [pyMWM](https://github.com/mnishida/PyMWM) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-01-16
    * [pymode](https://github.com/smartalecH/pyMode) ⭐ 6 | 🐛 10 | 🌐 Python | 📅 2021-06-29 - Allows bends.
      * [wgms3d](http://www.soundtracker.org/raw/wgms3d/)
    * [modes](https://modes.readthedocs.io/en/latest/)
    * [mpb](https://mpb.readthedocs.io/en/latest/Scheme_Tutorial/) - Bloch mode solver.
    * [mpb](https://mpb.readthedocs.io/en/latest/Scheme_Tutorial/) - Bloch mode solver.
    * [protis](https://protis.gitlab.io) - Bloch mode solver (2D only), support for multiple backends (numpy/autograd/torch/jax)

* component design:

  * [SiPANN (neural networks for photonics component design)](https://github.com/contagon/SiPANN) ⭐ 54 | 🐛 9 | 🌐 Python | 📅 2026-02-05
  * [TCAD](https://tcadcentral.com/Software.html#open-source-tcad-software) [tcad repos](https://github.com/thesourcerer8/OpenSourceTCAD) ⭐ 47 | 🐛 2 | 🌐 Dockerfile | 📅 2026-06-25 [TCAD Overview spreadsheet here](https://docs.google.com/spreadsheets/d/1dK1GxGl1C7v3rhWKw3RcbeZsRre66HPAOPFbgYni74A/edit?pli=1#gid=0)
    * [TCAD docker containers](https://github.com/thesourcerer8/OpenSourceTCAD) ⭐ 47 | 🐛 2 | 🌐 Dockerfile | 📅 2026-06-25
    * [Suprem4](https://github.com/cogenda/Suprem4) ⭐ 39 | 🐛 2 | 🌐 C | 📅 2014-10-09 - Process simulator (no python)
    * [Charon](https://charon.sandia.gov/) - Paralell TCAD simulator. [GitHub mirror](https://github.com/tcadsoftware/charon) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2022-07-29
    * [pisces](https://github.com/ComputerWhisperer/pisces) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2020-07-12 - Poison and continuity equation solver (no python)
    * [devsim](https://devsim.org/) - Semiconductor Device Simulator
    * [BOSIM](https://eexu.home.ece.ust.hk/BOSIM.html)
  * [Lightening-Transformer: A Dynamically-operated Optically-interconnected Photonic Transformer Accelerator](https://github.com/zhuhanqing/Lightening-Transformer) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2025-02-05
  * [Sipkit](https://github.com/Photonic-Architecture-Laboratories/si-photonics-toolkit) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2025-07-02 - A JAX-compatible toolkit providing fundamental waveguide and material properties to aid in the design of silicon photonic components.
  * FDTD - Finite differences time domain.
    * [meep FDTD](https://github.com/NanoComp/meep) ⭐ 1,747 | 🐛 375 | 🌐 C++ | 📅 2026-08-21
      * [grating coupler example](https://github.com/simbilod/grating_coupler_meep) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2022-07-10
      * [meep ipkiss integration](https://github.com/luceda/ipkiss_meep_integration) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2019-06-20
      * [meep docker image](https://hub.docker.com/r/mochen4/meepdocker) - [code](https://github.com/mochen4/meepdocker) ⭐ 1 | 🐛 0 | 📅 2021-09-19
    * [Python 3D FDTD simulator](https://github.com/flaport/fdtd) ⭐ 714 | 🐛 28 | 🌐 Python | 📅 2025-09-22 - Written in PyTorch.
    * tidy3d client [docs](https://docs.simulation.cloud/projects/tidy3d/en/latest/) and [code](https://github.com/flexcompute/tidy3d) ⭐ 360 | 🐛 86 | 🌐 Python | 📅 2026-08-07 - Server is propietary.
    * [fdtdx](https://github.com/ymahlau/fdtdx) ⭐ 337 | 🐛 45 | 🌐 Python | 📅 2026-08-24
    * [fdtdz](https://github.com/spinsphotonics/fdtdz) ⭐ 160 | 🐛 6 | 🌐 C++ | 📅 2025-02-08
    * [emopt FDTD](https://github.com/anstmichaels/emopt) ⭐ 119 | 🐛 9 | 🌐 Python | 📅 2026-02-17
    * [Luminescent](https://github.com/paulxshen/Luminescent.jl) ⭐ 89 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2026-05-08
    * [khronos](https://github.com/facebookresearch/Khronos.jl) ⚠️ Archived
    * [ARTEMIS](https://github.com/AMReX-Microelectronics/artemis) ⭐ 45 | 🐛 15 | 🌐 C++ | 📅 2026-08-18 - High-performance FDTD solver coupled with magnetization dynamics (LLG), GPU-accelerated for microelectronics and superconducting devices
    * [GSvit](http://gsvit.net/) - GPU support
  * FDFD - Finite differences frequency domain.
    * [ceviche (2D only) FDTD and FDFD](https://github.com/twhughes/ceviche) ⭐ 422 | 🐛 10 | 🌐 Python | 📅 2023-07-06
    * [spins FDFD on GPU](https://github.com/stanfordnqp/spins-b) ⭐ 351 | 🐛 15 | 🌐 Python | 📅 2024-04-13
    * [jaxwell](https://github.com/stanfordnqp/jaxwell) ⚠️ Archived
  * EME - Eigen mode expansion.
    * [CAMFR](https://github.com/demisjohn/CAMFR) ⭐ 79 | 🐛 9 | 🌐 C++ | 📅 2023-03-21
    * [meow](https://github.com/flaport/meow) ⭐ 55 | 🐛 6 | 🌐 Python | 📅 2026-06-16
    * [emepy](https://github.com/BYUCamachoLab/emepy) ⭐ 50 | 🐛 22 | 🌐 Python | 📅 2022-10-03
  * FEM:
    * [gyptis](https://gyptis.gitlab.io) - based on FEniCS, automatic differentiation with dolfin-adjoint
    * [GetDP](https://getdp.info/)
  * RCWA:
    * [S4](https://github.com/victorliu/S4) ⭐ 186 | 🐛 80 | 🌐 C++ | 📅 2021-01-26
    * [FMMAX](https://github.com/facebookresearch/fmmax) ⚠️ Archived
    * [grcwa](https://github.com/weiliangjinca/grcwa) ⭐ 108 | 🐛 4 | 🌐 Python | 📅 2026-04-13 - automatic differentiation included with autograd
    * [inkstone](https://github.com/alexysong/inkstone) ⭐ 71 | 🐛 3 | 🌐 Python | 📅 2024-11-02
    * [nannos](https://nannos.gitlab.io) - support for multiple backends (numpy/autograd/torch/jax)
  * FIT:
    * [wakis](https://wakis.readthedocs.io/) - a 3D Time-domain Electromagnetic solver that solves the Integral form of Maxwell's equations using the Finite Integration Technique (FIT) numerical method.
  * [Bempp](https://bempp.com) - Open-source computational boundary element platform to solve electrostatic, acoustic and electromagnetic problems
  * [OpenModes](https://openmodes.readthedocs.io) - Mode solver for open electromagnetic structures based on the method of moments (MOM)
  * [pyGDM](https://homepages.laas.fr/pwiecha/pygdm_doc/) - Green dyadic method for nanophotonics, including evolutionary optimization
  * [inverse design](http://metanet.stanford.edu/code/)
    * [wavetorch](https://github.com/fancompute/wavetorch) ⭐ 540 | 🐛 3 | 🌐 Python | 📅 2020-02-08
    * [lumopt](https://github.com/chriskeraly/lumopt) ⭐ 211 | 🐛 18 | 🌐 Python | 📅 2024-03-20
    * [angler](https://github.com/fancompute/angler/) ⭐ 194 | 🐛 11 | 🌐 Python | 📅 2019-12-14 - Frequency-domain photonic simulation and inverse design optimization for linear and nonlinear devices.
    * ceviche-challenges [code](https://github.com/google/ceviche-challenges) ⚠️ Archived - Photonic inverse designs based on the FDFD simulator Ceviche
    * [glonet: global optimization based on generative neural networks](https://github.com/jonfanlab/GLOnet) ⭐ 125 | 🐛 1 | 🌐 Python | 📅 2022-11-17
    * SPLayout [code](https://github.com/Hideousmon/SPLayout) ⭐ 72 | 🐛 0 | 🌐 Python | 📅 2025-09-06 [docs](https://splayout.readthedocs.io/en/latest/index.html)
    * [NIDN](https://github.com/esa/NIDN) ⭐ 54 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2023-10-31 - Inverse design of metamaterials, photonic crystals, ... using PyTorch
    * A Neural Operator-based Surrogate Solver for Free-Form Electromagnetic Inverse Design \[[Paper](https://arxiv.org/pdf/2302.01934.pdf)] \[[Github](https://github.com/tfp-photonics/neurop_invdes) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2024-02-28]
  * ray tracing:
    * [scattering tools](https://github.com/rafael-fuente/diffractsim) ⭐ 1,065 | 🐛 21 | 🌐 Python | 📅 2026-07-24
    * [optiland](https://github.com/HarrisonKramer/optiland) ⭐ 919 | 🐛 31 | 🌐 Python | 📅 2026-08-20 - Comprehensive optical design with GPU-accelerated ray tracing via PyTorch
    * [rayoptics](https://github.com/mjhoptics/ray-optics) ⭐ 401 | 🐛 4 | 🌐 Python | 📅 2026-08-22 - Optical design and analysis in Python
    * [ray tracing](https://github.com/DCC-Lab/RayTracing) ⭐ 344 | 🐛 2 | 🌐 Python | 📅 2026-07-08
    * [rayopt](https://github.com/quartiq/rayopt) ⭐ 310 | 🐛 13 | 🌐 Python | 📅 2023-08-15
    * [pyrate](https://github.com/mess42/pyrate) ⭐ 203 | 🐛 29 | 🌐 Python | 📅 2021-06-26 - Optical raytracing based on Python
  * adaptive optics
    * [AOtools](https://github.com/AOtools)
  * multisolvers
    * [simphox (FDTD, beamPropagation, circuit simulation)](https://github.com/fancompute/simphox) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2023-01-07
  * transfer matrix
    * [TMM](https://github.com/sbyrnes321/tmm) ⭐ 265 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-11-26
    * [tmmax](https://github.com/bahremsd/tmmax) ⭐ 38 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2026-02-11
    * [PyElli](https://github.com/PyEllips/pyElli) ⭐ 38 | 🐛 23 | 🌐 Jupyter Notebook | 📅 2026-08-03 - Toolkit for 1D optical simulations, with a focus on ellipsometry

* circuit simulation:

  * pyFDA filter design [code](https://github.com/chipmuenk/pyfda) ⭐ 730 | 🐛 39 | 🌐 Python | 📅 2026-08-23 and [docs](https://pyfda.readthedocs.io/en/latest/manual/input_specs.html)
  * Sparameter linear solvers
    * [SignalIntegrity (linear circuit simulation)](https://github.com/TeledyneLeCroy/SignalIntegrity) ⭐ 212 | 🐛 17 | 🌐 Python | 📅 2026-08-24
    * [simphony (linear circuit solver)](https://github.com/BYUCamachoLab/simphony) ⭐ 170 | 🐛 16 | 🌐 Python | 📅 2026-07-10
    * SAX [code](https://github.com/flaport/sax) ⭐ 129 | 🐛 8 | 🌐 Python | 📅 2026-06-19 and [docs](https://flaport.github.io/sax/) - Differentiable circuit solver.
    * [photontorch docs](https://docs.photontorch.com/) - [code](https://github.com/flaport/photontorch) ⭐ 93 | 🐛 4 | 🌐 Python | 📅 2022-06-16 - Includes time domain.
    * [opics](https://github.com/siepic/opics) ⭐ 54 | 🐛 6 | 🌐 Python | 📅 2023-03-02
    * [lekkersim](https://github.com/mpasson/lekkersim) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-07-12
    * [scikit-rf RF simulator](https://scikit-rf.readthedocs.io/en/latest/)
  * Optical communications
    * [optiCommPy](https://github.com/edsonportosilva/OptiCommPy) ⭐ 207 | 🐛 7 | 🌐 Python | 📅 2026-08-13
    * [QAMpy](https://github.com/ChalmersPhotonicsLab/QAMpy) ⭐ 87 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-04-28 - DSP chain for simulation and equalisation of optical communications signals
  * RF photonic link analysis
    * [Princeton RF photonic notebooks](https://github.com/ericcblow/MWP_RF_Sims/tree/main) ⭐ 12 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-02
  * Spice
    * [pyspice](https://github.com/FabriceSalvaire/PySpice) ⭐ 862 | 🐛 205 | 🌐 Python | 📅 2024-08-13
    * [lcapy](https://github.com/mph-/lcapy) ⭐ 301 | 🐛 39 | 🌐 Python | 📅 2026-08-16 - Linear circuit analysis.
    * [openVAF](https://github.com/pascalkuthe/OpenVAF) ⭐ 195 | 🐛 69 | 🌐 Rust | 📅 2024-08-20 Verilog-A
    * [Xyce](https://xyce.sandia.gov/) - open source, SPICE-compatible, high-performance analog circuit simulator.
    * [VACASK](https://codeberg.org/arpadbuermen/VACASK) Verilog-A

* nonlinear schrodinger equation (NLSE): calculate the propagation of pulses along a fiber/waveguide in the presence of dispersion and nonlinearity.
  * [PyNLO](https://github.com/pyNLO/PyNLO) ⭐ 140 | 🐛 19 | 🌐 Python | 📅 2023-10-17 more capable, but unmaintained
  * [Laserfun](https://github.com/DanHickstein/laserfun) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-02-06 aims for simplicity
  * [PyNLO fork includes Chi2 simulation capabilities](https://cdfredrick.github.io/PyNLO/build/html/index.html)

* Lugiato Lefever Equation (LLE) to calculate propagation in ring resonators:
  * [PyLLE](https://github.com/gregmoille/pyLLE) ⭐ 90 | 🐛 2 | 🌐 Python | 📅 2025-01-24 has more features
  * [PyGLLE](https://github.com/omelchert/pyGLLE) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2022-09-22 is nice and simple

* material database

  * [rii pandas](https://github.com/mnishida/RII_Pandas) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2026-06-28

* lithography simulation
  * [optolithium](https://github.com/xthebat/optolithium) ⚠️ Archived
  * [notebooks](https://github.com/pierremifasol/Lithography-Simulation) ⭐ 130 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2021-10-26
  * [dimmilitho](https://github.com/vincentlv/DimmiLitho) ⭐ 84 | 🐛 4 | 🌐 Python | 📅 2022-07-10
  * [keras based litho model](https://github.com/Dusandinho/PreFab.git) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2023-03-02

* free space
  * [diffractsim](https://github.com/rafael-fuente/diffractsim) ⭐ 1,065 | 🐛 21 | 🌐 Python | 📅 2026-07-24
  * [prysm](https://github.com/brandondube/prysm) ⭐ 350 | 🐛 12 | 🌐 Python | 📅 2026-07-26 - Physical optics with integrated modeling, phase retrieval, segmented systems
  * [lightpipes](https://github.com/opticspy/lightpipes) ⭐ 310 | 🐛 52 | 🌐 Python | 📅 2026-02-26
  * [POPPY](https://github.com/mperrin/poppy) ⭐ 191 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2026-08-20 - Physical Optics Propagation in Python for diffraction modeling
  * [TorchOptics](https://github.com/matthewfilipovich/torchoptics) ⭐ 157 | 🐛 1 | 🌐 Python | 📅 2026-05-13
  * [HCIPy](https://github.com/ehpor/hcipy) ⭐ 143 | 🐛 48 | 🌐 Python | 📅 2026-08-23 - High Contrast Imaging for Python
  * [Poke](https://github.com/Jashcraf/poke) ⭐ 61 | 🐛 39 | 🌐 Jupyter Notebook | 📅 2025-05-05 - Polarization ray tracing and Gaussian beamlet module
  * [waveprop](https://github.com/HelgeGehring/wavepropagation/) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2022-03-18

## verification

* parasitic extraction
  * [speedsterpy](https://github.com/das-dias/speedsterpy)

## lab automation

* backend:

  * [PySerial](https://github.com/pyserial/pyserial) ⭐ 3,565 | 🐛 340 | 🌐 Python | 📅 2026-05-19 - Issue simple serial commands (RS-232, RS485) to instruments (and read data).
  * [PyVISA](https://pyvisa.readthedocs.io/en/latest/) - Allows you to control the lab instruments with python. As the backend you can use NI or [PyVISA-py](https://pyvisa-py.readthedocs.io/en/latest/).

* lab automation repos:
  * [pymeasure](https://github.com/pymeasure/pymeasure) ⭐ 769 | 🐛 206 | 🌐 Python | 📅 2026-08-24
  * [hardware testing framework](https://github.com/google/openhtf) ⭐ 717 | 🐛 140 | 🌐 Python | 📅 2026-08-13 - Google
  * <https://github.com/AlexShkarin/pyLabLib> ⭐ 210 | 🐛 87 | 🌐 Python | 📅 2026-05-02
  * [instrumental](https://github.com/mabuchilab/Instrumental) ⭐ 136 | 🐛 60 | 🌐 Python | 📅 2025-01-01
  * [labrad](https://github.com/labrad/pylabrad) ⭐ 58 | 🐛 79 | 🌐 Python | 📅 2024-09-02
  * [lightlab](https://github.com/lightwave-lab/lightlab) ⭐ 54 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2024-11-13 [docs](https://lightlab.readthedocs.io/en/latest/index.html)
  * [SiePIC lab](https://github.com/SiEPIC/SiEPIClab) ⭐ 40 | 🐛 2 | 🌐 Python | 📅 2024-03-08
  * LabEXT [docs](https://labext.readthedocs.io/en/latest/) and [code](https://github.com/LabExT/LabExT) ⭐ 24 | 🐛 14 | 🌐 Python | 📅 2026-03-31
  * [drivers](https://github.com/SweepMe/instrument-drivers) ⭐ 23 | 🐛 9 | 🌐 Python | 📅 2026-08-17
  * [measurement sequencer](https://github.com/SweepMe/pysweepme) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2026-08-17
  * [pic-wafer](https://github.com/DerekK88/PIC_WaferProbeSystem) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2019-03-25
  * [laval python lab](https://github.com/Simon-Belanger/ULPythonLab) ⭐ 11 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2020-06-01
  * [autosweep](https://github.com/gdsfactory/autosweep) ⭐ 7 | 🐛 5 | 🌐 Python | 📅 2026-08-07 [docs](https://gdsfactory.github.io/autosweep/)
  * [pyrolab](https://github.com/BYUCamachoLab/pyrolab) ⭐ 7 | 🐛 10 | 🌐 Python | 📅 2025-11-20
  * [autogator](https://github.com/BYUCamachoLab/autogator) ⭐ 7 | 🐛 4 | 🌐 Python | 📅 2025-09-04 - camera-assisted motion control and experiment configuration of photonic integrated circuit interrogation platforms.
  * [autolab](https://github.com/autolab-project)

## data analysis

* [wafermap](https://github.com/xlhaw/wfmap) ⭐ 57 | 🐛 1 | 🌐 Python | 📅 2022-11-01
* [wafer data](https://github.com/guanghaofan/wafermap) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2019-08-29
* pandas
* dask
* Webapp
  * [streamlit](https://github.com/streamlit/streamlit) ⭐ 45,602 | 🐛 1,193 | 🌐 Python | 📅 2026-08-24
  * [voila](https://github.com/voila-dashboards/voila) ⭐ 5,939 | 🐛 328 | 🌐 Python | 📅 2026-08-03
  * [plotly dash](https://dash.plotly.com/)

## Visualization

* [Klayout](https://www.klayout.de/) for GDS files
* [Meshlab](https://github.com/cnr-isti-vclab/meshlab) ⭐ 5,798 | 🐛 197 | 🌐 C++ | 📅 2026-08-24 for STL
* [ParaView](https://www.paraview.org/) for data visualization

## electronics

* transmission line [wcalc](https://github.com/dmcmahill/wcalc) ⭐ 16 | 🐛 3 | 🌐 C | 📅 2025-03-09

* schematic capture:
  * elkjs [code](https://github.com/kieler/elkjs) ⭐ 2,721 | 🐛 98 | 🌐 JavaScript | 📅 2026-08-13 [demo](https://rtsys.informatik.uni-kiel.de/elklive/elkgraph.html) - Javascript schematic editor.
  * [skidl: netlist formatting, writing, and reading](https://github.com/devbisme/skidl) ⭐ 1,631 | 🐛 46 | 🌐 Python | 📅 2026-08-20

* layout

  * [VLSI placement](https://github.com/limbo018/DREAMPlace) ⭐ 1,042 | 🐛 92 | 🌐 C++ | 📅 2026-07-18
  * [kicad PCB layout python](https://github.com/atait/kicad-python) ⭐ 80 | 🐛 4 | 🌐 Python | 📅 2026-05-13

* circuit simulation

  * [Spice book](https://github.com/PyLCARS/Python-and-SPICE-Book) ⚠️ Archived

* open source pdks

  * [skywater-pdk](https://github.com/google/skywater-pdk) ⭐ 3,667 | 🐛 199 | 🌐 Python | 📅 2026-07-21

## other links

* [Awesome lists](https://github.com/sindresorhus/awesome) ⭐ 499,517 | 🐛 106 | 📅 2026-08-21
* <https://github.com/awesome-selfhosted/awesome-selfhosted> ⭐ 314,659 | 🐛 0 | 📅 2026-08-22
* [Awesome electronics](https://github.com/kitspace/awesome-electronics) ⭐ 8,058 | 🐛 30 | 📅 2026-01-05
* [Awesome quantum](https://github.com/qosf/awesome-quantum-software) ⭐ 2,382 | 🐛 5 | 📅 2026-08-24
* [Awesome scientific computing](https://github.com/nschloe/awesome-scientific-computing) ⭐ 1,582 | 🐛 17 | 🌐 Python | 📅 2026-07-20
* [princeton notebooks](https://github.com/simbilod/ELE559-simulations) ⭐ 43 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-09-16
* <https://hackmd.io/@joamatab/rJngxJudr#/>
* <https://git.shivering-isles.com/shivering-isles/infrastructure>
* [epda](https://openepda.org)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
