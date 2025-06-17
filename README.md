# Two different micro-polar phase-field models for brittle fracture and their open-source finite element implementation

Realizing the limitations of classical phase-field fracture models and the need for the development of non-local phase-field models that can capture the experimentally observed size 
effects in brittle and quasi-brittle materials, we propose thermodynamically consistent volumetric-deviatoric and spectral decomposition-based phase-field models (PFMs) for brittle
fracture in micro-polar continua. For developing the proposed models, we have considered the micro-rotation as an additional kinematic descriptor, and have derived the balance equations
by invoking the virtual power principle. On satisfying the thermodynamic laws, we have determined the constitutive relations for the thermodynamic fluxes and demonstrated that any 
dissipative effect can easily be incorporated into the proposed models. We have provided an open-source finite element (FE) implementation of the micro-polar PFMs using Gridap in Julia.
The implementation includes various benchmark problems to illustrate how the responses in a specimen change with the variations in micro-polar material parameters. Through a series of 
numerical examples with different values of micro-polar material parameters, we have showcased both the capabilities and limitations of the proposed volumetric-deviatoric and spectral
decomposition-based micro-polar PFMs.

# See the details using the link below:

https://www.sciencedirect.com/science/article/abs/pii/S0013794423007403

# Cite this article:

@article{behera2024two,
  title={Two different micro-polar phase-field models for brittle fracture and their open-source finite element implementation},
  author={Behera, Akash Kumar and Das, Aniruddha and Rahaman, Mohammad Masiur},
  journal={Engineering Fracture Mechanics},
  volume={295},
  pages={109782},
  year={2024},
  publisher={Elsevier}
}
