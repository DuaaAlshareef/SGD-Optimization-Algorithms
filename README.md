# SGD Optimization Experiments

This project explores various techniques to enhance the convergence and performance of SGD in optimizing machine learning models. The experiments compare different variants of SGD and Gradient Descent (GD) to determine the most effective methods for achieving stable and accurate solutions.

## Repository Structure
- **Report:** The detailed report of our experiments is available.
- **Code:** The code for running the experiments and generating the plots.


## Experiments

### Sample from the Experiments

<p align="center">
<img src="images/sgd_gd_momentum_distance.png" alt="Alt text" width="400"/>
</p>

## Experiment: SGD with Momentum (SGDm) and Gradient Descent (GD)

Compare the performance of SGD with momentum, SGD with shrinking step sizes, and Gradient Descent.
- **SGD with Momentum**: Improves efficiency and stability by accumulating a velocity vector that smooths updates and helps the optimizer move consistently towards the minimum, even with noisy gradients.

- **SGD with Momentum (SGDm)**: Aims to accelerate convergence and reduce oscillations.
- **SGD with Shrinking Step Sizes**: Switches step sizes to improve convergence stability.
- **Gradient Descent (GD)**: Standard method for optimization.

### Findings
- **SGDm**: Converges faster than standard SGD with shrinking step sizes.
- **GD**: Takes more iterations to converge but ultimately reaches the optimal solution more effectively than SGD methods.
- **Convergence**: SGDm achieves an error below \(10^{-2}\) in approximately 15,000 iterations, whereas GD requires about 23,000 iterations for similar accuracy.


## Conclusion
In this project, we implemented various Stochastic Gradient Descent (SGD) techniques to enhance convergence and performance. These techniques included constant and shrinking step sizes, with and without replacement, averaging, and momentum. Our findings indicate that:

- **Shrinking step sizes** outperform constant ones, achieving lower final errors and more stable convergence.
- **Combining initial constant step sizes with later shrinking ones** improves precision and reduces variability.
- **Averaging in the final iterations** stabilizes convergence and smooths out fluctuations.
- **SGD with momentum** accelerates convergence and reduces oscillations, outperforming standard SGD and traditional Gradient Descent (GD).
- **Using indices without replacement** enhances generalization and speeds up convergence, especially for smaller datasets.

Overall, these methods significantly improve training efficiency and model performance by balancing rapid initial progress with precise long-term convergence.



## How to Use
1. **Clone the Repository:**
   ```bash
<<<<<<< HEAD
   git clone https://github.com/your-repo/sgd-optimization-experiments.git
   
=======
   git clone https://github.com/DuaaAlshareef/SGD-Optimization-Algorithms.git
>>>>>>> e929067 (Added the report)
