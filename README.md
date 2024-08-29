# HRL Based Autonomous Trading Bot

Exploring the application of Reinforcement Learning (RL) in Finance through Hierarchical Reinforcement Learning (HRL) and other advanced methodologies like DQN.

## Overview

This project delves into the use of Hierarchical Reinforcement Learning (HRL) within financial contexts, aiming to optimize trading strategies by structuring decision-making in a multi-agent hierarchy. Additionally, it explores the use of GAN-based synthetic data generation and advanced data ingestion techniques to support these financial models.

## Features

- **Hierarchical Reinforcement Learning (HRL)**: Implements a hierarchy of RL agents, where:
  - The **higher-level agent** selects equities to trade and allocates portfolio sizes.
  - The **middle agent** chooses trading strategies based on indicator data.
  - The **lower-level agent** executes trades and manages risk through stop-loss mechanisms.
  
- **DQN-Based HRL**: One of the HRL implementations leverages Deep Q-Networks (DQN) to enhance decision-making processes within the hierarchy.

- **GAN-Based Synthetic Data Generation**: A notebook dedicated to generating synthetic financial data using Generative Adversarial Networks (GANs), aimed at augmenting the training dataset and improving model robustness.

- **Data Ingestion and Processing**: Another notebook focuses on ingesting, cleaning, and processing financial data, preparing it for use in RL models.

## Notebooks

- **Simple HRL Implementation**: Demonstrates a straightforward HRL model applied to equity trading.
- **DQN-Based HRL**: Shows how DQN can be integrated within the HRL framework to improve trading strategies.
- **GAN-Based Data Generator**: Details the process of creating synthetic financial data using GANs.
- **Data Ingestion**: Explains the steps involved in preparing financial data for model training and testing.

## Environment

The project is designed to work within a Python-based environment, leveraging libraries such as TensorFlow, PyTorch, and various financial data handling packages. The setup is straightforward and ensures reproducibility of experiments across different systems.

## Contributing

Contributions are welcome! Whether it's improving the existing models, adding new RL algorithms, or refining the synthetic data generation process, your input is valuable. Please fork this repository and submit a pull request with your changes. Issues and questions can be discussed through the issue tracker.

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.

## Contact

For questions, discussions, or collaborations, please reach out via [email](mailto:your-email@example.com).
 
