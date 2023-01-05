# State estimation and localization using EKF

Kalman filtering, also known as linear quadratic estimation (LQE), is an algorithm that uses a series of measurements observed over time, including statistical noise and other inaccuracies, and produces estimates of unknown variables that tend to be more accurate than those based on a single measurement alone, by estimating a joint probability distribution over the variables for each timeframe.

Since in real world, we mostly deal with non linear systems, but kalman filter is ineffective incase of non linear model. So We prefer to switch to Extended Kalman filter. In estimation theory, the extended Kalman filter (EKF) is the nonlinear version of the Kalman filter which linearizes about an estimate of the current mean and covariance.

Here is one of the solution of assignments from **State Estimation and Localization for Self-Driving Cars**. Estimating the robots trajectory with the help of given landmarks positions.
