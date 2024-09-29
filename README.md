# predicting-disease-causing-mutations

Creating a better understanding of how specific mutations can affect protein function and structure.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Abstract

Alzheimer’s Disease is the most common cause of dementia[1], causing loss of cognitive brain function and affecting over 55 million people worldwide[2]. The disease is generally not known to have an individual genetic cause, however, it is influenced by many genes as well as environmental factors and lifestyle[3]. Regardless of this, about two-thirds of the people with Alzheimer’s are women[4]. Using bioinformatics tools, we will investigate the risk of Alzheimer's development through genomics. This lets us better understand the genetic factors contributing to Alzheimer’s and may provide insights into developing targeted therapies.

We will focus on predicting the likelihood of Alzheimer’s in females based on the existence of specific single-nucleotide variants (SNVs) in their genetic code. Using Deep Genomics’ GenomeKit python repository to process a database of SNVs in women with and without Alzheimer’s and inputting this information into the Borzoi model, we can score variant effects across multiple layers of regulation. This streamlined approach could provide a foundation for diagnosing Alzheimer’s, emphasising prevention and early detection, ultimately contributing to effective disease management and highlighting the need for more research on how the disease affects women. 

Sources:  
[1] Podcasy, J. L., & Epperson, C. N. (2016, December). Considering sex and gender in alzheimer disease and other dementias. Dialogues in clinical neuroscience. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5286729/

[2] Alzheimer’s disease: Facts & figures. BrightFocus. (n.d.). https://www.brightfocus.org/alzheimers/article/alzheimers-disease-facts-figures 

[3] What causes alzheimer’s disease? | National Institute on Aging. National Institute on Aging. (n.d.). https://www.nia.nih.gov/health/alzheimers-causes-and-risk-factors/what-causes-alzheimers-disease 

[4] Why does alzheimer’s affect more women than men? BrightFocus. (n.d.-b). https://www.brightfocus.org/alzheimers/article/why-does-alzheimers-disease-affect-more-women-men 


## Installation

Provide instructions on how to install and set up the project, such as installing dependencies and preparing the environment.

```bash
# Example command to install dependencies (Python)
pip install project-dependencies

# Example command to install dependencies (R)
install.packages("project-dependencies")
```

## Quick Start

Provide a basic usage example or minimal code snippet that demonstrates how to use the project.

```python
# Example usage (Python)
import my_project

demo = my_project.example_function()
print(demo)
```
```r
# Example usage (R)
library(my_project)

demo <- example_function()
print(demo)
```

## Usage

Add detailed information and examples on how to use the project, covering its major features and functions.

```python
# More usage examples (Python)
import my_project

demo = my_project.advanced_function(parameter1='value1')
print(demo)
```
```r
# More usage examples (R)
library(demoProject)

demo <- advanced_function(parameter1 = "value1")
print(demo)
```

## Contribute

Contributions are welcome! If you'd like to contribute, please open an issue or submit a pull request. See the [contribution guidelines](CONTRIBUTING.md) for more information.

## Support

If you have any issues or need help, please open an [issue](https://github.com/hackbio-ca/predicting-disease-causing-mutations/issues) or contact the project maintainers.

## License

This project is licensed under the [MIT License](LICENSE).
