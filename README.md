# n_pendulum
Simulator in python of a pendulum made up of an arbitrary number of bars

## Setup
  ```
  pip install requirements.txt
  ```

## Number of bars
  - You can set it with the variable num_bars
  - It is also possible to create your own initial velocities and angles, in the form of numpy array

## Expected perfomance
  - Using fourth order runge-kutta, the program handles well up to 17 bars
  - After that, problems due to the approximation start to arise
  - Also, since it is runge-kutta, after a long time in simulation, energy varies slightly
