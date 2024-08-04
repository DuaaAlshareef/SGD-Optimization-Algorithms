# SGD Optimization Experiments

This project explores various techniques to enhance the convergence and performance of SGD in optimizing machine learning models. The experiments compare different variants of SGD and Gradient Descent (GD) to determine the most effective methods for achieving stable and accurate solutions.

## Repository Structure
- **Report:** The detailed report of our experiments is available [here](link-to-SGD_FINAL_LAB_REPORT.pdf).
- **Code:** The code for running the experiments and generating the plots.
- **Data:** Synthetic datasets used for linear and logistic regression experiments.


## Experiments Overview

### Samples from the Report

#### Key Graphs
<p align="center">
  <img src="path-to-convergence-plot.png" alt="Convergence Plot" width="45%">
  <img src="path-to-loss-function-vs-iterations.png" alt="Loss Function vs Iterations" width="45%">
  <img src="path-to-sgd-switch-to-shrinking.png" alt="SGD Switch to Shrinking" width="45%">
  <img src="path-to-sgd-with-averaging.png" alt="SGD with Averaging" width="45%">
</p>

In our experiments, we investigated the performance of various SGD techniques to improve convergence and accuracy. The convergence plot shows that SGD with averaging leads to rapid and stable convergence, significantly outperforming SGD without replacement and traditional GD. The loss function vs. iterations graph highlights the effectiveness of shrinking step sizes in achieving more stable and accurate convergence compared to constant step sizes. By switching from constant to shrinking step sizes, we observed initial rapid progress followed by stable long-term convergence. Additionally, averaging updates in the later stages of optimization proved beneficial for reducing variability and enhancing model accuracy. These visualizations collectively demonstrate the advantages of different SGD strategies in optimizing machine learning models.




## How to Use
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/sgd-optimization-experiments.git
   
