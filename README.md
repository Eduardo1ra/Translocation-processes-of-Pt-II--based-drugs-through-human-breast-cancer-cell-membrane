# Translocation-processes-of-Pt-II--based-drugs-through-human-breast-cancer-cell-membrane
Files of the paper: Translocation processes of Pt(II)-based drugs through human breast cancer cell membrane: in silico experiments

Input files, topologies, atomic parameters, and initial coordinates for molecular dynamics simulations. Files for the Steered Molecular Dynamics simulations and for Umbrella Sampling method are also available. The files and scripts were prepared based on the Amber tutorial: https://github.com/callumjd/AMBER-Umbrella_COM_restraint_tutorial

In summary, for each system (cddp>c_memb, cpx>c_memb, oxa>c_memb, cdcla>c_memb, and cdclo>c_memb), we run 140 windows of simulations (70 windows for the processes of drug influx and 70 windows for the processes of drug efflux) along the reaction coordinate defined as the axis perpendicular to the membrane plane. Therefore, we prepared 70 files (prod0.in, COM_dist0.RST, frame_0.0.rst) for each system. We included here some examples of these files referring to the window 0.
