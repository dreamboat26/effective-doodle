# Accelerating Neural Network Training with OpenMP

<div align="center">
  <img src="https://github.com/user-attachments/assets/67115777-f519-4b30-81b8-2905c996a756" alt="snip">
</div>

## Abstract

The growing complexity of neural networks necessitates efficient training methodologies, especially for large-scale datasets like MNIST. This paper investigates the application of OpenMP for accelerating neural network training by leveraging its parallelization capabilities. By distributing computations across multiple threads, I aim to enhance training efficiency without compromising recognition accuracy. This study explores the impact of OpenMP configurations, including thread count and processor architecture variations, on training time and resource utilization. Preliminary results demonstrate significant reductions in training time and improved computational resource efficiency, providing valuable insights for optimizing parallel processing in neural network training workflows.

## Overview

This work explores the application of OpenMP for accelerating the training of neural networks in handwritten digit recognition. By leveraging OpenMP's parallelization capabilities, I aim to distribute computation across multiple threads, thereby enhancing efficiency.

## Paper
- A PDF copy of the full research paper is available in the `docs/` folder.

## Objectives

- Assess the impact of OpenMP on recognition accuracy.
- Evaluate training time and resource utilization.
- Explore variations in thread count, processor architectures, and dataset sizes using the MNIST dataset.

## Anticipated Outcomes

When I intially started the implementation I expected to achieve the following:
- Improved efficiency in training neural networks.
- Reduced training times.
- Valuable insights for optimizing OpenMP configurations in fashion recognition systems.

## Getting Started

### Prerequisites

- C/C++ compiler supporting OpenMP.
- Access to the MNIST dataset.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/dreamboat26/effective-doodle.git
   cd effective-doodle
   ```
2. Compile the source code with OpenMP support
3. Run training scripts:
4. Visualize the results

## Configuration

You can adjust the following parameters:

1. Thread Count: Modify the number of threads for OpenMP.
2. Processor Architecture: Test on different architectures as needed.
3. Dataset Size: Use different subsets of the MNIST dataset for experimentation.

## Results

The results will provide insights into:

1. Recognition accuracy improvements.
2. Training time reductions.
3. Resource utilization efficiency.

## Citation

If you use this repository or reference this work, please cite it as follows:

```bibtex
@article{mahule2024openmp,
  title={Training of Neural Network on a Fashion MNIST Dataset Using OpenMP for Image Recognition},
  author={Mahule, Roy},
  journal={IJCSPUB - International Journal of Current Science},
  volume={14},
  number={2},
  pages={477--485},
  year={2024},
  month={April},
  issn={2250-1770},
  url={https://rjpn.org/IJCSPUB/papers/IJCSP24B1055.pdf}
}
```
## Acknowledgements

I want to express my sincere gratitude to the open-source community for providing free access to Tensor Processing Units (TPUs) in Google Colab. This generous provision has been instrumental in advancing my work, allowing me to efficiently train and test my models. Furthermore, I would like to acknowledge the valuable contributions of research papers from Arxiv in this field. These papers have been foundational in shaping my understanding and guiding the development of 
my project. I deeply appreciate the collaborative spirit of the community and the continuous efforts to make advanced resources widely accessible.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
