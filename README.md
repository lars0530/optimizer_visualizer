# Optimizer Visualizer

This repository contains interactive visualizations of different optimization algorithms used in machine learning. By exploring this repository, you'll gain an understanding of how different optimizers behave and how various hyperparameters affect their performance. The repository includes a main notebook for visualizing optimizers, a compatibility check script, and a solutions script.

The Optimizer Visualizer was originally created for a university class about Deep Learning with Python at the University of Münster.

## Files in the Repository

1. **compatibility_check.ipynb**: 
   - A simple Jupyter Notebook for ensuring that the plotting and interactive elements are working correctly. It plots a linear function based on the parameters `a` and `b`. It includes interactive sliders for adjusting these parameters and visualizing their impact on the function.

2. **optimizer_lecture.ipynb**: 
   - This Jupyter Notebook provides an interactive lecture on optimization algorithms. It includes various sections with tasks and visualizations to help understand different optimizers such as Regular Gradient Descent, Momentum, Nesterov Accelerated Gradient, AdaGrad, RMSProp, and Adam. Additionally, there's a section to create your own custom optimizer.

3. **optimizer_lecture_solutions.py**: 
   - This script contains the solutions for the tasks presented in the `optimizer_lecture.ipynb` notebook. It can be used as a reference to check your work or to understand the implementation details of different optimization algorithms.

## How to Use

### Jupyter Notebook
To use the `optimizer_lecture.ipynb`:
1. Clone the repository:
    ```bash
    git clone https://github.com/lars0530/optimizer_visualizer.git
    cd optimizer_visualizer
    ```
2. Run the `compatibility_check.ipynb` notebook to test if all required packages are installed.
If not, install using
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook optimizer_lecture.ipynb

   # or using code
   code .
   ```
3. Follow the instructions in the notebook to execute each cell, visualize the optimizers, and complete the tasks.

## Interactive Visualization

The main feature of this repository is the interactive visualization tool included in the Jupyter Notebook. Here are some of the functionalities you can explore:

- **Compare Optimizers**: Select multiple optimizers to see how they behave with different starting points and learning rates.
- **Adjust Hyperparameters**: Use sliders to adjust hyperparameters like learning rate and beta values for momentum-based optimizers.
- **Explore Different Functions**: Test the optimizers on various functions such as Steep Valley, Symmetric Convex, Asymmetric Convex, and L-shaped Valley functions.

## Questions to Explore

While using the notebook, consider the following questions to deepen your understanding:

- How do different starting points affect the convergence of the optimizers?
- How does adjusting the learning rate impact the optimization path?
- What is the effect of the beta parameter in momentum-based optimizers?
- How do different learning rate schedules influence the performance of the optimizers?

## Contributions

Contributions to this repository are welcome. If you have any improvements or additional features you'd like to add, feel free to open a pull request.

## License

This repository is licensed under the MIT License. See the LICENSE file for more details.

---

Enjoy exploring and visualizing different optimization algorithms! If you have any questions or feedback, please don't hesitate to reach out.