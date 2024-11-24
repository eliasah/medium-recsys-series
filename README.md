[![GitHub stars](https://img.shields.io/github/stars/eliasah/medium-recsys-series?style=social)](https://github.com/eliasah/medium-recsys-series/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/eliasah/medium-recsys-series?style=social)](https://github.com/eliasah/medium-recsys-series/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with ❤️ by eliasah](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20by-eliasah-red)](https://github.com/eliasah)

# Recommender Systems Series

This repository accompanies a comprehensive blog series on recommender systems published on [Medium](https://medium.com/@eliasah). The series progresses from theoretical foundations to practical implementations, providing both conceptual understanding and hands-on coding examples.

## Series Structure & Content

### Part 1: Theory & Foundations
1. [Introduction to Recommender Systems: A Personalized Experience](https://medium.com/@eliasah/introduction-to-recommender-systems-a-personalized-experience-839b63a5e98f)
    - Foundational concepts and terminology
    - Overview of recommender system types
    - Real-world applications and use cases
    - Business impact and considerations
    - *No companion notebook (theoretical focus)*

### Part 2: Basic Implementation
2. [Delving Deeper into Recommender Systems: From Basics to State-of-the-Art](https://medium.com/@eliasah/delving-deeper-into-recommender-systems-from-basics-to-state-of-the-art-d92ee8e277f2)
    - Evolution of recommender systems
    - Implementation of three fundamental approaches:
        - User-Based Collaborative Filtering
        - Item-Based Collaborative Filtering
        - Matrix Factorization using SVD
    - 📓 [`2.Delving Deeper into Recommender Systems.ipynb`](notebooks/2.Delving%20Deeper%20into%20Recommender%20Systems.ipynb)
        - Working implementation using MovieLens 100K dataset
        - Practical examples of each approach

### Part 3: Advanced Techniques
3. [Deep Dive into Matrix Factorization for Recommender Systems](https://medium.com/@eliasah/deep-dive-into-matrix-factorization-for-recommender-systems-from-basics-to-implementation-79e4f1ea1660)
    - In-depth exploration of matrix factorization
    - Advanced implementation techniques
    - Two complementary notebooks:
        - 📓 [`3.1.Understanding Matrix Factorization Step by Step.ipynb`](notebooks/3.1.Understanding%20Matrix%20Factorization%20Step%20by%20Step.ipynb)
            - Core algorithm implementation
            - Detailed explanations of each component
        - 📓 [`3.2.Deep Dive into Matrix Factorization for Recommender Systems.ipynb`](notebooks/3.2.Deep%20Dive%20into%20Matrix%20Factorization%20for%20Recommender%20Systems.ipynb)
            - Comprehensive examples
            - Visualization tools
            - Performance analysis

4. Introduction to Recommender System Evaluation Beyond Accuracy (Coming Soon)

## Repository Structure

```
.
├── LICENSE
├── README.md
├── data
│   └── ml-100k                  # MovieLens 100K dataset
├── notebooks
│   ├── 2.Delving Deeper into Recommender Systems.ipynb
│   ├── 3.1.Understanding Matrix Factorization Step by Step.ipynb
│   └── 3.2.Deep Dive into Matrix Factorization for Recommender Systems.ipynb
└── requirements.txt
```

## Data Sources

The repository utilizes two types of data:

1. **MovieLens 100K Dataset**
    - Located in `data/ml-100k/`
    - Used in Part 2 for demonstrating collaborative filtering approaches
    - Contains user-movie ratings and movie metadata

2. **Synthetic Data**
    - Generated within the Part 3 notebooks
    - Used for demonstrating matrix factorization concepts
    - Provides controlled examples for learning

## Installation

```bash
conda create -n medium-recsys-series python=3.10 jupyterlab
conda activate medium-recsys-series
pip install -r requirements.txt
```

## Getting Started

1. Start with the Part 1 blog post for theoretical foundations
2. Move to Part 2 for basic implementations:
    - Read the blog post
    - Follow along with the notebook using the MovieLens dataset
3. Progress to Part 3 for advanced techniques:
    - Start with notebook 3.1 for core implementation
    - Move to 3.2 for comprehensive examples

## Contributing

If you find any issues with the code examples or have suggestions for improvement, please feel free to open an issue or submit a pull request. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For any questions or inquiries, please contact me via:
- LinkedIn: [Connect with me](https://www.linkedin.com/in/eliasah)

Happy exploring the world of recommender systems! 🚀