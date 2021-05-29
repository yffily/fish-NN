# Fish Bayesian Neural Network Proof of Concept

This is a rough proof of concept that a Probabilistic Bayesian Neural Network can be trained to generate stochastic trajectories resembling the motion of Astyanax mexicanus fish in a circular tank.

The training data is from a 20-minute video of Astyanax mexicanus surface fish aged 70 days, collected by the [Cavefish Trilab](https://www.cavefishtrilab.com) at Florida Atlantic University. The trajectory was extracted with [trilab-tracker](https://github.com/yffily/trilab-tracker).

The design of the neural network was inspired by https://keras.io/examples/keras_recipes/bayesian_neural_networks/.
