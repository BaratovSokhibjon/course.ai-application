# GitHub Copilot Instructions for AI Application Course

This repository is for studying and practicing concepts from the AI Application Systems course at Inha University. To get the most out of GitHub Copilot, follow these guidelines:

## General Coding Practices
- **Write clear, concise code**: Use meaningful variable and function names.
- **Keep notebooks minimal**: Use only necessary comments and print statements, avoid lengthy explanations.
- **Divide code into logical cells**: Separate imports, data setup, processing, and results into distinct cells.
- **Focus on functionality over documentation**: Let the code speak for itself with clear variable names.
- **Prefer Python and Jupyter Notebooks**: Most course work is in Python, using pandas, numpy, matplotlib, and seaborn.

## Copilot Usage Tips
- **Prompt Copilot with context**: Start comments or code cells with a clear description of your goal.
- **Review suggestions**: Always check Copilot's code for correctness and relevance.
- **Ask for explanations**: Use Copilot to explain code, suggest improvements, or generate visualizations.
- **Use Copilot for repetitive tasks**: E.g., data cleaning, plotting, or summary statistics.

## Project Structure
This repository is organized by **topics and concepts** rather than weeks, making it easier to find related content:

### Core Learning Topics
- `foundations/`: Basic Python, data structures, and course introduction
- `data-analysis/`: Exploratory data analysis, visualization, and statistical analysis
- `machine-learning/`: Supervised/unsupervised learning algorithms and model evaluation
- `deep-learning/`: Neural networks, computer vision, and NLP
- `applications/`: Real-world projects, case studies, and final project

### Supporting Materials
- `resources/`: Reference materials including lecture slides, papers, and cheat sheets
- `assignments/`: Course assignments organized by topic
- `.vscode/`: VS Code settings and this instruction file

### File Organization
- Each topic has `notebooks/` subdirectories for Jupyter notebooks
- Group related notebooks by specific concepts (e.g., classification, regression)
- Place small reference datasets in `resources/datasets/` (**avoid committing large files**)

## Best Practices for Notebooks
- **Import only necessary libraries**.
- **Separate code into logical cells**: One cell for imports, one for data setup, separate cells for each major operation.
- **Use minimal, functional comments**: Only comment what the code does, not why (unless complex logic).
- **Print only essential results**: Show original data, intermediate steps, and final verification.
- **Restart and run all cells before submission** to ensure reproducibility.
- **Handle missing values and outliers** as shown in class examples.
- **Create clean, focused visualizations** using matplotlib or seaborn.

## Example Copilot Prompts
- "# Import required libraries"
- "# Create dataset with missing values"
- "# Fill missing numeric values with median"
- "# Fill missing categorical values with mode"
- "# Verify all missing values handled"
- "# Create scatter plot"
- "# Calculate correlation coefficient"
- "# Train linear regression model"
- "# Build classification model"
- "# Perform K-means clustering"

## Topic-Specific Guidelines

### Data Analysis (`data-analysis/`)
- Focus on pandas, numpy, matplotlib, and seaborn
- Minimal data exploration - show dataset structure and key statistics only
- Use concise print statements to display results

### Machine Learning (`machine-learning/`)
- Use scikit-learn for traditional ML algorithms
- Show only essential metrics and results
- Separate model training, evaluation, and results into different cells

### Deep Learning (`deep-learning/`)
- Use TensorFlow or PyTorch
- Focus on code implementation over detailed explanations
- Show training progress with minimal output
- Display only final model performance

## Exclusions
- Do not commit large datasets (>10MB) - use `resources/datasets/` only for small reference files
- Ignore model checkpoints, outputs, and temporary files
- Avoid committing virtual environments and build artifacts
- Keep sensitive data and API keys out of the repository

## Workflow Tips
- Create topic-specific branches for major assignments
- Use descriptive commit messages that reference the topic area
- Keep notebooks focused on single concepts for better organization
- Cross-reference related notebooks in different topic areas when beneficial