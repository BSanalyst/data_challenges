# Databricks Weekly Challenges

Welcome to the **Databricks Weekly Challenges** repository! This project is designed to engage the data community by providing weekly data analysis challenges using [Apache Spark](https://spark.apache.org/) in [Databricks](https://databricks.com/). Each challenge includes a publicly available dataset, a clear problem statement, and a solution, fostering learning and collaboration for data enthusiasts of all skill levels.

## Project Goals

The aim of this repository is to:
- **Educate**: Teach data processing, analytics, and visualization using Databricks and Spark.
- **Engage**: Offer fun, real-world challenges that encourage problem-solving and creativity.
- **Build Community**: Create a space for data professionals, students, and hobbyists to collaborate, share solutions, and learn from each other.
- **Leverage Open Data**: Use high-quality, publicly available datasets from sources like the [awesome-public-datasets repository](https://github.com/awesomedata/awesome-public-datasets).

## Challenge Structure

Each week, a new challenge is added to the repository, containing:
- **Dataset**: A manageable, open dataset (typically <2GB compressed) sourced from repositories like awesome-public-datasets.
- **Challenge Description**: A clear problem statement with objectives and constraints, designed to be accessible yet educational.
- **Solution**: A sample solution using PySpark in Databricks, demonstrating best practices for data processing.
- **Optional Extensions**: Suggestions for advanced analysis, visualizations, or machine learning to deepen learning.

Challenges are organized in folders (e.g., `week_01`, `week_02`), each containing:
- A dataset file or a link to the dataset.
- A markdown file (`challenge.md`) with the problem statement.
- A PySpark script (`solution.py`) with the solution.
- Additional resources or notebooks for context.

## Example Challenge
**Week 1: U.S. Domestic Flights On-Time Performance**
- **Dataset**: U.S. Domestic Flights 1990-2009 (~1.2GB compressed) from the U.S. Bureau of Transportation Statistics.
- **Task**: Identify the airline with the highest on-time departure percentage for each year.
- **Solution**: A PySpark script that loads CSV data, filters on-time flights, groups by year and airline, and ranks results.

## How to Contribute

We welcome contributions from the community! Here’s how you can get involved:
- **Suggest a Challenge**: Propose a new dataset or problem idea by opening an [Issue](https://github.com/your-username/databricks-weekly-challenges/issues) with details on the dataset (preferably from awesome-public-datasets) and task.
- **Submit a Solution**: Share your solution to a challenge by creating a Pull Request with your PySpark code or Databricks notebook in the relevant week's folder.
- **Improve Solutions**: Enhance existing solutions by optimizing code, adding visualizations, or suggesting extensions.
- **Provide Feedback**: Comment on challenges or solutions to help improve the project.

To contribute:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature/new-challenge`).
3. Add your challenge or solution in the appropriate folder.
4. Submit a Pull Request with a clear description of your changes.

Please follow our [Contributing Guidelines](CONTRIBUTING.md) and ensure datasets are publicly available and manageable in size.

## Getting Started

To participate:
1. Clone this repository: `git clone https://github.com/your-username/databricks-weekly-challenges.git`
2. Set up a [Databricks Community Edition](https://databricks.com/try-databricks) account (free) to run challenges.
3. Download the dataset for the current week (links provided in each challenge folder).
4. Run the provided PySpark solution or develop your own in Databricks.
5. Share your results or alternative solutions via Pull Requests or Issues!

## Why Join?

- **Learn Spark and Databricks**: Gain hands-on experience with big data tools.
- **Work with Real Data**: Explore diverse datasets, from flight records to public health data.
- **Collaborate**: Connect with a global community of data enthusiasts.
- **Build Your Portfolio**: Showcase your solutions in a public GitHub repository.

## Datasets

Challenges use datasets from the [awesome-public-datasets repository](https://github.com/awesomedata/awesome-public-datasets), ensuring high-quality, open data. Examples include:
- U.S. Domestic Flights (Bureau of Transportation Statistics)
- Public health datasets (e.g., CDC)
- Environmental data (e.g., NOAA)

Check each week's folder for specific dataset details and download instructions.

## License

This repository is licensed under the [MIT License](LICENSE). Datasets are subject to their respective licenses, as noted in each challenge.

## Contact

Have questions or ideas? Open an [Issue](https://github.com/your-username/databricks-weekly-challenges/issues) or join our community discussion (link to be added).

Happy analyzing, and let’s build a vibrant data community together!
