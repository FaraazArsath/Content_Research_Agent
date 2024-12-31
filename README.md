# Content_Research_Agent

## Overview
This repository contains a Google Colab notebook leveraging the Crew AI framework and the LLM model **Chat Cohere** to create and manage three agents for content planning, writing, and editing. The project demonstrates the use of the `Markdown` module from `IPython.display` to render results dynamically within the notebook.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Colab Notebook](#colab-notebook)
- [Contributing](#contributing)
- [License](#license)

## Features
- Uses Crew AI framework and LLM model **Chat Cohere** to create three specialized agents:
  - **Planner**: Generates structured plans for content creation.
  - **Writer**: Drafts content based on the planner's output.
  - **Editor**: Reviews and refines the written content.
- Dynamic content rendering using:
  ```python
  from IPython.display import Markdown
  Markdown(result)
  ```
- Fully integrated workflow within a single Colab notebook.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/FaraazArsath/Content_Research_Agent.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Content_Research_Agent
   ```
3. Install dependencies (if applicable):
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Colab notebook:
   ```bash
   https://colab.research.google.com/github/FaraazArsath/Content_Research_Agent/blob/main/your-notebook.ipynb
   ```
2. Run each cell sequentially to:
   - Initialize agents.
   - Plan, write, and edit content dynamically using **Chat Cohere**.
   - View rendered results using the Markdown module.

## Colab Notebook
We have included a Google Colab notebook for easy execution and experimentation. To use it:
1. Navigate to the [Colab Notebook](https://colab.research.google.com/github/FaraazArsath/Content_Research_Agent/blob/main/your-notebook.ipynb).
2. Open the notebook in Google Colab.
3. Execute the cells as described in the [Usage](#usage) section.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).




