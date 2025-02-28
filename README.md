# A dataset of interactions and emotions for website user experience evaluation

This repository contains Python code accompanying the dataset released with the article *"A dataset of interactions and emotions for website user experience evaluation."* The dataset aims to support research in user experience (UX) analysis, particularly focusing on the interplay between user interactions and emotional responses.

## Repository Structure

This repository includes multiple Git submodules that point to relevant codebases used for data collection, processing, and analysis:

- **[browser-extension](https://github.com/your-org/browser-extension)**: Contains the source code for the browser extension used to collect user interaction data.
- **[emotion-analysis](https://github.com/your-org/emotion-analysis)**: Provides C++ code for server-side emotion detection based on user headshots, enabling on-premise analysis without external API dependencies.
- **[dataset-preprocessor](https://github.com/your-org/dataset-preprocessor)**: Includes Python scripts for preprocessing and structuring the collected dataset.
- **[server](https://github.com/your-org/server)**: Implements the backend server that facilitates communication between the browser extension and the data processing pipeline.

## Cloning the Repository

Since this repository contains submodules, make sure to clone it recursively:

```bash
git clone --recurse-submodules https://github.com/uxsad/dataset-tools.git
```

If you have already cloned the repository without submodules, you can initialize them separately:

```bash
cd dataset-tools
git submodule update --init --recursive
```

### Further Documentation
Please refer to the various sub-repositories for specific documentation.

<!--
## Citation
If you use this dataset or the accompanying code in your research, please cite:

```
@article{yourcitation,
  title={A dataset of interactions and emotions for website user experience evaluation},
  author={Your Name and Others},
  journal={Nature Scientific Data},
  year={2025}
}
```
-->

## License
This repository is licensed under the [GNU GPL v3](LICENSE).

## Contact
For any questions, please open an issue or reach out to the corresponding author of the dataset article.

