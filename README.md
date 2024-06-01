# Scientific Computing Exercises

Exercises for submission to Scientific Computing class at UvA (MSc Computational Science). 

## Exercise Set 1

1. 1D wave equation
2. 2D time-dependent diffusion equation
3. 2D Time-independent (Laplace) diffusion equation using
    - Jacobi iteration
    - Gauss-Seidel iteration
    - Successive Over Relaxation (SOR)

### Some visual results

#### Wave equation

<div style="padding: 20px; max-width: 90%;">
    <img src="media/ex1/wave_equation.png" alt="Wave equation" style="height: 150px;"/>
    <img src="media/ex1/animated_wave_1.gif" alt="Animated wave" style="height: 150px;"/>
</div>

#### Diffusion equation
<div style="padding: 20px; max-width: 90%;">
    <img src="media/ex1/diffusion_at_different_times.png" alt="Diffusion through time" style="height: 180px"/>
    <img src="media/ex1/2d_diffusion_until_equillibrium.gif" alt="Animated diffusion" style="height: 180px;"/>
</div>

#### Laplace solvers

<div style="padding: 20px; max-width: 90%;">
    <img src="media/ex1/convergence_measure.png" alt="Diffusion through time" style="height: 194px;"/>
    <img src="media/ex1/laplace_comparison.png" alt="Laplace solvers analysis" style="height: 194px;"/>
</div>

## Exercise Set 2
1. Diffusion Limited Aggregation (DLA) using
    - SOR
    - Agent-based Monte-Carlo (Random Walkers)
2. Gray-Scott model (reaction-diffusion system)

### Some visual results

<div style="display: flex; justify-content: center;">
  <div style="padding: 10px; max-width: 45%;">
    <img src="media/ex2/final_concentration_dla_iters_500_iters_eta_1.5.png" alt="DLA simulation" style="height: 250px; width: 100%;"/>
    <p align="center">SOR (Laplace) solution after 500 iterations</p>
  </div>
  <div style="padding: 10px; max-width: 45%;">
    <img src="media/ex2/final_object_and_walkers_at_t=82604_p=0.5_terminate_at_450.png" alt="Animated wave" style="height: 250px; width: 100%;"/>
    <p align="center">MC (Random Walker) solution to size 450</p>
  </div>
</div>

## Exercise Set 3
1. Numerical solutions to Eigenmodes of drums or membranes (wave equation on 2D elastic material)
2. Solving steady state of diffusion equations
3. Applying the Leapfrog method - efficient time integration