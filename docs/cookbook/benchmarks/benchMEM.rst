============
benchMEM.mdp
============

::

   integrator                     = md
   tinit                          = 0
   dt                             = 0.002
   nsteps                         = 10000
   init-step                      = 0
   simulation-part                = 1
   comm-mode                      = Linear
   nstcomm                        = 100
   bd-fric                        = 0
   ld-seed                        = 1993
   emtol                          = 1e-06
   emstep                         = 0.01
   niter                          = 100
   fcstep                         = 0
   nstcgsteep                     = 1000
   nbfgscorr                      = 10
   rtpi                           = 0.05
   nstxout                        = 0
   nstvout                        = 0
   nstfout                        = 0
   nstlog                         = 0
   nstcalcenergy                  = 100
   nstenergy                      = 0
   nstxout-compressed             = 0
   compressed-x-precision         = 1000
   cutoff-scheme                  = Verlet
   nstlist                        = 10
   pbc                            = xyz
   periodic-molecules             = false
   verlet-buffer-tolerance        = 0.005
   rlist                          = 1
   coulombtype                    = PME
   coulomb-modifier               = Potential-shift
   rcoulomb-switch                = 0
   rcoulomb                       = 1
   epsilon-r                      = 1
   epsilon-rf                     = 1
   vdw-type                       = Cut-off
   vdw-modifier                   = Potential-shift
   rvdw-switch                    = 1.2
   rvdw                           = 1
   DispCorr                       = No
   table-extension                = 1
   fourierspacing                 = 0.12
   fourier-nx                     = 96
   fourier-ny                     = 96
   fourier-nz                     = 80
   pme-order                      = 4
   ewald-rtol                     = 1e-05
   ewald-rtol-lj                  = 1e-05
   lj-pme-comb-rule               = Geometric
   ewald-geometry                 = 0
   epsilon-surface                = 0
   tcoupl                         = Berendsen
   nsttcouple                     = 10
   nh-chain-length                = 0
   print-nose-hoover-chain-variables = false
   pcoupl                         = Berendsen
   pcoupltype                     = Isotropic
   nstpcouple                     = 10
   tau-p                          = 1
   compressibility                = 4.5e-05 4.5e-05 4.5e-05 0 0 0
   ref-p                          = 1 1 1 0 0 0
   refcoord-scaling               = No
   posres-com                     = 0 0 0
   posres-comB                    = 0 0 0
   QMMM                           = false
   QMconstraints                  = 0
   QMMMscheme                     = 0
   MMChargeScaleFactor            = 1
   qm-opts:
   ngQM                           = 0
   constraint-algorithm           = Lincs
   continuation                   = false
   Shake-SOR                      = false
   shake-tol                      = 0.0001
   lincs-order                    = 4
   lincs-iter                     = 1
   lincs-warnangle                = 30
   nwall                          = 0
   wall-type                      = 9-3
   wall-r-linpot                  = -1
   wall-atomtype[0]               = -1
   wall-atomtype[1]               = -1
   wall-density[0]                = 0
   wall-density[1]                = 0
   wall-ewald-zfac                = 3
   pull                           = false
   awh                            = false
   rotation                       = false
   interactiveMD                  = false
   disre                          = No
   disre-weighting                = Equal
   disre-mixed                    = false
   dr-fc                          = 1000
   dr-tau                         = 1.25
   nstdisreout                    = 100
   orire-fc                       = 0
   orire-tau                      = 0
   nstorireout                    = 100
   free-energy                    = no
   cos-acceleration               = 0
   deform                         = 0 0 0 0 0 0
   simulated-tempering            = false
   swapcoords                     = no
   userint1                       = 0
   userint2                       = 0
   userint3                       = 0
   userint4                       = 0
   userreal1                      = 0
   userreal2                      = 0
   userreal3                      = 0
   userreal4                      = 0
   nrdf                           = 163634
   ref-t                          = 300
   tau-t                          = 0.1
   annealing                      = No
   annealing-npoints              = 0
   acc:	                            0           0           0
   nfreeze:                         N           N           N
   energygrp-flags[  0]:            0
