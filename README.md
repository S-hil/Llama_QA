# SafetyNet: Llama Guard Integration and Testing

SafetyNet is a comprehensive testing framework designed to integrate with Meta-Llama's Llama-Guard-7b, providing robust safety assessments for conversational AI interactions. This repository contains all necessary components to evaluate and ensure that user inputs or AI-generated outputs adhere to strict safety policies, focusing on preventing harmful or inappropriate content from permeating AI applications.

## Key Features

- **Llama Guard Integration**: Utilizes Meta-Llama's Llama-Guard-7b model to assess text for potential safety violations, wrapped within a user-friendly Python interface.
- **Comprehensive Test Suite**: Includes a suite of automated tests designed to validate the safety assessment across various content categories, ensuring thorough coverage and reliability.
- **Customizable Safety Policies**: Supports evaluation against predefined safety categories, including violence, sexual content, criminal planning, and more, with the flexibility to adapt to specific application needs.
- **Error Handling and Reporting**: Implements robust error handling to gracefully manage and report issues encountered during safety assessments, enhancing reliability and user experience.
- **Jupyter Notebook Integration**: Offers a Jupyter Notebook setup for interactive testing and demonstration purposes, making it easy to showcase and explore functionality.

## Technologies Used

- Python
- Jupyter Notebooks
- Meta-Llama's Llama-Guard-7b model
